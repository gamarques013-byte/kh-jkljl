# Intelbras (INTB3) — Modelo de Negócios: a lógica econômica

*Data-base: 2T26 (release de 29/07/2026). Estrutura: seção 1 do roteiro "Como Analisar Empresas" (o que faz → clientes e fornecedores → produção e distribuição → escala), aprofundada nos 10 pontos pedidos.*

> **Sobre as fontes.** O **Formulário de Referência 2026 não estava entre os anexos** (vieram: Release 2T26, planilha interativa 2T26 e o comunicado + apresentação do BTG CEO Conference 2021). Tentei baixá-lo do RI e da CVM, mas a política de rede deste ambiente bloqueia esses domínios. Por isso uso as marcações abaixo e indico o que precisa ser confirmado no FRE.
>
> | Tag | Fonte |
> |---|---|
> | **[R p.X]** | Release de Resultados 2T26, página X |
> | **[P]** | Planilha interativa 2T26 (abas DRE-R, BP-R, FC, Indicadores, Informações por Segmento) |
> | **[BTG21 s.X]** | Apresentação CEO Conference, mai/2021, slide X. É dado da companhia e está defasado |
> | **[FRE\*]** | Dado do FRE citado no seu brief ou reproduzido por research/imprensa. **Não verifiquei no documento original** |
> | **[Imprensa]** | Notícias/research, com link no final |
> | **Inferência:** | Conclusão minha, com a cadeia lógica explicada |
> | **Estimativa:** | Cálculo meu, com a fórmula |

---

## Tese em uma linha

**O modelo de negócios da Intelbras funciona porque ela converte hardware de plataformas tecnológicas globais (em boa parte chinesas) em *disponibilidade local + suporte + marca + regime fiscal de produção nacional* para ~80–90 mil instaladores pulverizados. Ela só captura margem onde o comprador é esse instalador. Onde o comprador é concentrado ou o produto tem preço global (GPON, solar), o modelo perde rentabilidade.**

### Os números que explicam o modelo

| Métrica | Valor | Fonte | Leitura |
|---|---|---|---|
| Receita líquida 2025 | R$4,46 bi: Segurança 61% / TIC 22% / Energia 17% | [P] | Confirma o FRE (R$2,73 bi / R$977 mi / R$753 mi) |
| CAGR da receita 2019–25 | 17,5% a.a. (Segurança 18,1%; TIC 9,2%; Energia 36,7%, com pico em 2022) | [P], cálculo | Segurança cresceu **todos os anos**; Energia teve boom e queda |
| Margem bruta | 34,9% (2019) → 28,4% (2022) → 30,1% (2025) → 33,1% (2T26) | [P], [R p.3] | Caiu quando Energia/solar ganhou peso |
| SG&A / receita | 20,3% (2019) → 17,4% (2022) → 19,3% (2025) | [P], cálculo | A receita cresceu 2,6x sem diluir despesa de forma duradoura |
| Capital de giro operacional × ativo fixo (2025) | R$1,60 bi × R$1,25 bi | [P], cálculo | **O capital da Intelbras é sobretudo estoque e crédito ao canal** |
| Ciclo de caixa (CCC) | 68 dias (2019) → 145 (2025) → 132 (LTM 2T26) | [P], cálculo | Dobrou em 6 anos |
| ROIC pré-IR | 31% (2019) → 15% (2025) → 18,8% (LTM 2T26) | [P], [R p.6] | A queda veio do giro do capital, não da margem (ver A4) |
| Alíquota efetiva de IR/CS | entre −5,6% e +1,9% (2019–25) | [P], cálculo | Parte relevante do retorno é fiscal/regulatória |

*Definições: CCC = DSO + DIO − DPO. DSO = contas a receber/receita × 365; DIO = estoques/CPV × 365; DPO = (fornecedores + risco sacado)/CPV × 365. Capital de giro operacional = contas a receber + estoques − fornecedores − risco sacado. ROIC pré-IR (definição da companhia) = EBIT LTM / (dívida líquida + PL) [R p.6].*

---

## A. Como gera valor e receita

### A1. O que vende e como cada receita se comporta

| Segmento (2025) | Receita / % | Categorias (exemplos) | Natureza da receita | Quem decide a compra |
|---|---|---|---|---|
| **Segurança** | R$2.730 mi / 61% | Videomonitoramento (câmeras, DVR/NVR), controle de acesso, alarmes, interfonia/comunicação condominial, incêndio; software de gestão e apps (portaria remota, "Condomínio Autônomo", VMS da Seventh) [BTG21 s.10, s.15] | Hardware transacional. O software vem embarcado ou acompanha o hardware | Instalador/revendedor; integrador em projetos maiores |
| **TIC** | R$977 mi / 22% | Redes empresariais (switches, Wi-Fi), cabeamento estruturado, cabos ópticos, GPON (OLT/ONT para provedores), comunicação corporativa (PABX/telefonia, Khomp) [R p.7–8; BTG21 s.15] | Hardware transacional. GPON e cabos são "bens de capital" de provedores | Revenda/integrador de TI; provedores regionais (ISPs) |
| **Energia** | R$753 mi / 17% | Nobreaks, fontes, proteção elétrica, baterias, carregadores veiculares, energia solar (kits; Renovigi) [R p.8] | Hardware transacional. Solar funciona como projeto/kit | Instalador elétrico/TI; integrador solar |

**Categorias mais relevantes em cada BU.** A abertura por categoria não está nas fontes fornecidas.
- **Segurança.** Inferência: videomonitoramento é provavelmente a maior categoria, por três sinais: (i) a Dahua, fornecedora exclusiva de CFTV, respondeu por 28,6% dos pagamentos a fornecedores em 2021 [FRE\*/Imprensa]; (ii) a fábrica de Manaus produz CFTV [Imprensa]; (iii) a expansão de R$200 mi em Manaus tem foco em segurança [Imprensa; R p.3].
  - Estimativa para controle de acesso: 27% × R$1,2 bi (participação e mercado de 2020 [BTG21 s.11]) ≈ R$0,32 bi, ou ~28% da receita de Segurança de 2020 (R$1,15 bi [P]). O cálculo supõe que a definição e a base de preço do mercado são iguais às da receita, o que não está garantido.
- **TIC.** Cabeamento estruturado e redes empresariais ganham peso à medida que a Intelbras reduz GPON. A linha de cabos ópticos opera perto da capacidade máxima [R p.7–8].
- **Energia.** Depois da redução em solar, nobreaks e carregadores veiculares são as linhas em crescimento [R p.8].

### A2. Mix, crescimento e margem (R$ mi)

| | 2019 | 2020 | 2021 | 2022 | 2023 | 2024 | 2025 | 1S26 (a/a) |
|---|---|---|---|---|---|---|---|---|
| Segurança | 1.007 | 1.148 | 1.620 | 1.982 | 2.225 | 2.603 | 2.730 | 1.381 (+5,8%) |
| TIC | 576 | 771 | 918 | 843 | 908 | 1.062 | 977 | 535 (+13,7%) |
| Energia | 115 | 215 | 549 | 1.408 | 971 | 1.091 | 753 | 343 (−12,4%) |
| **Total** | 1.698 | 2.134 | 3.087 | 4.233 | 4.104 | 4.756 | 4.460 | 2.260 (+4,2%) |
| Peso de Energia | 6,8% | 10,1% | 17,8% | **33,3%** | 23,7% | 22,9% | 16,9% | 15,2% |
| Margem bruta consolidada | 34,9% | 32,8% | 29,5% | **28,4%** | 31,1% | 30,8% | 30,1% | 31,9% |

