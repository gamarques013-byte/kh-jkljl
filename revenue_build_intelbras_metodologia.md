# Revenue build da Intelbras por market share × tamanho de mercado

Como montar o modelo de receita no estilo da WSP (exemplo da Dell no guia "Projecting the 3 Statements", p.7). Os cases (conservador, base, upside, street) ficam para depois.

---

## 1. A ideia e quando ela funciona

O guia da WSP lista três formas de projetar receita:

1. taxa de crescimento simples;
2. unidades × preço médio;
3. **market share × tamanho de mercado**.

A terceira serve quando a empresa vende centenas de produtos e o mercado tem **tamanho conhecido e poucos grandes players** ("3-4 major players"). A WSP diz que o número final não muda muito. O que muda é que **cada premissa fica defensável**: "o mercado cresce X% por causa de Y, e mantemos o share em Z% porque W".

No exemplo da Dell, **só Servers and Networking** usa share × mercado. As outras linhas usam crescimento simples. A Intelbras pede o mesmo tratamento misto:

| BU | Share (MIDI, FRE 2026) | Encaixa em share × mercado? | Método sugerido |
|---|---|---|---|
| Segurança | 44% (2025), 43% (2024) | **Sim.** Líder, mercado medido, poucos rivais grandes | Share × mercado |
| TIC | 9% (2025 e 2024) | **Fraco.** Universo amplo e fragmentado (Huawei, Cisco, TP-Link…). O share arredondado gera ruído enorme (ver 3.2) | Drivers por linha |
| Energia sem solar | 19% | Sim, mas a receita sem solar não é divulgada | Share × mercado, com a receita solar estimada |
| Solar | 1,9% | Sim, em **unidades**: GW instalados × share × R$/W | Unidades × preço × share |

---

## 2. A equação e os blocos da planilha

**Fórmulas**

- Receita da BU no ano *t*: `Receita(BU, t) = Mercado(BU, t) × Share(BU, t)`
- Mercado no ano *t*: `Mercado(BU, t) = Mercado(BU, t−1) × (1 + g(BU, t))`

**Blocos, como na imagem da Dell**

1. **Receita por BU**: histórico de 2021 a 2025, projeção de 2026E a **2036E** (11 anos, em três fases; ver seção 6).
2. **Tamanho de mercado por segmento**: em R$ mi.
3. **Crescimento do mercado**: a premissa principal, com os drivers ao lado.
4. **Market share por BU**: a segunda premissa.
5. *(Depois)* **Cases de share e de crescimento**: conservador, base, upside e street, mais o case selecionado (com `CHOOSE` ou `INDEX`).

---

## 3. Passo 1: tamanho de mercado no ano-base (calibração)

### 3.1 Segurança

O mercado do ano-base sai da própria receita, `Mercado = Receita ÷ Share`. Assim, o modelo **fecha com a receita reportada** no ano-base.

| Segurança | 2024 | 2025 |
|---|---|---|
| Receita líquida (R$ mi) | 2.602,7 | 2.730,3 (+4,9%) |
| Share MIDI | 43% | 44% |
| **Mercado implícito (R$ mi)** | 2.602,7 ÷ 0,43 = **6.053** | 2.730,3 ÷ 0,44 = **6.205** |
| Crescimento implícito | | 6.205 ÷ 6.053 − 1 = **+2,5%** |

> **Confira o slide 20 do seu case.** Ele mostra mercado de R$6,48 bi (2024) e ~R$7,2 bi (2025). Pela conta acima, o mercado é de R$6,05 bi e R$6,21 bi. A conta de controle não fecha: 7,2 × 44% = R$3,17 bi, contra R$2,73 bi de receita.
>
> Se o R$7,2 bi vier de outra fonte, use o **share calibrado**: 2.730 ÷ 7.200 = **37,9%**. Share e mercado precisam ter **a mesma definição**: R$ líquido, mesmo perímetro. Pelos dois números do slide, o mercado cresceu +11% em 2025, contra +2,5% pela receita.

### 3.2 O problema do share arredondado

O FRE diz "mais de 44%", ou seja, um share entre 44,0% e 44,9%.

**Segurança.** O crescimento implícito de 2025 pode ir de `1,049 × 43/45 − 1 = +0,2%` a `1,049 × 44/44 − 1 = +4,9%`. É um intervalo grande, mas utilizável.

**TIC.** A receita caiu 8% (977,2 ÷ 1.062,2 = 0,920). Com share "mais de 9%" nos dois anos, o crescimento implícito do mercado vai de `0,920 × 9/10 − 1 = −17,2%` a `0,920 × 10/9 − 1 = +2,2%`. **Esse intervalo não serve para premissa.**

Por isso, em TIC o mercado do MIDI serve no máximo como ordem de grandeza: 977 ÷ 0,09 ≈ R$10,9 bi.

### 3.3 Ressalvas do MIDI (FRE 1.4)

1. **Só a controladora.** A receita consolidada por BU inclui Seventh (Segurança), Khomp e Décio (TIC) e Renovigi (Energia). O erro é pequeno em Segurança e maior em TIC e Energia.
2. **Base em importações.** O MIDI usa dados da Comex Stat em R$. O mercado em R$ **mexe com o câmbio** (ver 4.1).
3. **Quebras de definição.** A série antiga media só CFTV: 43% em 2020, segundo o BTG CEO Conference 2021. O TIC de 2020 (redes + comunicação) era de R$3,3 bi. **Não emende séries antigas com a de 2024–25.** Use só o ano-base atual e projete daí para frente.

---

## 4. Passo 2: crescimento do mercado (a premissa que importa)

**Regra de ouro.** O mercado projetado tem que vir de **fontes externas**. Se você deriva o crescimento do mercado do histórico da própria Intelbras, o método vira "taxa de crescimento com passos extras". No histórico, o ajuste é perfeito por construção (mercado = receita ÷ share), então isso não prova nada.

**Use o nível do MIDI e o crescimento de fontes externas trianguladas.** Os relatórios de mercado (MarketsandMarkets, IMARC) têm escopos e moedas diferentes. Use as **taxas de crescimento**, nunca o nível.

### 4.1 Decomponha o crescimento em R$

A fórmula:

```
(1 + g_R$) = (1 + g_volume) × (1 + g_preço em US$) × (1 + g_câmbio)
```

**Exemplo só da mecânica.** Premissas:

- volume +6%;
- preço em US$ −2% (deflação de câmeras chinesas);
- dólar médio de 5,58 (2025) para 5,29 (1S26), ou −5,2%.

A conta: 1,06 × 0,98 × 0,948 = 0,985, ou seja, **−1,5% em R$**. O mercado cai em R$ mesmo com 6% mais equipamentos instalados. Essa é a pegadinha.

O efeito contrário apareceu no 2T26. A Intelbras **reajustou preços pelo custo de reposição** (alta de commodities e memórias). O preço em R$ subiu com o dólar caindo. Por isso, separar volume, preço e câmbio explica 2026 melhor do que um crescimento único.

### 4.2 Drivers por BU

**Segurança**

| Driver | Dado | Uso |
|---|---|---|
| Vídeo (CFTV) | MarketsandMarkets: US$495,6 mi (2025) → 606,3 mi (2030), **3,4% a.a.** | Crescimento do sub-segmento CFTV (US$) |
| Controle de acesso | IMARC: US$587 mi (2025) → 1.279 mi (2034), **9,0% a.a.** | Crescimento do sub-segmento de acesso (US$) |
| Peso dos sub-segmentos | BTG21: CFTV R$2,2 bi, acesso R$1,2 bi (2020) → 65% / 35% | Pondera os dois: 0,647 × 3,4% + 0,353 × 9,0% ≈ **5,4% a.a. em US$** |
| Obra (com defasagem) | Lançamentos: 471,8 mil unidades em 2025, +13,9% (CBIC); PIB da construção +2% em 2026 (CBIC) | Segurança entra no acabamento: lançamento de *t* vira instalação em *t*+2 a *t*+3 |
| Retrofit e condomínio | 13,3 mi unidades em condomínio; portaria remota +24% (Abese) | Volume do instalador |
| Cidades inteligentes | MarketsandMarkets: 17,1% a.a. (2025–30); Statista ~12% a.a. | Cresce rápido, mas a Intelbras captura pouco (ver 5.1) |
| **Não use como mercado** | Abese: R$14 bi, +16,1% (2024) | Inclui serviços (monitoramento, portaria) |