Fonte: [P], aba Informações por Segmento (soma dos trimestres) e Indicadores Anuais.

**Leitura econômica**
- **Segurança é o núcleo que se compõe.** É a única linha que cresceu em todos os anos (+4,9% a +41% a/a). Inferência: a demanda é pulverizada e recorrente (obras, condomínios, PMEs, retrofit) e a Intelbras tem posição dominante declarada (44% [FRE\*]; 43% em 2020 [BTG21 s.11]).
- **TIC está estagnada desde 2021** (CAGR 2021–25 de +1,6%). Ela mistura linhas maduras (telefonia/PABX) com linhas commoditizadas que a própria companhia está podando (GPON) [R p.7].
- **Energia foi um ciclo.** A receita foi de R$115 mi para R$1,4 bi (2022), com a aquisição da Renovigi por R$334 mi [Imprensa], e voltou a R$753 mi. A queda reflete a "priorização da rentabilidade" em solar desde o 3T25 [R p.8].

**Margem bruta por segmento: o que se sabe**
- **2017–2020** [BTG21 s.13]:
  - Segurança: 41% / 40% / 38% / 39%;
  - TIC (Redes + Comunicação): 29% / 32% / 32% / 32%;
  - Energia: 31% / 30% / 28% / 26%. A margem de Energia caiu justamente quando solar cresceu.
- **3T25:** TIC com 26,8% [Imprensa, sobre o release 3T25].
- **2T26:** a margem de Energia é "a segunda maior entre os três segmentos" [R p.8]. Inferência: a ordem é Segurança > Energia > TIC.
- **2025:** os valores por segmento estão no FRE 2026, mas não nas fontes fornecidas. **Não há evidência suficiente nas fontes fornecidas para concluir** qual é a participação de cada segmento no lucro bruto de 2025.
  - Estimativa grosseira para 2020 (margens do BTG21 × receita [P]): Segurança ≈ 60% do lucro bruto com 54% da receita. A soma estimada fica ~7% acima do lucro bruto reportado, então use apenas como ordem de grandeza.

**O teste do mix.**
- Entre 2019 e 2022, o peso de Energia subiu de 6,8% para 33,3%, e a margem bruta consolidada caiu de 34,9% para 28,4%.
- Quando Energia recuou para 23,7% (2023), a margem voltou a 31,1%.
- Inferência: a maior parte da compressão de 2019–22 foi **mix** (solar), não erosão de preço em Segurança.
- Em 2025, porém, Energia caiu a 16,9% e a margem não voltou aos 35% de 2019. Há outros fatores, como AVP (ajuste a valor presente: o componente financeiro embutido nas vendas a prazo, deduzido da receita), câmbio e competição. As fontes não permitem separar esses efeitos.

**A margem do 2T26 tem uma parte cíclica.**
- A companhia reajustou preços pelo **custo de reposição** (o custo de recomprar o item hoje), enquanto o estoque ainda carrega custo médio mais baixo. Ela mesma diz que essa parte "tende a se normalizar" [R p.2–4, p.10].
- A margem bruta ex-AVP passou de 30,2% para 33,7% [Imprensa].
- Mecanismo: com DIO de ~144 dias (≈ 5 meses), a margem bruta reage com defasagem ao câmbio e ao custo na origem. Ela **sobe** quando os custos sobem (repasse antes do custo chegar ao CPV) e **cai** quando os custos caem. Isso mostra que, em Segurança, a Intelbras consegue repassar preço dentro de uma faixa. É poder de preço relativo, não absoluto.

### A3. Hardware, software e recorrência

- **Fato:** os três segmentos reportados são categorias de hardware. Releases e planilha não divulgam receita recorrente [R; P]. Em 2021 a companhia citava 28 apps, mais de 7 milhões de downloads e modelos "SaaS/HaaS" com "equipamento sem custo" como avenida futura [BTG21 s.10, s.16].
- **Inferência:** software (apps, VMS, nuvem, portaria remota) funciona hoje como **complemento que aumenta o custo de troca do hardware**, não como linha de receita. O cliente que já opera o app Intelbras tende a expandir o sistema com a mesma marca.
- **Não há evidência suficiente nas fontes fornecidas para concluir** que exista receita recorrente material.

### A4. Quando o portfólio amplo cria valor, e quando não cria

| Mecanismo | Faz sentido quando… | Evidência disponível | Veredito |
|---|---|---|---|
| Ticket por revendedor ↑ | O mesmo instalador compra várias categorias na mesma obra (condomínio: CFTV + interfonia + acesso + rede + nobreak) | Ticket por revendedor não é divulgado | Não comprovado |
| CAC ↓ (CAC = custo de aquisição de cliente) | O custo de "conquistar" o instalador já foi pago por Segurança | SG&A/receita ficou entre 17% e 20% de 2019 a 2025 | Não aparece nos números agregados |
| Share of wallet ↑ | O portfólio cobre a lista de materiais do projeto típico | Não divulgado | Não comprovado |
| Frequência de compra ↑ | Itens de reposição (cabos, fontes, baterias) | Não divulgado | Plausível |
| Utilização da rede ↑ | Os mesmos distribuidores carregam as novas linhas | Distribuidores: 370+ (2020) → ~500 (2024) [BTG21 s.4; FRE\*] | Parcial: a rede cresceu junto com o portfólio |
| Poder de barganha ↑ | A Intelbras vira fornecedor "obrigatório" do distribuidor | Nenhum cliente >10% da receita [FRE\*]. DSO subiu de 79 para 96–103 dias | Ambíguo: prazo maior ao canal sugere que a Intelbras **financia** o canal |
| Diluição de custo fixo | P&D, marca, TI e CD compartilhados | G&A/receita: 6,3% (2019) → 5,8% (2025). Vendas/receita: 13,9% → 13,5% | Diluição pequena |
| Menor dependência de uma categoria | Categorias não correlacionadas | Segurança segurou a receita quando Energia caiu (2023, 2025) | Sim, mas Energia trouxe volatilidade, estoque e goodwill |

**Conclusão.** Portfólio amplo cria valor quando a nova categoria cumpre três condições:
1. tem o **mesmo comprador** (o instalador);
2. é vendida na **mesma ocasião de compra** (a obra ou o projeto);
3. **precisa de suporte local** (configuração, garantia).

Quando essas condições falham, o portfólio acrescenta receita mas dilui margem e ROIC. Exemplos: solar, com rede própria da Renovigi de 9 mil revendedores [Imprensa], e GPON vendido a ISPs. A própria administração está podando essas linhas [R p.7–8].

### A5. Unit economics conceituais por segmento

*Volume × preço × mix → receita → margem bruta → despesas → capital de giro → ROIC*

| | **Segurança** | **TIC** | **Energia** |
|---|---|---|---|
| Volume | Obras, condomínios, PMEs, retrofit analógico→IP, percepção de insegurança *(hipótese)* | Capex de ISPs (fibra/GPON), PMEs (redes), construção (cabeamento) *(hipótese)* | Geração distribuída (juros, tarifa, regulação), PMEs/TI (nobreaks), veículos elétricos (carregadores) *(hipótese)* |
| Preço | Repasse a custo de reposição observado [R p.7]. Faixa limitada por marcas globais | GPON e cabos com referência de preço global. Cabos ópticos protegidos por antidumping desde dez/2025 (US$2,42/kg cabos; US$47,46/kg fibras — Gecex 837 e 829) [Imprensa] | Módulos solares: commodity global com deflação *(inferência)* |
| Mix | IP/IA/acesso facial elevam o ticket *(hipótese)* | Saída de GPON, entrada de cabeamento/redes [R p.7] | Menos solar → lucro bruto +12% a/a com receita −13,5% no 2T26 [R p.8] |
| Margem bruta (histórico) | 38–41% (2017–20) [BTG21] | 29–32% (2017–20); 26,8% (3T25) | 26–31% (2017–20). A Renovigi tinha margem EBITDA de 6,2% em 2021 [Imprensa] |
| Despesa necessária | Treinamento, suporte, marca (custo de plataforma já amortizado) | Pré-venda técnica para projetos | Rede própria (Renovigi), projetos |
| Capital de giro | Muitos SKUs em estoque + prazo ao distribuidor | Prazo a ISPs (risco de crédito) + fábrica de Tubarão | Estoque de kits sujeito a deflação + goodwill (R$334 mi em 2022) |
| ROIC *(inferência)* | Provavelmente o maior do grupo: maior margem sobre a mesma estrutura de canal | Menor e mais volátil | Diluiu o retorno no ciclo 2022–24 |