**TIC.** Modele por linha, com drivers. O release do 2T26 dá a composição qualitativa:

| Linha | Driver | Observação |
|---|---|---|
| Cabos ópticos | **Capacidade**, não mercado | Antidumping desde dez/25. Tubarão opera "próxima à capacidade máxima" e deve ficar assim. Receita = capacidade × preço. Cresce com preço e com eventual expansão |
| Redes empresariais e cabeamento | Investimento de PMEs | "Crescimento constante" (2T26). Proxies: intenção de investir da pequena indústria (CNI) e Selic. Wi-Fi Brasil: MarketsandMarkets 16,5% a.a., otimista e em US$ |
| GPON | Capex dos ISPs; banda larga +2,7% | Redução **deliberada** (risco de crédito). Premissa de queda ou estabilidade |
| Comunicação (telefonia) | Declínio secular | Crescimento negativo |

A receita por linha não é divulgada. Na prática, a TIC vira **uma linha com crescimento ponderado por esses drivers**, e você explica os pesos no texto. É o "método 1" da WSP, só que justificado.

**Energia sem solar**

- Nobreaks e fontes são satélites de Segurança e TIC: mesmo instalador, mesmo projeto. Um driver razoável é **o crescimento do mercado de Segurança**, mais algo pelos carregadores.
- A frota de eletrificados chegou a 613 mil, +64% (FRE).
- UPS de data center (MarketsandMarkets, 8,4% a.a.) é outro produto. Não use.

**Solar.** Projete em unidades:

```
Receita solar = GW de GD adicionados × Share (MW) × R$/W do kit
```

**Estimativa de 2025.** Premissas: 7,8 GW de GD × 1,9% ≈ 148 MW; kit (equipamento sem instalação) de ~R$1,5–2,0/W, abaixo dos R$2,91/Wp do sistema residencial instalado.

- Receita solar: **R$220–300 mi**.
- Energia sem solar: 753 − ~260 ≈ **R$490 mi**.
- Mercado sem solar: 490 ÷ 0,19 ≈ **R$2,6 bi**.

**É estimativa.** Calibre com o RI se encontrar o peso de solar em Energia.

- **Teste de sanidade de 2022.** Share solar de 4,3% × ~8 GW × ~R$3,5/W ≈ R$1,2 bi, perto do pico de Energia (R$1,4 bi).
- **Drivers:** projeção da Absolar, Fio B (60% em 2026, 75% em 2027, 90% em 2028) e preço por watt em queda.
- **Confira:** há fontes que citam 10,6 GW como adição de 2025 e outras como projeção de 2026.

---

## 5. Passo 3: market share

### 5.1 Segurança: o share é uma média ponderada

A ideia do slide de Segurança (líder no instalador, coadjuvante nas cidades) vira matemática:

```
Share total = Share no instalador × peso do instalador + Share em projetos e cidades × peso de projetos
```

**Exemplo só da mecânica:** 50% de share no instalador e 15% em projetos dão ~44% hoje. Se projetos crescem mais rápido, o **share total cai sem a Intelbras perder nenhum cliente**. Esse é o efeito mix.

**Defina os pesos** a partir do que você tem:

- canais: integradores e contas nomeadas ≤16% das vendas;
- o FRE fala em "evolução de participação" em CFTV IP e projetos.

**Leitura dos dados.** Share estável em 43–44% e o FRE fala em "estabilidade de market share". A premissa defensível é **share estável**. Ganho de share precisa de evidência (CFTV IP, projetos). Perda precisa de mecanismo (Hikvision em Manaus com paridade de incentivo depois da reforma; Dahua com distribuidores próprios).

### 5.2 Para a tese de compra

- **Não ponha o upside no share.** O seu próprio deck diz que a captura está ameaçada (Hikvision, Dahua, P&D 51x). Se a receita assumir share subindo, o avaliador aponta a contradição.
- Uma tese de compra mais robusta: **o mercado cresce, o share resiste, e o valor vem de margem, caixa e ROIC**. Isso bate com a nova gestão ("menor receita, maior rentabilidade"), o FCL LTM de R$786 mi antes do giro e o estoque normalizado.
- O revenue build deve ser **conservador e crível**. O upside vem de onde você tem evidência.