**ROIC: a decomposição que mais importa** (margem × giro)

*Fórmula: ROIC pré-IR = EBIT / CE = (EBIT / Receita) × (Receita / CE), onde CE = capital empregado.*

| | 2019 | 2021 | 2022 | 2023 | 2024 | 2025 | LTM 2T26 |
|---|---|---|---|---|---|---|---|
| Margem EBIT | 10,8% | 11,7% | 10,9% | 12,7% | 11,4% | 9,5% | 11,3% |
| Giro (Receita/CE) | 2,88x | 2,17x | 2,41x | 1,84x | 1,58x | 1,58x | 1,66x |
| **ROIC pré-IR** | **31,2%** | 25,5% | 26,4% | 23,3% | 18,1% | **15,1%** | **18,8%** |

*Exemplo 2025: 9,5% × 1,58 = 15,1%. LTM 2T26: R$514 mi / R$2.740 mi = 18,8%, que bate com [R p.6]. 2020 foi excluído: ROIC de 53% inflado por não recorrentes.*

**Leitura.** A margem EBIT ficou praticamente na mesma faixa (10–13%). O ROIC caiu à metade porque o capital empregado multiplicou-se 4,8x (R$590 mi → R$2.815 mi), enquanto a receita cresceu 2,6x. De onde veio o capital:
- capital de giro operacional: 4,8x (R$334 mi → R$1.595 mi);
- intangível: R$88 mi → R$572 mi (aquisições: Khomp, Renovigi);
- imobilizado: R$230 mi → R$682 mi. [P]

**Variáveis de maior impacto** *(hipóteses de modelagem)*

| Linha | Variáveis que mais pesam |
|---|---|
| **Crescimento** | Nº de obras/condomínios/PMEs (Segurança); capex de ISPs e proteção comercial (TIC); juros e regras de geração distribuída (Energia) |
| **Margem bruta** | Câmbio (BRL/USD, BRL/CNY) × DIO (defasagem de repasse); peso de Energia e GPON; AVP (juros × prazo concedido); créditos da Lei de TICs (ver C5) |
| **EBITDA** | Margem bruta menos despesas com vendas, que ficaram em ~13,5% da receita e se mostraram rígidas |
| **Estoque** | Lead time da Ásia, nº de SKUs, choques de componentes (2021: DIO 217 dias), apostas de categoria (2024: estoque de R$1,77 bi) |
| **Contas a receber** | Prazo ao distribuidor (DSO de 72 a 103 dias) e perdas de crédito (PCLD de R$28,8 mi em 2025 vs R$7,1 mi em 2024) [P, FC] |
| **ROIC** | **Giro do capital (CCC) mais do que margem** |

---

## B. Clientes, canais e distribuição

### B1. Quem é quem na cadeia

| Rota | Cliente direto (quem paga a Intelbras) | Quem especifica | Quem instala | Usuário final | % das vendas 2024 [FRE\*] | % 2020 [BTG21 s.9] |
|---|---|---|---|---|---|---|
| **Intelbras → distribuidor → revendedor/instalador → cliente** | ~500 pontos de distribuição | Em residências e PMEs, o instalador frequentemente escolhe a marca | Instalador | Residências, condomínios, PMEs | **71%** | 77% |
| **Intelbras → varejista → consumidor** | Varejistas físicos e online | Consumidor (faça-você-mesmo) | Consumidor ou instalador | Residências | **13%** | 13% |
| **Intelbras → integrador / conta nomeada** | Integradores, grandes empresas, governo; ISPs *(inferência para GPON)* | Projetista, integrador ou área técnica do cliente; licitação | Integrador | Médias e grandes empresas, governo, ISPs | **16%** | 10% |

- O distribuidor é o **cliente direto**.
- O instalador é o **especificador**: no varejo técnico, é ele quem decide a marca.
- O usuário final é o **pagador econômico**, mas raramente escolhe a marca.
- Entre 2020 e 2024, a rota de **projetos** (integradores/contas nomeadas) foi de 10% para 16%. É a rota com comprador mais técnico e sensível a preço.

### B2. Quantificação

| Indicador | Valor | Fonte |
|---|---|---|
| Pontos de distribuição | 370+ (2020) → ~500 (2024/2025) | [BTG21 s.4, s.8]; [FRE\*] |
| Revendedores/instaladores | ~80 mil (2020) → 80 mil+ (2024) → 90 mil+ (FRE 2026) | [BTG21]; [FRE\*] |
| Cobertura | 98% dos municípios "com potencial de consumo de eletrônicos" | [BTG21 s.4, nota 1] |
| Relacionamento médio com distribuidores | 20+ anos | [BTG21 s.8] |
| Concentração | Nenhum cliente acima de 10% da receita | [FRE\*/Imprensa] |
| **Estimativa:** receita por ponto de distribuição | R$4,46 bi × 71% / 500 ≈ **R$6,3 mi/ano** (~R$530 mil/mês) | cálculo |
| **Estimativa:** receita (a preço Intelbras) por revendedor | R$4,46 bi × 71% / 80–90 mil ≈ **R$35–40 mil/ano** (~R$3 mil/mês) | cálculo |

*Premissas das estimativas: o mix de canal de 2024 vale para 2025, e todo revendedor compra via distribuição. Atenção: os "pontos de distribuição" contam **todas as unidades** de cada parceiro [BTG21 s.4, nota 2]. O número de grupos econômicos é menor, então a concentração real é maior do que "500" sugere.*

### B3. Por que essa arquitetura existe

**O problema econômico.** O especificador (instalador) compra cerca de R$3 mil/mês da Intelbras.
- Atender 80–90 mil contas desse porte diretamente exigiria análise de crédito, cobrança e logística fracionada para tíquetes pequenos. Para um fabricante, isso é inviável.
- **O distribuidor existe para agregar demanda, manter estoque local e assumir o risco de crédito do micro-instalador.**

| Dimensão | Efeito da venda via distribuidor + instalador | Evidência e contra-evidência |
|---|---|---|
| Capilaridade | O distribuidor local leva o produto a 98% dos municípios sem filiais próprias | [BTG21] |
| Custo comercial | A Intelbras "paga" a margem do distribuidor (embutida no preço) em vez de manter força de vendas para 90 mil contas | As despesas com vendas ainda são **13,5% da receita** (2025). A Intelbras mantém promotores (90+ em 2021 [BTG21 s.12]), treinamento e marketing. O modelo é de dupla tração: puxado pelo instalador e empurrado pelo distribuidor |
| Estoque | O estoque fica em dois níveis (Intelbras + distribuidor) | A Intelbras ainda carrega DIO de 144–217 dias. **Ela é o "estoque regulador" do sistema**; o distribuidor não absorve o grosso |
| Logística | A Intelbras entrega lotes grandes a ~500 pontos; a última milha é do distribuidor | — |
| Capital de giro | O crédito ao micro-instalador fica com o distribuidor | Mas a **Intelbras financia o distribuidor**: DSO de 79 dias (2019) → 96 (2025) → 103 (LTM 2T26). PCLD quadruplicou em 2025 [P] |
| Suporte técnico | Treinamento centralizado (Intelbras Itec, Universidade Intelbras) + suporte do distribuidor | [Imprensa] |
| Velocidade de lançamento | Um SKU novo chega a ~500 pontos e é apresentado a 90 mil instaladores pelo mesmo canal | "Innovation targets are the resellers, integrators" [BTG21 s.10] |
| Barreira à entrada | O entrante precisa convencer o distribuidor a estocar (risco de giro) e o instalador a aprender | A barreira é transponível: a Dahua opera **marca própria no Brasil desde 2016** e fechou com a distribuidora Dimensional (grupo Sonepar) [Imprensa] |

**Sell-in × sell-out.**
- Sell-in é a venda da Intelbras ao canal; sell-out é a venda do canal ao cliente final.
- A companhia monitora a relação entre os dois e diz que ela "se manteve estável" [R p.6]. Isso é positivo para a qualidade da receita: reduz o risco de empurrar estoque para o canal.
- Mas a receita reportada é **sell-in**. Quando o distribuidor reduz estoque, a receita da Intelbras cai mais do que a demanda final (efeito chicote). O 1T25 (falha na migração do ERP) mostrou essa sensibilidade ao fluxo de pedidos [R p.2–3].

### B4. O papel do instalador: há custo de troca e fidelidade?

| Mecanismo | Existe? | Por quê, e qual o limite |
|---|---|---|
| **Custo de troca** | Moderado em ecossistemas, baixo em itens isolados | Configurar DVR/NVR, VMS, apps de portaria e controle de acesso exige aprendizado específico, e a base instalada induz expansões com a mesma marca *(inferência)*. Uma câmera isolada é intercambiável, e padrões abertos de câmeras IP reduzem esse custo |
| **Fidelidade** | Sim, parcialmente "comprada" | Programa de Canais com níveis Golden/Silver/Bronze/Registered [BTG21 s.9; Imprensa]. Fidelidade sustentada por benefício e rebate é replicável por quem tem caixa |
| **Preferência de especificação** | Sim no residencial/PME | A marca conhecida pelo usuário final reduz o esforço de venda do instalador. Pesquisa da própria empresa (2019): 97% conhecem, 84% escolheriam Intelbras [BTG21 s.12]. Dado da companhia, com viés |
| **Distribuição cativa** | **Não** | Distribuidores são multimarca e a Dahua usa distribuidores próprios. *Inferência:* a Intelbras não tem exclusividade de canal |
| **Network effect indireto** | **Fraco** | Não há interação entre usuários. O que existe é efeito de **base instalada e aprendizado**: mais instaladores treinados → mais mão de obra disponível → o usuário prefere a marca que "todo técnico conhece". É uma vantagem de escala no canal, não um efeito de rede clássico |
| **Barreira à entrada** | Sim, **de tempo** | A combinação estoque local + instalador treinado + marca leva anos para replicar, mas não é impossível para um player global com produto mais barato |

**Limites da vantagem.**
1. Em **projetos** (16% das vendas), o integrador decide por especificação técnica e preço e tem acesso direto a fabricantes globais.
2. No **varejo e em marketplaces** (13%), o preço é comparado lado a lado com marcas importadas.
3. No **residencial de baixa renda**, até o instalador cede a preço.

### B5. Distribuição como parte do produto

**Por que um concorrente com tecnologia comparável não replica rapidamente a posição da Intelbras?**

O que o instalador compra não é só o equipamento. É o pacote: *equipamento + disponibilidade hoje na sua cidade + crédito via distribuidor + treinamento + garantia/assistência local + aceitação da marca pelo cliente + ecossistema compatível*.
- Um concorrente iguala o **equipamento** rápido.
- Os outros componentes dependem de um **problema de ovo e galinha**: o distribuidor só estoca o que gira, e só gira o que o instalador já sabe instalar e o cliente reconhece.

| Elemento | Classificação | Justificativa |
|---|---|---|
| Base de 80–90 mil instaladores treinados e familiarizados | **Estrutural** (lenta de replicar) | Conhecimento tácito acumulado. Cada instalador tem custo de reaprender |
| Marca junto ao usuário final | **Estrutural parcial** | Décadas de marketing e varejo (mídia nacional, Copa do Brasil 2019–22 [BTG21 s.12]). Pesa menos em projetos |
| Relações de 20+ anos com distribuidores | **Estrutural parcial** | Confiança e histórico de proteção da rentabilidade do distribuidor [Imprensa]. Mas os distribuidores são multimarca |
| Produção local / PPB / incentivos | **Regulatória**, não competitiva "natural" | Depende de política pública (Lei de TICs, ZFM). Um concorrente pode instalar-se em Manaus. Muda com a reforma tributária |
| Cobertura de ~500 pontos / 98% dos municípios | Replicável com tempo e capital | Os mesmos distribuidores podem carregar outra marca, se ela girar |
| Crédito ao canal | Replicável | Players globais têm balanço maior |
| Ecossistema (apps/VMS) | Replicável | Fabricantes globais têm apps e plataformas próprias *(inferência)* |
| Suporte pré e pós-venda, assistência | Replicável com investimento | — |

---

## C. Produção, sourcing e fornecedores

### C1. Unidades produtivas

| Unidade | O que produz | Função econômica *(inferência)* |
|---|---|---|
| **São José (SC)**, sede | Matriz, P&D, centro de distribuição. Produção da linha GPON [Imprensa: Teletime, jan/26] | Centro de engenharia, logística e montagem |
| **Manaus (AM)**, desde 2009, ~1.200 colaboradores | CFTV [Imprensa]. Terreno de 670 mil m² comprado por R$19,4 mi; investimento total de ~R$200 mi em 18 meses, com foco em segurança [Imprensa; R p.3, p.9] | Captura incentivos da ZFM e da Lei de TICs + capacidade para o core |
| **Tubarão (SC)** | Cabos de rede e cabos ópticos (investimento inicial de R$60 mi), em cooperação com a FiberHome. Perto da capacidade máxima após o antidumping [R p.8; Imprensa] | Manufatura protegida por defesa comercial |
| **Santa Rita do Sapucaí (MG)** | Não detalhado nas fontes | — |
| Total | 5 unidades fabris em 2021 [BTG21 s.4] | — |

### C2. Cadeia de suprimentos

- **Plataforma/produto de vídeo — Dahua.**
  - Acordo de Cooperação (2018) com **compromisso de compra exclusiva de CFTV** da Dahua, condicionado a condições comerciais favoráveis [FRE\*/Imprensa].
  - Pagamentos à Dahua = **28,6% dos gastos com fornecedores em 2021** [FRE\*/Imprensa].
  - **Concentração alta em um único parceiro, na maior categoria do maior segmento.**
- **GPON — FiberHome.**
  - Exclusividade de produção e comercialização de 01/01/2024 a **12/01/2026**. Agora as duas empresas podem trabalhar com outros parceiros.
  - A cooperação em cabos ópticos (Tubarão) continua [Imprensa].
- **Componentes eletrônicos** (semicondutores, placas, sensores).
  - Inferência: são majoritariamente importados. Sinais: DIO alto, "política de proteção cambial" com derivativos [R p.5], variação cambial líquida de −R$65 mi (2024) e −R$31 mi (2025) [P], e estoque disparando na crise de chips de 2021 (DIO de 217 dias).