---

## 6. Horizonte até 2036: três fases

O exemplo da Dell projeta 5 anos. Com 11 anos, os drivers detalhados perdem sentido depois de ~3 anos, e as fontes externas acabam antes de 2036 (MarketsandMarkets vai até 2030, IMARC até 2034). Por isso, o crescimento precisa **convergir**.

### 6.1 As fases

| Fase | Anos | Crescimento do mercado | Share | Fontes |
|---|---|---|---|---|
| **1. Drivers explícitos** | 2026–2028 | Volume × preço × câmbio, por BU | Último observado (44%, 9%, 19%, 1,9%) | 1S26 realizado, Focus, lançamentos com defasagem, Absolar, capacidade de cabos |
| **2. Eventos e convergência** | 2029–2033 | Converge linearmente para o longo prazo | **Onde os cases vão diferir** (eventos abaixo) | Calendário regulatório e contratual |
| **3. Estado estável** | 2034–2036 | = crescimento da perpetuidade | Constante | — |

**Fórmula da convergência (fade linear)**, da fase 1 até 2036:

```
g(t) = g(2028) + [g(LP) − g(2028)] × (t − 2028) ÷ (2036 − 2028)
```

**Exemplo só da mecânica.** Com g(2028) = 7,0% e g(LP) = 5,6%, o crescimento cai 0,175 p.p. por ano: 7,0% → 6,8% (2029) → 6,7% → 6,5% → 6,3% → 6,1% → 6,0% → 5,8% → **5,6% (2036)**.

### 6.2 O crescimento de longo prazo

- **Nominal em R$** = (1 + PIB real) × (1 + IPCA) − 1. Com o Focus de 2029 (PIB 2,0%, IPCA 3,5%): 1,02 × 1,035 − 1 = **5,6% a.a.**
- **Câmbio além do Focus.** Paridade de poder de compra: o real se desvaloriza (1 + IPCA) ÷ (1 + inflação dos EUA) − 1 = 1,035 ÷ 1,02 − 1 = **1,5% a.a.** De R$5,50 em 2029, chega a 5,50 × 1,0147⁷ ≈ **R$6,09 em 2036**. Só use câmbio se a BU estiver decomposta em US$; nas fases 2 e 3, o nominal em R$ basta.
- **Por BU**, como ponto de partida:
  - Segurança: perto do PIB nominal (~5,6%). Ainda há penetração para crescer: só 17% dos domicílios tinham alarme ou câmera em 2021.
  - TIC e solar: perto do IPCA (~3,5%). Hardware maduro e deflacionário.
  - Energia sem solar: acompanha Segurança, porque é satélite dela.
- **Amarração com o DCF.** O crescimento de 2036 tem que ser **igual ao g da perpetuidade**. Se a receita cresce 8% em 2036 e a perpetuidade usa 4%, o valor terminal fica inconsistente.

### 6.3 Eventos dentro do horizonte

Eles mexem em share e preço, não só em margem:

| Quando | Evento | BU | Efeito no revenue build |
|---|---|---|---|
| mai/2026 → | Imposto de importação zerado no cross-border até US$50 | TIC, varejo de Segurança | Pressão de share no varejo |
| ago/2028 | Fim da autorização de venda das ações da Dahua | Segurança | Sinal sobre a relação |
| **dez/2028** | **Vence o acordo de cooperação Intelbras–Dahua** | Segurança | Maior risco de share do horizonte: renovação, troca de fornecedor ou competição direta |
| 2028–2029 | Fio B a 90%; regras da Aneel a partir de 2029 | Solar | Volume de geração distribuída no piso |
| 2029 | Fim da Lei de TICs | Todas | Se a Intelbras repassar o fim do crédito ao preço, perde share |
| 2029–2032 | Transição do ICMS (incentivos de SC, MG e PE caem; a Zona Franca de Manaus fica) | Todas | Hikvision em Manaus ganha paridade relativa → risco de share em Segurança |
| dez/2030 | Fim do antidumping de fibra (5 anos) | TIC | Cabos: preço normaliza; a limitação de capacidade deixa de valer |