- **Solar** — módulos e inversores. Inferência: majoritariamente importados.
- **Matérias-primas** (cobre, plásticos, metais). Elevação recente de custos "em função da alta dos preços das commodities" [R p.7].
- **Financiamento de fornecedores.**
  - Risco sacado de **R$369 mi** no 2T26, ≈ **30% do estoque** [R p.14]. (Risco sacado: o banco antecipa o pagamento ao fornecedor e a Intelbras paga o banco num prazo mais longo. Economicamente, é próximo de dívida.)
  - Tratado como dívida, o caixa líquido de R$585 mi cairia para ~R$216 mi.

### C3. A relação com a Dahua: benefícios × riscos

| Benefícios | Riscos |
|---|---|
| **Tecnologia e P&D:** vídeo, óptica e IA de um player global, numa escala de P&D que a Intelbras (≈4% da receita, ~400 profissionais em 2021 [BTG21 s.10]) não teria sozinha | **Concentração:** 28,6% dos pagamentos a fornecedores (2021), na maior categoria do maior segmento |
| **Velocidade de lançamento:** portfólio atualizado no ritmo global | **Dependência tecnológica:** a exclusividade de CFTV amarra a Intelbras à plataforma do parceiro |
| **Custo:** escala de compra e fabricação do parceiro | **Poder de barganha:** o dono da tecnologia influencia o preço de transferência e a prioridade de lançamentos |
| **Qualidade:** inspeção pré-embarque e auditoria de fornecedores [BTG21 s.10] | **Conflito de interesse:** a Dahua tem **marca própria no Brasil desde 2016**, virou região independente da América Latina e fechou com a Dimensional (Sonepar) [Imprensa]. **Disputa o mesmo instalador** |
| **Alinhamento societário (2019):** comprou 10% da Intelbras para "consolidar relação de 12 anos" [Imprensa] | **Desalinhamento crescente:** a participação caiu de 10% para 7,56% (venda em bloco de ~2,5%) e, em **ago/2025**, o conselho da Dahua autorizou vender os 7,56% restantes em até 36 meses [Imprensa] |
| | **Geopolítica:** os EUA restringem equipamentos Dahua/Hikvision (NDAA 2019, seção 889; FCC 2022). Hoje não há restrição no Brasil, mas há risco de contágio em compras públicas e corporativas |
| | **Câmbio e tarifas:** custo atrelado a USD/CNY; exposição a eventual defesa comercial brasileira |
| | **Integração vertical:** a Dahua já vende direto no Brasil por canal próprio |

**Quem tem o poder?** Há dependência mútua.
- A Dahua credita parte do seu crescimento no Brasil ao "grande sucesso da parceria com a Intelbras" [Imprensa].
- A Intelbras depende da tecnologia da Dahua no CFTV.
- Inferência: o equilíbrio **está migrando para a Dahua**, porque ela constrói canal próprio e se desfaz da participação acionária.

### C4. Que tipo de empresa é a Intelbras? Depende da categoria

| Categoria | Papel predominante *(inferência)* | Evidência |
|---|---|---|
| CFTV / videomonitoramento | **Dona da marca + montadora local** da plataforma Dahua + camada de firmware, apps e suporte | Exclusividade Dahua; fábrica de CFTV em Manaus |
| Controle de acesso, alarmes, interfonia, incêndio | **Desenvolvedora + fabricante** (herança de Automatiza/Engesul e P&D próprio) | Aquisição de Automatiza e Engesul em 2013 segundo o slide 15 (o slide 5 indica 2017) [BTG21]; Maxcom (2005/07) marcou a entrada em segurança e redes |
| Comunicação corporativa (PABX, Khomp) | **Desenvolvedora + fabricante**: o negócio de origem | Fundação em 1976 com centrais telefônicas [BTG21 s.5] |
| GPON | **Fabricante licenciada / distribuidora** de tecnologia FiberHome, em redução | [R p.7]; Teletime |
| Cabos ópticos e de rede | **Fabricante** com parceiro tecnológico | [R p.8] |
| Redes empresariais | Dona da marca / integradora | Origem da tecnologia não divulgada |
| Solar | **Distribuidora / integradora** de kits importados | Renovigi: receita de R$799 mi e EBITDA de R$49,8 mi (6,2%) em 2021 [Imprensa] |
| Nobreaks, fontes, carregadores | Dona da marca / fabricante | Não detalhado nas fontes |

*Atenção ao dado "75% da receita vem de produtos desenvolvidos internamente" [BTG21 s.10].* Com exclusividade de CFTV com a Dahua, "desenvolvido internamente" deve incluir adaptação e codesenvolvimento. **A definição não foi divulgada e o número não deve ser lido como tecnologia proprietária.**

### C5. Onde a Intelbras realmente captura valor

| Etapa | Quem faz | Captura de valor pela Intelbras | Por quê |
|---|---|---|---|
| P&D de núcleo (chips, óptica, algoritmos de vídeo) | Parceiros (Dahua, FiberHome) e fornecedores de semicondutores | **Baixa** | É paga no preço de transferência |
| Engenharia de adaptação: firmware, apps, certificação Anatel | Intelbras | **Média** | "Abrasileira" o produto (idioma, padrões, ecossistema) e é condição para o incentivo da Lei de TICs (P&D obrigatório) |
| Sourcing / compras | Intelbras | **Média** | Escala relevante no Brasil, pequena perto de Hikvision/Dahua, que são ao mesmo tempo fornecedor e concorrente |
| Fabricação / montagem (Manaus, SC) | Intelbras | **Média — via regime fiscal e prazo de entrega, não via custo industrial** | Ver o box abaixo |
| Marca | Intelbras | **Alta** no residencial/PME e com o instalador | Reduz o esforço de venda do canal |
| Estoque, distribuição e crédito | Intelbras + distribuidor | **Alta, mas cara em capital** | Capital de giro de R$1,6 bi |
| Treinamento e relacionamento com instaladores | Intelbras | **Alta** | É o que converte disponibilidade em especificação |
| Pós-venda / garantia | Intelbras | **Média** | Provisão para garantias de R$55 mi [R p.14]. O suporte local diferencia de importados sem representação |
| Integração de portfólio | Intelbras | **Potencial** | Só se materializa nas categorias do "trabalho do instalador" (A4) |

**Box — o valor econômico de fabricar no Brasil é principalmente fiscal.**
- **Fato:** a alíquota efetiva de IR/CS ficou entre −5,6% e +1,9% de 2019 a 2025 [P]. O NOPAT ficou próximo do EBIT ou até acima (2025: NOPAT de R$428,7 mi vs EBIT de R$425,2 mi).
- **Fato:** a DFC mostra "Créditos tributários e atualização monetária" (receita não-caixa) de **R$99–134 mi por ano entre 2021 e 2025** (R$129 mi em 2025, ≈30% do EBIT) [P, aba FC].
- **Inferência:** esses créditos são majoritariamente o **crédito financeiro da Lei de TICs**, que exige produção sob PPB e P&D obrigatório. A baixa alíquota reflete incentivos regionais (ZFM/Sudam), Lei do Bem e JCP. **A composição e a linha da DRE onde os créditos entram precisam ser confirmadas** na nota de subvenções/IR das DFs e no item de regulação do FRE (1.6).
- **Consequência:** a nova fábrica de Manaus (R$200 mi) é, em parte, uma decisão de **regime tributário**. Fabricar localmente cria vantagem enquanto a política existir. É uma vantagem regulatória, não de custo industrial.

**Síntese.** A Intelbras captura valor na **interface com o mercado brasileiro** (marca + canal + instalador + regime fiscal), não no núcleo tecnológico.

---

## D. Economias de escala, economias de escopo e poder de barganha

### D1. Economias de escala: o que os números mostram

| Fonte potencial | Mecanismo | Evidência | Conclusão |
|---|---|---|---|
| Compras | Volume → preço unitário | CPV de R$3,1 bi (2025): grande no Brasil, pequeno perto dos próprios fornecedores globais | Escala de compra é vantagem contra players **locais**, não contra os globais *(inferência)* |
| Produção | Custo fixo de linha diluído | Imobilizado ≈ 15% da receita. Tubarão no limite de capacidade [R p.8] | Intensidade fixa baixa: **escala de fábrica não é o motor** |
| Logística | Densidade de entregas | Não divulgado | Não há evidência suficiente |
| P&D | Custo fixo amortizado em mais unidades | ≈4% da receita (2021). Pela Lei de TICs, o P&D obrigatório é **proporcional ao faturamento incentivado** | Parte do P&D é **variável por lei**, então a alavancagem é menor do que parece *(inferência)* |
| Marketing / marca | Campanhas nacionais diluídas | Mídia Tier 1, patrocínio nacional [BTG21 s.12] | Ajuda contra entrantes regionais |
| **SG&A** | Diluição com volume | **SG&A/receita: 20,3% (2019) → 17,4% (2022, pico de receita) → 19,3% (2025)**. Vendas/receita: 13,9% → 11,8% (2021) → 13,5% (2025) [P] | O ganho de escala de 2021–22 **reverteu**. A despesa comercial é semivariável (fretes, comissões, rebates, promotores) e manter o canal exige gasto contínuo. **Não há evidência de economia de escala crescente em SG&A em 2019–25** |
| EBITDA | Alavancagem operacional | Receita 2,6x (2019–25); margem EBITDA de 11,9% → 12,1% | Escala **não** expandiu a margem operacional no período |

### D2. Economias de escopo: a mesma rede vende Segurança + TIC + Energia?

| Categoria adjacente | Mesmo comprador? | Mesma ocasião de compra? | Precisa de suporte local? | Resultado observado |
|---|---|---|---|---|
| Controle de acesso / interfonia / alarmes | Sim | Sim (condomínio, PME) | Sim | Segurança cresceu todo ano |
| Cabeamento estruturado / redes empresariais | Sim (instalador/integrador de TI) | Frequentemente | Médio | Puxam TIC: +7% a/a no 2T26 [R p.7–8] |
| Nobreaks / fontes / carregadores | Sim (instalador elétrico/TI) | Parcialmente | Baixo a médio | Crescendo no 2T26 [R p.8] |
| GPON para ISPs | **Não** (provedor concentrado) | Não | Não (o ISP tem engenharia própria) | Estratégia de redução; fim da exclusividade [R p.7; Imprensa] |
| Solar (kits e miniusinas) | **Não** (integrador solar; rede própria da Renovigi) | Não | Sim, mas de outro tipo | Receita de R$1,41 bi (2022) → R$0,75 bi (2025); "priorização da rentabilidade" [R p.8] |

**Conclusão.** O mecanismo *mais SKUs → mais share of wallet → mais uso do canal → mais relevância → mais capacidade de lançar* **é real, mas limitado ao "trabalho do instalador"**. Solar entrou por **aquisição de outra rede**, não por escopo do canal existente, e foi a linha que mais diluiu retorno. **Os dados para confirmar o escopo (compra cruzada por revendedor) não são divulgados.**

### D3. Matriz de poder de barganha

| Relação | Quem tende a ter mais poder | Fatos observáveis | Motivo |
|---|---|---|---|
| **Intelbras × fornecedores** (componentes, commodities) | **Fornecedores** | Crise de chips (2021): estoque foi a R$1,3 bi e DIO a 217 dias. "Elevação dos custos na origem" [R p.10] | A Intelbras é tomadora de preço em semicondutores e commodities; responde com estoque (custo de capital) e repasse |
| **Intelbras × Dahua** | **Dahua**, com dependência mútua | Exclusividade de CFTV; 28,6% dos pagamentos (2021); marca própria da Dahua no Brasil; saída do capital | A Dahua tem a tecnologia; a Intelbras tem o canal. O canal próprio da Dahua reduz o valor do canal da Intelbras para ela |
| **Intelbras × distribuidores** | **Intelbras** (moderado) | ~500 pontos, nenhum cliente acima de 10%. Mas DSO de 96–103 dias e PCLD em alta | A marca é "puxada" pelo instalador, o que torna o distribuidor dependente. O preço desse poder é **financiar o canal** |
| **Intelbras × revendedores** | **Intelbras** individualmente; o coletivo tem força | ~R$35–40 mil/ano por revendedor *(estimativa)* | Fragmentação total. Mas o conjunto de instaladores é o especificador e pode trocar de marca a cada obra em itens commoditizados |
| **Intelbras × varejistas** | **Equilibrado, pendendo ao varejo** | 13% das vendas | Grandes redes e marketplaces são concentrados e comparam preço com importados. A marca reconhecida limita o poder do varejo |
| **Intelbras × integradores / contas nomeadas** | **Contraparte** | 16% das vendas. GPON/ISPs com margem baixa (podado) | Especificação técnica, comparação multimarca, licitações e acesso direto a fabricantes globais |
| **Intelbras × consumidor final** | **Intelbras** (indiretamente) | Marca conhecida; compra pouco frequente | Consumidor fragmentado, que delega a escolha ao instalador. O limite é o preço: no residencial de baixa renda, o marketplace oferece alternativas mais baratas |

---

## E. Flywheel: testando a hipótese

**Hipótese:** portfólio maior → relevância para o canal → share of wallet e capilaridade → volume → escala (compras/P&D/distribuição) → oferta competitiva e lançamentos → marca e relacionamento → novas categorias → portfólio maior.

| Elo | Evidência | Status |
|---|---|---|
| 1. Portfólio ↑ → relevância para o canal ↑ | Distribuidores 370 → 500 e revendedores 80 mil → 90 mil, junto com a expansão de categorias. Não dá para separar causalidade | Parcial |
| 2. Relevância → share of wallet / capilaridade | Sem dados de share of wallet ou ticket por revendedor | Não evidenciado |
| 3. → Volume | **Sim em Segurança** (CAGR de 18%, crescimento todo ano). **Não** em TIC/Energia (voláteis) | Parcial |
| 4. Volume → escala (custo unitário ↓) | SG&A/receita estável; margem bruta menor; margem EBITDA estável | **Não evidenciado / contradito** |
| 5. Escala → produto competitivo e lançamentos | Os lançamentos são contínuos, mas o custo e a tecnologia vêm da **escala dos parceiros** (Dahua, FiberHome), não da Intelbras | Parcial |
| 6. → Marca e relacionamento | NPS de 68% (2S20), Reclame Aqui, pesquisas de marca [BTG21 s.9, s.12]. Dados da companhia | Evidenciado (com viés) |
| 7. → Novas categorias | Entrou em acesso, energia, solar, cabos. **Mas a entrada lucrativa não se confirmou:** solar e GPON diluíram retorno | Parcial / contradito |
| Resultado esperado: retorno crescente | **ROIC caiu de 31% (2019) para 15% (2025)** e voltou a 18,8% com a poda e a gestão de capital de giro | **Contradito no ciclo 2021–24** |