Na fase 2, o share de Segurança é a premissa que separa os cases. Por isso, deixe uma **linha de share com as datas desses eventos** já na estrutura.

### 6.4 Testes de sanidade para 11 anos

**1. Juros compostos amplificam erro.** Receita de Segurança em 2036:

- crescendo 6% a.a.: 2.730 × 1,06¹¹ = **R$5,18 bi**;
- crescendo 7% a.a.: 2.730 × 1,07¹¹ = **R$5,75 bi**.

Um ponto a mais de crescimento dá **+10,9%** de receita no ano terminal. Com 11 anos explícitos, a trajetória pesa mais no valor do que num modelo de 5 anos.

**2. Decomponha o múltiplo de 2036.** Mercado de Segurança: 6.205 × 1,056¹¹ ≈ **R$11,3 bi**, ou 1,82x o de hoje.

- Inflação: 1,035¹¹ = 1,46x.
- Volume real: 1,02¹¹ = 1,24x.

Pergunte se 2% a.a. reais de volume por 11 anos é crível: domicílios, condomínios, penetração de 17%, preço por câmera caindo.

**3. Mix de receita.** Segurança é 61% da receita hoje. Se cresce acima de TIC e Energia, chega a 2036 maior. Isso eleva a margem consolidada pelo mix, um argumento a favor da tese de compra que **não depende de ganhar share**.

**4. Share × mercado em 2036.** Verifique se o share implícito é coerente com o que a fase 2 assumiu sobre Hikvision e Dahua.

---

## 7. Âncoras para calibrar (não são cases)

**1S26 realizado.** Receita de R$2.259,7 mi (+4,2%):

| BU | 1S26 (R$ mi) | Variação |
|---|---|---|
| Segurança | 1.380,9 | +5,8% (release: "reflete o mercado em geral", ou seja, share estável) |
| TIC | 535,4 | +13,7% |
| Energia | 343,4 | −12,4% |

O 2026E deve ser `1S26 real + 2S26E`, e o 2S25 foi de R$2.292,7 mi. **Não projete 2026 do zero.**

**Sell-side.** A WSP inclui um "Street Consensus Case":

| Casa | Projeção de receita |
|---|---|
| JP Morgan | 2S26 +3,1% (neutro desde set/26, alvo R$18,50) |
| XP | 2026 +0,5% |
| Ágora | 2026 estável, 2027 ~+8% |
| Bradesco BBI | Compra, alvo R$18 |

São resumos de imprensa. Confirme nos relatórios.

**Macro (Focus).** PIB de 2027 ~1,5–1,7%, IPCA de 2027 ~3,8–4,3%. As edições encontradas divergem; confira a mais recente no BCB.

---

## 8. Armadilhas

1. **Definição de share ≠ definição de mercado.** Share e mercado da mesma fonte e perímetro; senão, use o share calibrado (3.1).
2. **Usar o nível de relatórios em US$** (MarketsandMarkets US$496 mi vs. MIDI ~US$1,1 bi). Use só o crescimento e converta o câmbio.
3. **Abese como mercado.** Inclui serviços e superestima o crescimento.
4. **Extrapolar crescimento implícito ano a ano.** O arredondamento do share gera ruído de ±2–10 p.p.
5. **Circularidade.** O mercado projetado com base no histórico da própria Intelbras não acrescenta nada.
6. **Nominal × real.** Mercados em R$ nominais carregam preço e câmbio. Não compare com o PIB real sem somar inflação.
7. **Defasagem de obra.** Lançamento não vira câmera no mesmo ano.
8. **Capacidade.** Em cabos ópticos, a demanda protegida esbarra na fábrica. Share × mercado superestimaria a receita.
9. **Estender CAGRs de relatórios além da janela deles.** MarketsandMarkets 2025–30 não vale para 2031–36. Depois da janela, use o fade.
10. **Crescimento de 2036 ≠ g da perpetuidade.** O valor terminal fica inconsistente.
11. **Share constante com mix mudando.** Se cidades e projetos crescem mais rápido e a Intelbras captura pouco, o share total cai (5.1).

---