**Veredito**
- **Existe um "loop curto" que gira.** Instalador treinado → disponibilidade local → marca → preferência do instalador → volume em Segurança e nas adjacências do mesmo trabalho → mais distribuidores dispostos a estocar. É o que sustenta 18% a.a. em Segurança e o repasse de preço do 2T26.
- **O "loop longo" não aparece nos números.** Portfólio → escala → vantagem de custo → entrada lucrativa em novas categorias. A expansão para fora do trabalho do instalador **quebrou o ciclo** e consumiu capital.
- **O que confirmaria o flywheel:**
  - receita por revendedor ativo e nº de segmentos comprados por revendedor (compra cruzada);
  - sell-out por distribuidor;
  - margem bruta e ROIC por segmento por 5 anos (FRE);
  - churn de revendedores;
  - custo de atender por canal.

---

## F. Principais fragilidades do modelo

| Fragilidade | Mecanismo | Linha afetada | Sinal já observado |
|---|---|---|---|
| **Entrada chinesa agressiva, inclusive do próprio parceiro** | Mesma plataforma vendida com marca própria e distribuidor próprio, a preço menor | Participação e margem bruta de CFTV | Dahua independente no Brasil, distribuidor Sonepar, venda da participação [Imprensa] |
| **Dependência de fornecedor** | Renegociação ou fim da exclusividade Dahua → custo de transferência ↑ ou troca de plataforma (recertificação, PPB, reeducação do instalador) | Margem bruta; risco de ruptura de receita | 28,6% dos pagamentos (2021). O caso FiberHome mostra que exclusividades são renegociadas |
| **Commoditização / deflação tecnológica** | IA embarcada e câmeras de entrada baratas; produto vira commodity | Margem bruta | Margem de Energia caiu de 31% para 26% com solar (2017–20); EBITDA de 6% da Renovigi |
| **E-commerce / desintermediação** | O marketplace liga importador ao consumidor ou instalador sem estoque local e reduz o valor da disponibilidade | Receita (varejo, entrada); preço | Não quantificado nas fontes |
| **Perda de relevância do instalador** | Câmeras Wi-Fi "plug and play" e nuvem: o consumidor instala sozinho e compra direto | Receita e margem do canal principal | Não quantificado; ameaça estrutural ao "loop curto" |
| **Capital de giro** | Mais SKUs, importação de longa distância e crédito ao canal fazem o capital crescer mais rápido que o lucro | **ROIC**, fluxo de caixa livre | CCC de 68 → 145 dias. FCO/lucro de 0,20x (2024) contra 1,90x (2025): o FCL é dominado por oscilação de estoque [P] |
| **Excesso de SKUs / obsolescência** | Ciclo tecnológico curto × 5 meses de estoque | Margem bruta (provisões); ROIC | Provisão para perda de estoques: R$0,6 mi (2019) → R$32 mi (2024) → **R$54 mi (2025)**; baixa de estoque de R$23,7 mi no 1S26 [P; R p.15] |
| **Câmbio** | Custo dolarizado + estoque de ~5 meses → repasse com defasagem. Real forte força corte de preço com estoque caro | Margem bruta (cíclica) | A companhia admite que a parte cíclica da margem do 2T26 vai normalizar [R p.10]. Variação cambial de −R$65 mi (2024) |
| **Regulação fiscal** | Mudanças na Lei de TICs, na ZFM ou na transição da reforma tributária (EC 132/2023) alteram créditos e incentivos | Margem e **NOPAT/ROIC** | Créditos de R$129 mi (2025) ≈ 30% do EBIT *(natureza a confirmar)* |
| **Crédito do canal** | Financiar distribuidores (e integradores solares) transfere risco de inadimplência | Despesa (PCLD); contas a receber | PCLD de R$7,1 mi (2024) → **R$28,8 mi (2025)** [P] |
| **Deterioração da relação com distribuidores** | Venda direta (contas nomeadas, online) ou excesso de sell-in leva o distribuidor a priorizar outra marca | Volume (efeito chicote) | Hoje, relação sell-in/sell-out estável [R p.6]. O ERP no 1T25 mostrou a dependência do fluxo de pedidos |
| **Mudança tecnológica** | O valor migra para software/serviço (vídeo em nuvem, analytics), onde a Intelbras não cobra recorrência | Crescimento e margem de longo prazo | Recorrência não divulgada; HaaS/SaaS era promessa em 2021 [BTG21 s.16] |

---

## 5 insights que realmente importam para a tese de investimento

**1. O ROIC caiu à metade por giro, não por margem.**
- **Fato:** a margem EBIT foi de 10,8% (2019) para 9,5% (2025) e 11,3% (LTM 2T26). O giro do capital caiu de 2,88x para 1,58–1,66x. O CCC foi de 68 para 145 dias, e o capital de giro (R$1,6 bi) supera o imobilizado + intangível (R$1,25 bi).
- **Mecanismo:** o modelo faz da Intelbras o estoque regulador e o financiador do canal. Com mais SKUs, mais categorias e importação de longa distância, o capital cresce mais rápido que o lucro.
- **Consequência:** a alavanca de valor mais potente é o capital de giro.
  - *Estimativa:* 10 dias a menos de CCC liberam R$86–125 mi (CPV ou receita LTM ÷ 365 × 10).
  - Isso vale **+0,6 a +0,9 p.p. de ROIC pré-IR**: R$514 mi / (R$2.740 mi − R$86 a 125 mi) = 19,4–19,7%, contra 18,8%.

**2. A margem é capturada onde o comprador é pulverizado.**
- **Fato:** margem bruta de Segurança de 38–41% (2017–20), contra 26–32% de Energia e TIC. EBITDA de 6% da Renovigi. A margem consolidada foi de 34,9% para 28,4% quando Energia chegou a 33% da receita. No 2T26, o lucro bruto de Energia subiu 12% com receita −13,5% após a redução de solar.
- **Mecanismo:** para o instalador fragmentado, a Intelbras vende disponibilidade + suporte + marca. Para ISPs e integradores solares, vende commodity com preço global.
- **Consequência:** crescer fora do trabalho do instalador dilui margem e ROIC. A poda de GPON e solar é **estruturalmente positiva para a margem e negativa para o crescimento de receita**. A pergunta para o modelo é quanto Segurança e as adjacências conseguem compensar.

**3. O canal pulverizado é uma barreira de tempo, não de tecnologia, e tem custo recorrente.**
- **Fato:** ~500 pontos de distribuição, 80–90 mil revendedores, 98% dos municípios, 71% das vendas via distribuição. ~R$35–40 mil/ano por revendedor *(estimativa)*.
- **Mecanismo:** o distribuidor só estoca o que gira, e só gira o que o instalador sabe instalar e o cliente reconhece. Um entrante precisa subsidiar estoque e treinamento por anos.
- **Consequência:** protege volume e permite repasse a custo de reposição (2T26). Mas a despesa com vendas (~13,5% da receita) **não se dilui com escala**, então a barreira sustenta margem bruta, não expansão de margem EBITDA.

**4. A Dahua é ao mesmo tempo o motor e o principal risco do núcleo.**
- **Fato:** exclusividade de CFTV com a Dahua desde 2018 e 28,6% dos pagamentos a fornecedores (2021). A participação foi de 10% para 7,56%, com venda do restante autorizada em 36 meses (ago/2025). A Dahua opera marca própria no Brasil desde 2016.
- **Mecanismo:** a Intelbras soma canal, marca e regime fiscal a uma plataforma que não controla. À medida que o parceiro constrói canal próprio e sai do capital, o poder de barganha migra para o dono da tecnologia.
- **Consequência:** risco assimétrico na margem bruta de Segurança, a maior fonte de lucro. Os vetores são o preço de transferência, a prioridade de lançamentos e uma eventual renegociação da exclusividade, como aconteceu com a FiberHome em jan/2026.

**5. Parte relevante do lucro é regulatória.**
- **Fato:** alíquota efetiva de IR/CS entre −5,6% e +1,9% (2019–25). Créditos tributários não-caixa de R$99–134 mi/ano (2021–25), equivalentes a 23–30% do EBIT. Nova fábrica de R$200 mi na ZFM.
- **Mecanismo:** produzir sob PPB/ZFM gera crédito da Lei de TICs (condicionado a P&D) e incentivos regionais *(inferência sobre a composição)*.
- **Consequência:** o NOPAT fica próximo do EBIT, o que eleva o ROIC em relação a importadores puros. Mudanças na Lei de TICs, na ZFM ou na reforma tributária afetam margem e ROIC diretamente. **No modelo, trate isso como variável, não como constante.**

---

## Visualizações recomendadas (4)

| # | Gráfico | Mensagem que deve provar | Variáveis | Fonte | Formato |
|---|---|---|---|---|---|
| 1 | **Mix de receita por segmento + crescimento** | "Segurança se compõe; Energia/TIC trazem volatilidade e diluem margem" | Receita por segmento 2019–2025 e 1S26; margem bruta consolidada | [P] Informações por Segmento + Indicadores Anuais | Barras empilhadas (R$ mi) + linha de margem bruta em eixo secundário. Rótulos: CAGR por segmento |
| 2 | **Fluxograma da cadeia de valor** | "O valor é capturado na interface com o mercado brasileiro, não no núcleo tecnológico" | Nós: plataforma (Dahua/FiberHome/componentes) → Intelbras (adaptação, fábricas, marca, estoque) → ~500 distribuidores (71%) → 80–90 mil instaladores → residências/condomínios/PMEs; ramos varejo (13%) e integradores/contas nomeadas (16%). Nas setas: DSO (~100 dias), DIO (~144 dias), quem especifica, quem tem poder | FRE (canais), [BTG21 s.9], [P] (prazos) | Diagrama de fluxo horizontal (estilo Sankey), largura das setas proporcional ao % de vendas |
| 3 | **Mix de canais 2020 × 2024 (+ contagem do canal)** | "A distribuição ainda domina, mas projetos (mais sensíveis a preço) ganham peso" | % distribuição/varejo/integradores; nº de distribuidores e revendedores | [BTG21 s.9] (FRE 2021) e FRE 2025/2026 | Duas barras 100% lado a lado + dois KPIs (370 → 500; 80 mil → 90 mil) |
| 4 | **Flywheel testado** | "O flywheel gira dentro do trabalho do instalador; fora dele, quebra" | Os 8 elos com o status da evidência | Esta análise | Diagrama circular com elos coloridos por evidência (evidenciado / parcial / não evidenciado). Painel lateral: "loop curto" × "loop longo" |

**Extra, se couber um quinto gráfico:** **decomposição do ROIC (margem EBIT × giro), 2019 a LTM 2T26.** Barras de giro e linha de margem. É o gráfico que melhor prova o insight 1. Num slide único, trocaria o gráfico 3 por este.

---

## Pontos a confirmar no FRE 2026

1. Lucro bruto por segmento 2021–2025 (item sobre segmentos operacionais, 1.3).
2. Mix de canais e nº de distribuidores/revendedores em 2025 (1.2–1.4).
3. Participação da Dahua nas compras de 2025 e transações com partes relacionadas (11.2); termos atuais do acordo de exclusividade.
4. Natureza dos "créditos tributários" (Lei de TICs × outros) e % da receita com produtos sob PPB (1.6 e notas das DFs).
5. Metodologia dos market shares (44% / 9% / 19% / 1,9%): universo, sell-in ou sell-out, R$ ou unidades. **Nas fontes fornecidas, a metodologia não é divulgada; trate como estimativa da companhia.**
6. Lista de unidades fabris e o que cada uma produz.

---

### Fontes externas

- [Genial Analisa — "Intelbras (INTB3): o poder da distribuição"](https://analisa.genialinvestimentos.com.br/setores/tecnologia/intelbras-s-a-intb3-o-poder-da-distribuicao/): mix de canais 71/13/16, ~500 distribuidores, 80 mil+ revendedores, Dahua
- [Nord Research — "Por que estamos tão confiantes?"](https://www.nordinvestimentos.com.br/blog/intelbras-intb3-por-que-estamos-confiantes/): Dahua como principal parceiro; exclusividade de CFTV e 28,6% dos pagamentos (2021)
- [Prospecto preliminar do IPO (Itaú BBA)](https://ww69.itau.com.br/fileserver/relatorios/intelbras-sa-ind-telecom-eletro-bra-prospecto-pre.pdf): acordo de cooperação com a Dahua
- [Brazil Journal — investidor vende 2,5% da Intelbras](https://braziljournal.com/intelbras-investidor-vende-25-da-companhia/)
- [FilingReader — Dahua to sell 7.56% stake in Intelbras (15/08/2025)](https://filingreader.com/news-wire/shenzhen/2025-08-15/dahua-technology-to-sell-756-stake-in-intelbras)
- [Dahua — "Dahua Technology Brasil ganha independência da América Latina"](https://www.dahuasecurity.com/br/newsEvents/pressRelease/4974)
- [IT Forum — Dahua e Dimensional (Sonepar)](https://itforum.com.br/?p=165693)
- [IT Forum — Programa de Canais Intelbras](https://itforum.com.br/?p=115366)
- [Teletime — fim da exclusividade GPON FiberHome (12/01/2026)](https://teletime.com.br/12/01/2026/intelbras-anuncia-fim-da-exclusividade-na-venda-de-gpon-da-fiberhome/)
- [DPL News — Abrint sobre o antidumping de cabos ópticos](https://dplnews.com/abrint-se-pronuncia-sobre-os-efeitos-da-medida-antidumping-sobre-cabos-de-fibra-optica/)
- [Resolução Gecex nº 837/2025](https://okai.com.br/documento/2025-12-22/resolucao-gecex-nº-837-de-19-de-dezembro-de-2025) e [nº 829/2025](https://okai.com.br/documento/2025-12-22/resolucao-gecex-nº-829-de-19-de-dezembro-2025)
- [Teletime — R$200 mi em nova fábrica em Manaus](https://teletime.com.br/27/04/2026/intelbras-vai-investir-r-200-milhoes-em-nova-fabrica-em-manaus/) e [Forbes — terreno em Manaus](https://forbes.com.br/forbes-money/2026/04/intelbras-compra-terreno-em-manaus-para-apoiar-aumento-de-capacidade-de-producao/)
- [NSC Total — unidade na Zona Franca desde 2009](https://www.nsctotal.com.br/?p=7889576) e [NSC Total — fábrica de fibra óptica em Tubarão](https://www.nsctotal.com.br/?p=6855705)
- [Brazil Journal — Intelbras compra Renovigi](https://braziljournal.com/intelbras-compra-renovigi-e-dobra-aposta-em-energia-solar) e [InfoMoney — Renovigi por R$334 mi](https://www.infomoney.com.br/mercados/intelbras-intb3-anuncia-compra-da-empresa-de-energia-solar-renovigi-por-r-334-milhoes/amp/)
- [Nord Research — resultados 3T25](https://www.nordinvestimentos.com.br/blog/intelbras-intb3-resultados-3t25/): margem bruta de TIC de 26,8%
- [Safra O Especialista — Intelbras 2T26](https://oespecialista.safra.com.br/analise/intelbras-2t26-margens-lucro/): margem bruta ex-AVP
- [Nord Research — resultados 4T25](https://www.nordinvestimentos.com.br/blog/intelbras-intb3-resultados-4t25/)

*Esta é uma análise do modelo de negócios, não uma recomendação de investimento.*