## 9. Dados que ainda faltam

- [ ] Fonte do mercado de R$7,2 bi no slide 20 (e a definição).
- [ ] Peso de solar na receita de Energia, ou R$/W de kit da Renovigi.
- [ ] Projeção da Absolar para GD em 2026–27 (confirmar 10,6 GW).
- [ ] Focus mais recente (PIB, IPCA, câmbio, Selic 2026–30).
- [ ] Lançamentos de 2026 (Abrainc/Fipe) para a defasagem de obra.
- [ ] Relatórios do sell-side (XP, Ágora, BBI, JPM) para o street case.
- [ ] Focus de 2027–2029 (o câmbio de 2029 varia de 5,36 a 5,57 entre edições) e meta de inflação de longo prazo.
- [ ] Status da renovação do acordo Intelbras–Dahua (vence em dez/2028).
- [ ] g da perpetuidade que você vai usar no DCF (amarra a fase 3).

---

## Fontes

- Wall Street Prep / BIWS, *Projecting the 3 Statements*, p.4–7 (exemplo da Dell).
- Intelbras: FRE 2026, item 1.4 (MIDI; shares de 44/43%, 9%, 19%, 1,9%); planilha de RI 2T26 (receita por BU); Release 2T26, p.7–8; BTG CEO Conference 2021, s.11.
- MarketsandMarkets — [Brazil Video Surveillance](https://www.marketsandmarkets.com/Market-Reports/geography/video-surveillance-market/Brazil); [Brazil Smart Cities](https://www.marketsandmarkets.com/Market-Reports/geography/smart-cities-market/brazil); [Brazil Wi-Fi](https://www.marketsandmarkets.com/Market-Reports/geography/global-wi-fi-market/Brazil); [Brazil Data Center UPS](https://www.marketsandmarkets.com/Market-Reports/geography/data-center-ups-market/brazil)
- IMARC — [Brazil Access Control](https://www.imarcgroup.com/brazil-access-control-market)
- Ken Research — [Brazil Electronic Security and Smart Surveillance](https://www.kenresearch.com/industry-reports/brazil-electronic-security-and-smart-surveillance-market)
- Abese via Monitor Mercantil — [R$14 bi em 2024](https://monitormercantil.com.br/seguranca-eletronica-faturou-r-14-bilhoes-em-2024-no-brasil/)
- CBIC — [Construção projeta 2026 mais positivo](https://cbic.org.br/construcao-civil-projeta-2026-mais-positivo-que-2025-impulsionado-por-credito-e-investimentos/); [PIB da construção 1T26](https://cbic.org.br/construcao-cresce-29-no-primeiro-trimestre-de-2026/)
- Canal Solar — [Previsão da energia solar em 2026](https://canalsolar.com.br/previsao-da-energia-solar-em-2026/); eixos (Absolar) — [Solar retraiu 29% em 2025](https://eixos.com.br/solar/expansao-da-energia-solar-retraiu-29-em-2025-indica-absolar/)
- Sell-side — [Money Times (JP Morgan)](https://www.moneytimes.com.br/apos-salto-nas-acoes-jp-morgan-rebaixa-recomendacao-de-intelbras-intb3-de-olho-no-segundo-semestre-lils/); [XP](https://conteudos.xpi.com.br/acoes/relatorios/intelbras-intb3-melhora-de-margens-com-crescimento-seletivo/); [EQI (Ágora)](https://euqueroinvestir.com/acoes/intelbras-tera-2026-de-menor-receita-mas-maior-rentabilidade); [EQI (BBI)](https://euqueroinvestir.com/acoes/intelbras-vai-reinvestir-ganhos-de-margem-diz-bradesco-bbi)
- Focus — [InfoMoney, abr/26 (2028–29)](https://www.infomoney.com.br/economia/boletim-focus-projecoes-macroeconomicas-06042026/); [EQI](https://euqueroinvestir.com/economia/boletim-focus-reduz-projecao-para-selic-no-fim-do-ano); [Suno](https://www.suno.com.br/noticias/boletim-focus-29062026-go/); [SBT News](https://sbtnews.sbt.com.br/noticia/economia/boletim-focus-reduz-projecoes-de-selic-e-pib-para-2026)
