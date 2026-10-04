# Intelbras (INTB3) — Análise setorial

**Pergunta central:** como a estrutura dos mercados em que a Intelbras atua determina crescimento, market share, pricing, margens, retorno sobre capital e risco competitivo da companhia?

**Legenda**
- **[DADO]**: número publicado, com fonte indicada.
- **[ESTIMATIVA]**: cálculo meu a partir de dados publicados. A fórmula aparece no texto.
- **[INFERÊNCIA]**: conclusão analítica, que pode ser testada com os dados listados em (D).

**Fontes primárias**
- Formulário de Referência 2026, v2 → [FRE item, p.]
- Demonstrações Financeiras 2025 → [DFP NE nº]
- Release 2T26 → [Rel. p.]
- Planilha interativa 2T26 → [Planilha]
- Apresentação BTG CEO Conference 2021, só como série histórica → [BTG21 s.]

**Fontes externas:** [E#], com lista e links ao final.

**Data-base:** 04/10/2026. Valores em R$ milhões, salvo indicação.

---

## Tese setorial em uma frase

**A Intelbras não pertence a um setor, e sim a três.**
- **Só Segurança** combina posição dominante, canal cativo e retorno acima do custo de capital.
- **Nos três negócios, o preço é definido fora da empresa:** custo global da tecnologia × câmbio.
- **O retorno acima do custo de capital vem, em boa parte, de política pública.** Sem o crédito de ICMS de Manaus, o retorno de Segurança cai para perto da Selic.

Por isso o valor da INTB3 depende menos do crescimento dos mercados e mais de três variáveis:
1. a transição tributária **fora** da Zona Franca de Manaus (ZFM);
2. a renovação do acordo com a Dahua em 2028;
3. o custo de capital de giro que o canal exige.

---

# PARTE I — Resultado da pesquisa

## (A) Principais achados

**1. Os incentivos fiscais são 95% do lucro líquido, mas não geram retorno anormal. Funcionam como paridade contra o importado.**
- [DADO] Incentivos reconhecidos em 2025: **R$459,7 mi** [DFP NE 23]. Equivalem a:
  - **10,3% da receita** líquida;
  - **84,8% do EBITDA**;
  - **108% do EBIT**;
  - **95,0% do lucro líquido**.
- [DADO] Alíquota efetiva de IR/CSLL: **0,74%** [DFP NE 24].
- [ESTIMATIVA] Mesmo com os incentivos, o ROIC pré-IR de 2025 foi **15,1%**, praticamente igual à Selic [Planilha; E10].
- [INFERÊNCIA] O incentivo leva o retorno até o custo de capital; não muito além. O risco econômico está concentrado nos **R$279,7 mi fora da ZFM**:
  - crédito da Lei de TICs, com vencimento em 2029;
  - ICMS de SC/MG/PE, com vencimento em 2032.
- *Importa porque* o modelo deve tratar o incentivo como linha explícita, com degrau em 2029/2033 e hipótese de repasse ao preço. Não deve ser tratado como perda integral de 95% do lucro.

**2. Segurança é o único negócio que cria valor, e metade desse valor é o incentivo de Manaus.**
- [ESTIMATIVA] ROIC pré-IR por segmento:
  - **Segurança ~28%**;
  - **TIC ~7,5%**;
  - **Energia ~6%**.
- [ESTIMATIVA] Excluindo o crédito de ICMS do Amazonas (R$180,0 mi, ligado à fábrica de Manaus, que é de Segurança), Segurança cai para **~14,7%**.
- *Importa porque* o valor da companhia está em um segmento cujo excesso de retorno depende do incentivo mais durável (ZFM, até 2073), mas não exclusivo: a Multilaser monta Hikvision em Manaus [E3].

**3. O crescimento recente de Segurança vem do mercado, não de ganho de share.**
- [DADO] Share MIDI: 43% (2024) → 44% (2025). Receita de Segurança: +4,9% em 2025 [FRE 1.4, p.24; DFP NE 31].
- [ESTIMATIVA] Mercado implícito em 2025: **≈ +2,5% nominal**. Cálculo: 1,049 × 43/44 − 1.
- [DADO] A série histórica do MIDI tem quebras de definição: 43% (2020, CFTV) → 54% (c.2022, CFTV) → 43% (2024, BU inteira) [BTG21 s.11; E30; FRE].
- Ganho estrutural de share: **NÃO COMPROVADO**.
- *Importa porque* a premissa de crescimento de Segurança deve seguir o mercado. Ganho de share não é um caso-base defensável.

**4. O moat existe no canal, não no hardware. Mas é comprado e não gera escala de custo.**
- [DADO] Canal:
  - ~95% dos distribuidores aderem por opção à exclusividade de linha (programa Mais Verde);
  - 68% das vendas passam por ~500 pontos de distribuição;
  - há mais de 90 mil instaladores ativos [FRE 1.2, p.6–7; 1.4, p.22].
- [DADO] Custo do canal:
  - SG&A/receita: 20,3% (2019) → 17,4% (2022) → 19,3% (2025);
  - ciclo de caixa: 68 → 145 dias [Planilha].
- *Importa porque* o canal defende margem bruta e share em Segurança, mas não expande a margem EBIT. A alavancagem operacional é limitada.

**5. A Intelbras é tomadora de preço com defasagem. A margem bruta depende da distância entre o custo de reposição e o custo médio do estoque.**
- [DADO] Fatos de preço e custo:
  - a própria companhia diz que "o mercado define os preços" [FRE 2.2, p.71];
  - ~80% do custo dos produtos vendidos (CPV) está atrelado a moeda estrangeira;
  - estoque de **173 dias** de CPV [DFP NE 8].
- [DADO] Margem bruta:
  - caiu de 33,9% (1T24) para 29,0% (4T24), com o dólar subindo 27,9% em 2024;
  - subiu para 33,1% no 2T26 por "precificação a custo de reposição", efeito que a companhia chama de **transitório** [Rel. p.2–3].
- *Importa porque* a margem do 2T26 não deve ser extrapolada. [INFERÊNCIA] A margem normalizada fica em ~30–31%.

**6. A Dahua dá tecnologia e financia o capital de giro, mas é dependência.**
- [DADO] Compras da Dahua: R$729 mi em 2025 (−38,6% a/a), equivalentes a 36% dos gastos com fornecedores. Saldo a pagar: R$449 mi [DFP NE 32; FRE 1.4.e].
- [ESTIMATIVA] Prazo implícito de pagamento à Dahua: **225 dias**. As compras equivalem a **~40% do CPV de Segurança**.
- Prazo do acordo: dez/2028.
- [DADO] Precedente: a FiberHome encerrou a exclusividade do GPON em jan/2026 [E27].
- *Importa porque* a renovação de 2028 é o maior evento de risco isolado sobre a margem do segmento que gera 68% do lucro bruto.

**7. Drivers de Segurança que você sugeriu: a demanda responde à percepção de risco e à obra, não ao crime medido.**
- [DADO] O crime medido cai:
  - mortes violentas intencionais (MVI): −8,2% em 2025;
  - roubos e furtos de celular: −7,7% [E4].
- [DADO] A percepção de insegurança sobe: segurança como maior problema do país passou de 17% (out/24) para 38% (nov/25) e 30% (jun/26) [E5, E6].
- [DADO] Lançamentos imobiliários: +30,1% em unidades em 2025, sendo 86% do programa Minha Casa Minha Vida (MCMV) até outubro [E8].
- [INFERÊNCIA] Esses drivers **sustentam** a demanda, mas não a **aceleram**. A obra chega à instalação com 2–3 anos de defasagem.
- *Importa porque* projetar Segurança pelo "medo" gera viés de alta. A âncora correta são as entregas de obra (defasadas) e o retrofit de condomínios.

**8. Driver de TIC que você sugeriu: o 5G é fraco como driver direto.**
- [DADO] Contexto do mercado:
  - banda larga fixa cresceu +2,7% em 2025, com 79% em fibra e 63% dos acessos nas prestadoras de pequeno porte (PPPs) [E25, E26];
  - o 5G deve cobrir 80% da população até o fim de 2026 [E22];
  - a Intelbras vende CPE 5G (aparelho na casa do cliente) feito com a Qualcomm [E23].
- [INFERÊNCIA] Quem compra CPE é a operadora. Além disso, o acesso fixo sem fio (FWA) concorre com a fibra dos provedores, que são os clientes de GPON da Intelbras.
- *Importa porque* o espaço real de TIC está em redes empresariais e em cabeamento, este com antidumping até ~2030. Não está em GPON nem em 5G.

**9. Energia: a queda é solar, que é commodity global em contração. Energia sem solar tem estrutura parecida com a de Segurança, mas com outro líder.**
- [DADO] Mercado solar no Brasil:
  - potência adicionada: −29% em 2025 (15 → 10,6 GW);
  - investimento: −40%;
  - Fio B (encargo de rede pago pelo gerador) em 60% em 2026 [E20, E21].
- [DADO] Receita de Energia da Intelbras: −31% em 2025.
- *Importa porque* a queda do segmento não é deterioração do núcleo. Solar deve ser avaliado como opção, separado do restante.

**10. As regras de importação protegem parte do portfólio e expõem outra.**
- [DADO] Mudanças recentes:
  - o Imposto de Importação de 20% sobre remessas de até US$50 foi zerado (MP de 13/05/2026; aprovada pelo Congresso em 03/09/2026) [E15];
  - há antidumping sobre fibra e cabos ópticos da China por até 5 anos (Gecex 829/837, dez/2025) [E17];
  - a Anatel fiscaliza marketplaces com IA (Regulatron) [E13].
- *Importa porque* cabeamento ganha preço protegido. O varejo plug-and-play (16% das vendas) fica exposto ao cross-border, inclusive à Imou, a marca de consumo da própria Dahua [E36].

---

## (B) Evidências

| # | Evidência | Dado | Fonte | Tipo | Importa para o acionista porque… |
|---|---|---|---|---|---|
| 1 | Incentivos por natureza (2025) | ICMS-AM 180,0; ICMS-SC 123,6; ICMS-MG 24,6; ICMS-PE 8,1; crédito da Lei de TICs 123,3. **Total 459,7** (2024: 514,7) | DFP NE 23 | [DADO] | …define quanto do lucro está sujeito a datas legais (2029, 2032, 2033, 2073) |
| 2 | Onde o incentivo entra no resultado | ICMS reduz as deduções de venda (sobe a receita líquida e o lucro bruto). Lei de TICs entra em "outras receitas operacionais" | DFP NE 3.13 | [DADO] | …a margem bruta reportada de 30,1% seria **24,4%** sem o ICMS incentivado. A margem "industrial" é menor do que parece |
| 3 | Alíquota efetiva | 0,74% (2025); 2,64% (2024). Incentivos excluídos da base de IR/CSLL | DFP NE 24 | [DADO] | …o lucro líquido é quase igual ao lucro antes do IR. Qualquer mudança na tributação das subvenções atinge o lucro diretamente |
| 4 | Retorno consolidado | ROIC pré-IR: 31,2% (2019) → 15,1% (2025) → 18,8% (LTM 2T26) | Planilha; Rel. p.6 | [DADO] | …mesmo com incentivos, o retorno ficou perto da Selic de 13,75–14,75% |
| 5 | Capital por segmento (2025) | Ativo operacional − fornecedores: Segurança 1.357; TIC 821; Energia 670 | DFP NE 31 | [DADO] | …permite estimar o ROIC por segmento: Segurança ~28%, TIC ~7,5%, Energia ~6% |
| 6 | Share MIDI | Segurança 44% (2025) / 43% (2024); TIC 9% / 9%; Energia sem solar 19% / 19%; solar 1,9% | FRE 1.4, p.10 e 24–26 | [DADO, metodologia própria] | …mostra posição estável. Nenhuma BU ganhou share em 2025 |
| 7 | Share e mercado em 2020 | CFTV 43% (R$2,2 bi); controle de acesso 27% (R$1,2 bi); redes 25% (R$2,1 bi); comunicação 18% (R$1,2 bi); power 10% (R$0,9 bi); solar 2,1% (R$6,1 bi) | BTG21 s.11 | [DADO companhia] | …é a única série anterior. Mostra que o universo de TIC mudou |
| 8 | Concorrentes nomeados | Segurança: Hikvision, JFL, PPA, Control iD, Garen. TIC: Huawei, Cisco, TP-Link, Furukawa, Logitech, Motorola, Multilaser. Energia: Legrand, Schneider, TS Shara, WEG | FRE 1.4, p.26 | [DADO] | …os rivais variam por categoria. Um competidor "geral" não existe |
| 9 | Escala global | Hikvision: receita de RMB 92,5 bi (US$12,95 bi), lucro de RMB 14,2 bi, exterior US$3,81 bi. Dahua: RMB 32,3 bi | E1, E2 | [DADO] | …a Hikvision tem **16x** a receita total da Intelbras e **4,8x** só fora da China. Escala de P&D e compras não é vantagem da Intelbras |
| 10 | Hikvision no Brasil | A Multilaser monta HiLook (Hikvision) em Manaus desde 2022, com investimento de R$6 mi | E3 | [DADO] | …a vantagem de "fabricante local na ZFM" é replicável, e barata |
| 11 | Programa de canais | PCI: proteção de preços, rotação de estoque ocioso, leads, metas quadrimestrais, reporte de sell-out, suporte a registro de projeto. Mais Verde: 95% dos distribuidores, desconto de 2–9%, exclusividade voluntária | FRE 1.2, p.6–7 | [DADO] | …o canal é cativo por contrato econômico, não por lock-in técnico |
| 12 | Treinamento | 370 mil qualificações em 2025; mais de 1.000 cursos; 2 mi de certificados acumulados | FRE 1.1, p.1; p.14 | [DADO companhia] | …é o ativo mais lento de replicar: custo de aprendizado do instalador |
| 13 | Dahua | Compras de R$729 mi (2025) e R$1.187 mi (2024); saldo de R$449 mi (consolidado); acordo até 31/12/2028; 7,56% do capital; venda autorizada em até 36 meses | DFP NE 32; FRE 11.2; E37 | [DADO] | …concentra custo, financiamento e governança na mesma contraparte |
| 14 | Exposição cambial | Fornecedores em USD: R$894 mi; NDF: R$451 mi (cobertura de ~50%); ±10% no dólar = ∓R$26 mi no resultado financeiro | DFP NE 25 | [DADO] | …o risco relevante é operacional (custo de reposição), não o financeiro |
| 15 | Composição do estoque | Produtos acabados 733; matéria-prima 428; importações em andamento 318; provisão de obsolescência 73 (2024: 47) | DFP NE 8 | [DADO] | …a defasagem entre câmbio e CPV é de ~2 trimestres. A obsolescência cresce |
| 16 | Margem bruta trimestral | 33,9% (1T24) → 29,0% (4T24) → 30,7% (4T25) → 33,1% (2T26) | Planilha | [DADO] | …a margem oscila ±2–5 p.p. com câmbio e custo de componentes |
| 17 | Crime vs percepção | MVI −8,2% (2025, 19,1 por 100 mil); segurança como maior problema: 17% → 38% → 30% | E4, E5, E6 | [DADO] | …o driver é percepção, que pode reverter, e não tendência de criminalidade |
| 18 | Construção | Lançamentos +30,1% em unidades (2025); jan–out: 161.709 unidades, 85,9% MCMV; médio e alto padrão +14,3% | E8 | [DADO] | …demanda de Segurança, TIC e nobreaks na entrega das obras, em 2027–28 |
| 19 | Condomínios | 13,3 mi de unidades residenciais em condomínio (CNEFE); mais de 14 mil condomínios com portaria remota; serviço cresceu +24% em 2024 | E9, E7 | [DADO, fonte secundária] | …o retrofit do estoque existente é um driver maior e menos cíclico que lançamentos |
| 20 | Telecom | Banda larga fixa: 53,9 mi de acessos (dez/25, +2,7%); fibra ~79%; PPPs 63,3% | E25, E26 | [DADO] | …o GPON está em maturação. Volume menor e risco de crédito do provedor |
| 21 | 5G | 80% da população coberta até o fim de 2026; Intelbras fabrica CPE 5G com a Qualcomm em São José desde 2022 | E22, E23 | [DADO] | …a exposição é a um nicho de CPE, comprado pelas operadoras |
| 22 | Solar | Potência adicionada: 15 → 10,6 GW (−29%); geração distribuída 7,8 GW; investimento R$54,9 → 32,9 bi (−40%); Fio B 60% (2026) → 90% (2028) | E20, E21 | [DADO] | …explica a maior parte da queda de Energia sem envolver o núcleo |
| 23 | Antidumping | US$2,42/kg sobre cabos ópticos e US$47,46/kg sobre fibra monomodo da China, por até 5 anos; fábrica de Tubarão "próxima da capacidade máxima" | E17; Rel. p.8 | [DADO] | …preço protegido até ~2030, com volume limitado pela capacidade |
| 24 | Cross-border | Desde 13/05/2026: II 0% para compras de até US$50, mais ICMS de 17–20%. Encomendas internacionais caíram 11% em 2024 com a taxa de 20% | E15, E16 | [DADO] | …a volta do II zero reabre a importação direta de câmeras Wi-Fi e roteadores |
| 25 | Reforma tributária | IPI mantido só para produtos com industrialização na ZFM; créditos presumidos de IBS/CBS na ZFM; Fundo de Compensação de R$160 bi para benefícios onerosos de ICMS em 2029–32 | E18, E19 | [DADO] | …ZFM preservada; incentivos de SC/MG/PE com data de fim |

---

## (C) Contradições encontradas

| # | Fonte A diz | Fonte B diz | Leitura [INFERÊNCIA] |
|---|---|---|---|
| 1 | Crime em queda: MVI −8,2%, celulares −7,7% [E4] | Insegurança como maior problema: 17% → 38% [E5] | A demanda segue a **percepção**. Se a percepção normalizar, cai a compra residencial discricionária |
| 2 | Share de CFTV de 43% (2020) [BTG21] e 54% (c.2022) [E30] | Share de Segurança de 43% (2024) e 44% (2025) [FRE] | Mudou a definição (CFTV → BU inteira), não necessariamente a posição. **Não há série comparável** |
| 3 | TIC: redes 25% + comunicação 18% em 2020, num mercado de R$3,3 bi [BTG21] | TIC 9% em 2025 [FRE] | [ESTIMATIVA] O mercado implícito iria de R$3,3 bi para R$10,9 bi (+27% a.a.), o que não é plausível. Logo, o **universo do MIDI foi ampliado** |
| 4 | Dahua com "prioridade" de fornecimento [FRE 1.2] | Compra "exclusiva" [FRE 1.4, 4.1; DFP NE 32] | A natureza da obrigação muda o poder de barganha. É preciso ler o contrato |
| 5 | Saldo a pagar à Dahua de R$524,4 mi [FRE 11.2] | R$448,8 mi no consolidado e R$430,2 mi na controladora [DFP NE 32] | Diferença de R$76–94 mi. Pode ser data, perímetro ou inclusão de risco sacado |
| 6 | Dahua sobe de 28,6% (2021) para 36% dos gastos com fornecedores [FRE; Ext.] | Compras da Dahua caem 38,6% em 2025, com Segurança crescendo +4,9% | Redução de estoque (estoques de 1.773 → 1.474) explica parte. Também pode ter havido diversificação, não mensurável |
| 7 | "Fortaleza muito grande contra potenciais concorrentes" [FRE 1.4, p.22] | Revendas podem "trabalhar diretamente com nossos concorrentes" [FRE 4.1, p.97]; integradores multimarca [FRE p.23] | A fidelidade é real em Segurança residencial e PME. É fraca em projetos e no varejo |
| 8 | Incentivos = 95% do lucro líquido | ROIC pré-IR de 15,1% ≈ Selic | Se o incentivo fosse margem extra, o retorno estaria bem acima do custo de capital. É **paridade** |
| 9 | Abese: mercado +16,1% em 2024 e indústria com previsão de +23,7% em 2025 [E7] | FRE: "evolução moderada"; mercado implícito de +2,5% em 2025 | A Abese inclui serviços (monitoramento, portaria). O mercado de equipamentos cresce menos |
| 10 | Vantagem de "fabricação nacional" [FRE] | Hikvision montada em Manaus pela Multilaser [E3] | A vantagem fiscal é de regime, não de empresa. Diferencia contra importadores, não contra montadores locais |
| 11 | "Parte do ganho é cíclica (custo de reposição)" [Rel. p.2] | "Outra parte é estrutural (mix)" [Rel. p.3] | A divisão não foi quantificada. A margem normalizada é a principal incerteza de curto prazo |
| 12 | Exclusividade de "Produtos Dahua no Brasil" [FRE 1.2] | Câmeras Imou (marca de consumo da Dahua) vendidas via AliExpress [E36] | O escopo da exclusividade parece não cobrir o cross-border nem submarcas |
| 13 | 2023: aposta de que o FWA 5G chegaria a "até 20% da banda larga" [E24] | Fibra com ~79% da banda larga fixa em 2025 [E25] | A tese do 5G não se materializou na escala esperada |

---

## (D) Lacunas de informação

| Lacuna | Por que importa | Onde buscar |
|---|---|---|
| Share independente (Omdia, IDC) de CFTV, controle de acesso, roteadores e switches no Brasil; shares de #2 e #3 | Validar ou contestar o MIDI. Sem isso, "liderança" é afirmação da companhia | Omdia Video Surveillance; IDC Networking Tracker; Comex Stat por NCM |
| Receita por subcategoria (CFTV × acesso × alarme; GPON × redes empresariais × cabeamento; solar × sem solar) | Separar crescimento estrutural de mix | Teleconferências; RI; Investor Day |
| Série consistente do MIDI desde 2019 | Distinguir share estável, temporário ou crescente | FREs de 2020 a 2025, item 1.4.c |
| Preço relativo Intelbras × Hikvision × TP-Link por SKU equivalente; margem do distribuidor e do revendedor | Medir se há prêmio de marca (pricing power) | Levantamento de preços em distribuidores; entrevistas de canal |
| Conteúdo Intelbras em R$ por unidade habitacional (MCMV × médio × alto padrão) | Converter lançamentos em receita | Incorporadoras; instaladores; companhia |
| Elegibilidade ao Fundo de Compensação: os benefícios de SC/MG/PE são "onerosos" e estão registrados na LC 160? | Define se o ICMS de 2029–32 é compensado | RI; nota fiscal; Receita Federal (habilitação de 2026 a 2028) |
| Tributação das subvenções após a Lei 14.789/2023: a exclusão integral de 2025 tem respaldo ou contingência? | 34% × R$459,7 mi = R$156 mi, ou 32% do lucro | Notas de contingência; parecer jurídico; RI |
| Escopo do acordo Dahua (submarcas, cross-border, renovação de 2028, efeito da venda das ações) | Risco nº 1 sobre a margem de Segurança | FRE 11.2 (íntegra); fato relevante; RI |
| Lead time por categoria; % de produto acabado importado × montado localmente | Medir a defasagem câmbio → CPV por BU | RI; dados de importação por NCM |
| Margem bruta trimestral por segmento antes de 2024 | Separar efeito câmbio de efeito mix | ITRs de 2019 a 2023 |
| Receita de CPE 5G / FWA; base de acessos FWA na Anatel | Dimensionar o driver 5G | Anatel (painel de dados); RI |
| Churn de revendedores; receita por revendedor; compra cruzada entre BUs | Testar o flywheel | RI; programa Pontua |
| Receita da Hikvision no Brasil | Dimensionar o #2 | Relatório anual da Hikvision (segmentação geográfica é limitada) |

---

## (E) Teses de slides, da mais para a menos importante

| # | Tese (título argumentativo) | Eixo | Força da evidência | Linha financeira |
|---|---|---|---|---|
| 1 | **Incentivos equivalem a 95% do lucro, mas funcionam como paridade contra importados; o risco econômico está nos R$280 mi fora da ZFM após 2029–2032** | Regulação | Alta (DFP), com inferência no repasse | EBITDA, lucro líquido, ROIC |
| 2 | **O moat está no canal, não no hardware: 95% dos distribuidores exclusivos protegem share em Segurança, mas a fidelidade é comprada e não gera escala de custo** | Competição | Média-alta | Margem bruta, SG&A, capital de giro |
| 3 | **Segurança concentra o valor (68% do lucro bruto, ROIC ~28%), mas cresce com o mercado e metade do excesso de retorno é o incentivo de Manaus** | Competição / BU | Média (ROIC estimado) | Receita, ROIC |
| 4 | **Preço é ancorado no custo global e no câmbio; a Intelbras captura margem apenas na defasagem de ~170 dias de estoque** | Preços | Alta | Margem bruta |
| 5 | **Dahua dá tecnologia e financia 225 dias de capital de giro, mas concentra ~40% do custo de Segurança num contrato que vence em 2028** | Supply chain / Competição | Alta | Margem bruta, capital de giro, ROIC |
| 6 | **A demanda de Segurança segue a percepção de risco e a obra, não o crime: o medo sobe com o crime em queda e os lançamentos recordes só chegam à instalação em 2027–28** | Macro (seus drivers) | Média | Receita |
| 7 | **Juros altos comprimem Energia e TIC mais que Segurança, criando sensibilidades distintas dentro do portfólio** | Macro | Média-alta | Receita, PCLD, capital de giro |
| 8 | **TIC tem 9% de share porque enfrenta escala global e compradores técnicos; o espaço real está em redes empresariais e cabeamento, não em GPON nem 5G** | Competição / Macro (seu driver) | Média | Receita, ROIC |
| 9 | **Energia sem solar é um negócio de canal defensável; solar é commodity global em contração e explica a queda de 31% do segmento** | BU | Média-alta | Receita, margem |
| 10 | **Regras de importação protegem cabos e o canal profissional, mas o II zero no cross-border expõe o varejo plug-and-play** | Regulação | Média | Receita e margem do varejo |

Teses do roteiro que **não** passaram no teste de evidência:
- **"Segurança combina liderança e crescimento"**: a liderança se sustenta, mas o crescimento recente é de mercado e o ganho de share não está comprovado. Foi incorporada à tese 3 com a ressalva.
- **"Reforma tributária reduz a vantagem de localização"**: é verdadeira só fora da ZFM. Dentro da ZFM, a reforma preserva e até reforça a vantagem (IPI mantido para produtos fabricados lá). Foi incorporada à tese 1.

---

# PARTE II — Análise

## 1. Intelbras não é um setor: mapa econômico por BU

| | **Segurança** | **TIC** | **Energia** |
|---|---|---|---|
| Receita 2025 [DFP NE 31] | 2.730 (61%) | 977 (22%) | 753 (17%) |
| Δ 2025 / Δ 1S26 [Planilha] | +4,9% / +5,8% | −8,0% / +13,7% | −31,0% / −12,4% |
| CAGR 2019–25 | 18,1% | 9,2% | 36,7% (pico em 2022: 1.408) |
| Margem bruta 2025 | 33,2% | 25,7% | 24,6% |
| % do lucro bruto | 67,5% | 18,7% | 13,8% |
| Capital operacional líquido¹ | 1.357 | 821 | 670 |
| Lucro bruto / capital | 66,8% | 30,5% | 27,7% |
| Giro (receita / capital) | 2,01x | 1,19x | 1,12x |
| **ROIC pré-IR estimado²** | **~28%** | **~7,5%** | **~6%** |
| Submercados | CFTV analógico e IP, DVR/NVR, câmeras Wi-Fi, controle de acesso, alarmes, incêndio, comunicação condominial, software (Seventh) | Redes empresariais, Wi-Fi, GPON, cabos ópticos e UTP, cabeamento estruturado, telefonia e comunicação unificada (Khomp), rádios, CPE 5G | Fontes, nobreaks, baterias, proteção, carregadores de veículo elétrico; solar on e off-grid |
| Share MIDI 2025 | 44% | 9% | 19% sem solar; 1,9% em solar |
| Tamanho implícito³ | ~R$6,2 bi | ~R$10,9 bi | n.d. (receita sem solar não divulgada) |

¹ Ativos do segmento (contas a receber, estoques, imobilizado e intangível) menos fornecedores [DFP NE 31].

² [ESTIMATIVA] Fórmula:

> ROIC_seg ≈ (Lucro bruto_seg − SG&A consolidado/receita × Receita_seg) ÷ Capital_seg

Passo a passo para Segurança:
- SG&A consolidado ÷ receita = (603,9 + 257,5) ÷ 4.460,4 = **19,3%**.
- Lucro operacional do segmento = 906,7 − 19,3% × 2.730,3 = 906,7 − 527,3 = **379,5**.
- ROIC = 379,5 ÷ 1.357,1 = **28,0%**.
- Mesmo cálculo para TIC: (250,7 − 188,7) ÷ 821,2 = **7,5%**.
- Mesmo cálculo para Energia: (185,1 − 145,4) ÷ 669,6 = **5,9%**.

Limitações do cálculo:
- o SG&A é rateado pela receita;
- o crédito da Lei de TICs (R$123 mi, em outras receitas) não foi alocado;
- o capital exclui caixa e tributos.

Segurança sem o ICMS-AM: (379,5 − 180,0) ÷ 1.357,1 = **14,7%**.

³ [ESTIMATIVA] Receita Intelbras ÷ share MIDI. **Só vale se o MIDI for comparável à receita**, o que não é garantido (ver 3.3).

**Erro comum.** Somar os três mercados em um "TAM de R$17 bi" mistura mercados com compradores, concorrentes e retornos diferentes. Esse número não serve para nada no valuation.

**Conclusão [INFERÊNCIA].** O valuation consolidado deve ser ponderado pela economia de Segurança:
- Segurança gera 68% do lucro bruto com o maior giro;
- TIC e Energia, no nível atual de margem, rendem abaixo da Selic (13,75%). Crescer nelas sem mudar a margem **destrói valor**.

---

## 2. Regulação

### 2.1 Mapa regulatório: barreira, custo, vantagem local ou risco?

| Norma | Mercado | Função econômica | Efeito para a Intelbras |
|---|---|---|---|
| **Lei de TICs** (Lei 8.248/91, alterada pela Lei 13.969/19) + **PPB** (Processo Produtivo Básico: roteiro mínimo de etapas fabris no Brasil exigido para o incentivo) | TIC, Segurança e Energia fora da ZFM | **Vantagem local + custo de compliance.** Gera crédito financeiro sobre PD&I, mas exige aplicar ≥4% do faturamento incentivado em PD&I [DFP NE 23] | R$123,3 mi (2,8% da receita). Vence em **31/12/2029** |
| **Zona Franca de Manaus** + SUFRAMA | Segurança (Manaus) | **Vantagem local durável:** isenção de IPI, II reduzido sobre insumos, crédito estímulo de ICMS-AM (R$180,0 mi), SUDAM com −75% de IRPJ até 2033 [FRE 1.6; DFP NE 23] | O incentivo mais valioso e mais durável (até 2073). **Não exclusivo:** Multilaser/Hikvision também usam [E3] |
| ICMS estaduais (SC, MG, PE), convalidados pela LC 160 | Todas | **Vantagem local temporária** | R$156,4 mi. Válidos até **2032** |
| **Reforma tributária** (EC 132/2023, LC 214/2025, LC 227/2026) | Todas | **Risco estrutural fora da ZFM; proteção dentro dela** | IPI zerado a partir de 2027, exceto para produtos com industrialização na ZFM; créditos presumidos de IBS/CBS na ZFM; ICMS extinto em 2033 [E18] |
| **Fundo de Compensação de Benefícios Fiscais** | ICMS oneroso | **Mitigante 2029–32:** R$160 bi; habilitação 2026–28; compensações 2029–32 [E19] | Só cobre benefícios onerosos concedidos até 31/05/2023 e registrados na LC 160. **Elegibilidade da Intelbras não divulgada** |
| **Anatel** (homologação) + Regulatron | Rádio, Wi-Fi, câmeras sem fio, GPON, CPE | **Barreira de entrada + custo de compliance.** 8,02 mi de produtos irregulares retirados desde 2018; 4.226 apreensões em CDs de marketplaces na Black Friday de 2024, incluindo câmeras sem fio e equipamentos de rede [E13, E14] | Protege marcas homologadas contra o importado informal. A fiscalização é parcial |
| **Remessa Conforme** / "taxa das blusinhas" | Varejo, plug-and-play | **Antes protegia; agora expõe.** 20% de II até US$50 (ago/2024 a mai/2026) → **0%** desde 13/05/2026, mais ICMS de 17–20% [E15, E16] | Câmeras Wi-Fi e roteadores baratos voltam a competir direto do exterior |
| **Antidumping** (Gecex 829 e 837/2025) | Cabos ópticos e fibra | **Barreira temporária** (até 5 anos) [E17] | Tubarão perto da capacidade máxima [Rel. p.8]. Preço protegido, volume limitado |
| **Lei 14.300/2022** (Fio B) | Solar (geração distribuída) | **Risco de demanda:** Fio B a 60% em 2026, 75% em 2027 e 90% em 2028; regras da Aneel a partir de 2029 [E20] | Payback (prazo de retorno do sistema) mais longo → menos instalações |
| II sobre módulos fotovoltaicos | Solar | Custo maior para o integrador | A Absolar cita o aumento entre as causas da queda de 2025 [E21] |

### 2.2 Os incentivos quantificados

| | 2024 | 2025 | Vencimento | Contabilização |
|---|---|---|---|---|
| Crédito financeiro, Lei 13.969/19 | 138,1 | 123,3 | 31/12/2029 | Outras receitas operacionais |
| ICMS-AM (crédito estímulo) | 183,1 | 180,0 | 31/12/2032 (ICMS) / ZFM 2073 | Deduções de venda |
| ICMS-SC | 153,8 | 123,6 | 31/12/2032 | Deduções de venda |
| ICMS-MG | 30,8 | 24,6 | 31/12/2032 | Deduções de venda |
| ICMS-PE | 8,9 | 8,1 | 31/12/2032 | Deduções de venda |
| **Total** | **514,7** | **459,7** | | |

Fonte: [DFP NE 23 e 3.13]. A controladora registra R$453,4 mi, que o FRE apresenta como 93,9% do lucro [FRE 2.11].

**Índices (2025, consolidado) [ESTIMATIVA]**

| Índice | Cálculo | Resultado |
|---|---|---|
| Incentivo ÷ receita | 459,7 ÷ 4.460,4 | **10,3%** (2024: 10,8%) |
| Incentivo ÷ EBITDA | 459,7 ÷ 541,8 | **84,8%** (2024: 80,1%) |
| Incentivo ÷ EBIT | 459,7 ÷ 425,2 | **108,1%** → o EBIT sem incentivos seria **−34,5** |
| Incentivo ÷ lucro líquido | 459,7 ÷ 483,7 | **95,0%** (2024: 97,4%) |
| Margem bruta sem ICMS incentivado | (1.342,6 − 336,3) ÷ (4.460,4 − 336,3) | **24,4%** vs 30,1% reportada |

### 2.3 Carga tributária: Intelbras vs importador

| Rota | Tributos sobre o bem | IR/CSLL | Fonte |
|---|---|---|---|
| **Intelbras — Manaus (ZFM, Segurança)** | IPI isento; II reduzido sobre insumos (PPB); crédito estímulo de ICMS-AM (R$180 mi ≈ 4,0% da receita consolidada) | SUDAM (−75% de IRPJ sobre o lucro da exploração até 2033); incentivos fora da base → **alíquota efetiva consolidada de 0,74%** | DFP NE 23/24; FRE 1.6 |
| **Intelbras — SC/MG/PE (Lei de TICs)** | Crédito financeiro de R$123 mi (2,8% da receita) em troca de PD&I ≥4%. ICMS-SC com base reduzida (12% sobre a base integral) e crédito presumido para bens da Lei de Informática; MG com crédito presumido; PE até 2032 | Idem | DFP NE 23 |
| **Montador concorrente em Manaus** (Multilaser–Hikvision) | Mesmo regime ZFM | SUDAM, se aplicável | E3 |
| **Importador formal de produto acabado** (ex.: câmera CMOS, NCM 8525.89.13) | II de 14% pela TEC (pode haver Ex-tarifário a 0%) + IPI de 13% + PIS/COFINS-importação (11,75% na regra geral, creditáveis) + ICMS-importação (4% interestadual; benefícios estaduais podem reduzir) | **34% nominal** | E35 (fonte secundária; **validar na TIPI e na TEC oficiais**) |
| **Cross-border ≤US$50** (marketplaces) | II 0% (desde 13/05/2026) + ICMS de 17–20%. Sem IPI e sem PIS/COFINS na remessa | — | E15 |

**[DATA NEEDED]** Modelo de landed cost NCM por NCM, para as 10 principais categorias, comparando Intelbras-Manaus, Intelbras-SC, importador formal e cross-border. Sem ele, o diferencial tributário em R$ por unidade não pode ser afirmado.

### 2.4 Cenários: contábil vs econômico

**Diferença central.**
- **Efeito contábil:** quanto do resultado reportado desaparece com o benefício, supondo preços e concorrentes constantes.
- **Efeito econômico incremental:** quanto a Intelbras realmente perde depois que:
  - (i) os concorrentes reagem, porque também perderam benefício equivalente e repassam ao preço;
  - (ii) a Intelbras escolhe a melhor alternativa (importar o acabado, como os rivais);
  - (iii) deixam de existir os custos exigidos pelo incentivo (P&D obrigatório).

**Fórmulas**

> Perda contábil no lucro líquido = Incentivo perdido. Como os incentivos já estão fora da base de IR, a perda é integral.
>
> Perda econômica = Incentivo perdido × (1 − repasse) − custos vinculados evitados

| Cenário | Premissa | Incentivo perdido (base 2025) | EBITDA contábil (margem) | Lucro líquido contábil (Δ) | Lucro líquido com repasse de 50% | Lucro líquido com repasse de 75% |
|---|---|---|---|---|---|---|
| **BASE (até 2032)** | Lei de TICs renovada em 2029 (precedente: prorrogada em 2019); ICMS até 2032, com redução de 2029–32 compensada pelo Fundo; ZFM até 2073 | 0 | 541,8 (12,1%) | 483,7 (0%) | — | — |
| **PARCIALMENTE REDUZIDO (pós-2033 ou sem renovação)** | Perde Lei de TICs (123,3) e ICMS de SC/MG/PE (156,4). AM preservado pelo regime ZFM (IPI + créditos presumidos de IBS/CBS) | **279,7** | 262,1 (5,9%) | 204,0 (**−58%**) | 343,9 (−29%) | 413,8 (−14%) |
| **ELIMINADO / NÃO COMPENSADO** | Perde tudo, inclusive AM | **459,7** | 82,1 (1,8%) | 24,1 (**−95%**) | 253,9 (−48%) | 368,8 (−24%) |

**Caso econômico central do cenário PARCIAL [ESTIMATIVA + INFERÊNCIA]**
- **ICMS de SC/MG/PE.** Com a reforma, o ICMS acaba para todos, inclusive para os benefícios de importação dos rivais. O IBS tem alíquota uniforme no destino.
  - Repasse alto, de ~75%.
  - Perda: 156,4 × 25% = **39,1**.
- **Lei de TICs.** É específica de fabricantes locais. O importador nunca a teve.
  - Repasse baixo, de ~25%.
  - Líquida dos R$39,5 mi de P&D vinculado [FRE 2.11]: (123,3 − 39,5) × 75% = **62,9**.
- **Perda econômica total ≈ 102,0** → lucro líquido de ~381,7 (**−21%**) e EBITDA de ~439,8 (9,9% de margem).

**Risco à parte (tributação das subvenções).** A Lei 14.789/2023 restringiu a exclusão de subvenções da base de IR/CSLL. Em 2025 a Intelbras excluiu os R$459,7 mi integralmente [DFP NE 24].
- Se essa exclusão fosse contestada: 34% × 459,7 = **R$156,3 mi** (32% do lucro líquido).
- [INFERÊNCIA] A exclusão integral sugere apoio na tese do STJ de que crédito presumido de ICMS não é renda. **Verificar a contingência.**

**Erro comum.** Ler "incentivo = 95% do lucro" como "sem incentivo, o lucro cai 95%". Isso supõe três coisas que não acontecem ao mesmo tempo:
1. preços constantes;
2. concorrentes inalterados;
3. nenhuma mudança de estratégia (por exemplo, importar em vez de fabricar).

### 2.5 Os incentivos são margem extra ou estrutura para competir?

**Resposta: são majoritariamente estrutura para competir. Há uma parcela de margem incremental, concentrada em Manaus.**

| Evidência | Aponta para | Tipo |
|---|---|---|
| Mesmo com R$460 mi de incentivos, o ROIC pré-IR de 2025 foi 15,1%, igual à Selic. Sem eles, o EBIT seria negativo (−34,5) | **Estrutura para competir.** O preço de mercado é fixado por quem tem custo mais baixo (importador asiático ou montador incentivado). O incentivo só traz a Intelbras até a paridade | [ESTIMATIVA] |
| "O mercado define os preços" [FRE 2.2, p.71] | Intelbras tomadora de preço → o incentivo não vira preço mais alto | [DADO] |
| Concorrentes com acesso a regime equivalente: Multilaser/Hikvision na ZFM; importadores com benefícios estaduais de importação | Vantagem de **regime**, não de empresa. Diferencia contra importadores, não contra montadores locais | [DADO] E3 + [INFERÊNCIA] |
| Segurança tem ROIC estimado de ~28%, mas ~14,7% sem o ICMS-AM | **Margem incremental parcial em Manaus.** A escala da Intelbras na ZFM pode capturar mais do que montadores menores | [ESTIMATIVA] |
| Lei de TICs exige ≥4% do faturamento incentivado em PD&I; P&D de R$179 mi vs crédito de R$123 mi | Parte do crédito **paga um custo obrigatório**. Não é margem pura | [DADO] FRE 2.10; DFP NE 23 |
| Expansão de R$200 mi em Manaus [E38] | Migração para o **regime que sobrevive** à reforma | [INFERÊNCIA] |

### 2.6 Cadeia FATO → MECANISMO → IMPACTO → LINHA → TESE

| Fato | Mecanismo econômico | Impacto na Intelbras | Linha financeira | Consequência para a tese |
|---|---|---|---|---|
| Lei de TICs vence em 2029 | Crédito financeiro sobre PD&I | −R$123 mi brutos (−R$84 mi líquidos de P&D vinculado) se não for renovada | EBITDA (outras receitas), lucro líquido | Evento binário em 2029. O precedente de prorrogação existe, mas não está garantido |
| ICMS acaba em 2033; redução em 2029–32 compensada pelo Fundo | Benefício substituído por compensação até 2032 e, depois, IBS uniforme | −R$156 mi (SC/MG/PE) após 2032, com repasse alto porque os rivais também perdem | Receita líquida, margem bruta | Risco real, mas parcialmente neutro na competição |
| ZFM mantida (IPI + IBS/CBS) até 2073 | Diferencial preservado para quem fabrica em Manaus | Incentivo AM de R$180 mi tende a se manter. Capex de R$200 mi aprofunda a exposição | Margem de Segurança | **Ponto a favor subestimado:** a parcela mais valiosa é a mais durável |
| II zero no cross-border ≤US$50 | Importação direta mais barata que o varejo formal | Pressão sobre câmeras Wi-Fi e roteadores no varejo (16% das vendas) | Receita e margem do varejo | Negativo e localizado. Não atinge o canal profissional |
| Antidumping de fibra (até ~2030) | Eleva o preço de importação chinesa | Demanda por cabo nacional; Tubarão no limite | Receita e margem de TIC | Ganho temporário, limitado pela capacidade |

---

## 3. Competição

### 3.1 Mercado a mercado, produto a produto

**Segurança**

| Submercado | Intelbras | Concorrentes que disputam o mesmo produto (origem) | Canal típico | Presença industrial no Brasil | Leitura [INFERÊNCIA] |
|---|---|---|---|---|---|
| CFTV analógico (HDCVI) + DVR | Plataforma Dahua, montagem em Manaus e São José | Hikvision/HiLook (China; montagem CKD pela Multilaser em Manaus desde 2022 [E3]); Giga Security | Distribuidor → instalador | Ambos na ZFM | Categoria madura, em "contexto mais desafiador" [FRE p.24]. O preço é definido pela Hikvision e pela Dahua globais |
| CFTV IP para projetos, com VMS e IA | Dahua + Seventh; distribuidores InProject | Hikvision, Motorola Solutions [E30]; globais de projeto | Integradores | Importados | O comprador é técnico e multimarca. O canal pesa menos. A Intelbras diz ganhar presença [FRE p.24], **sem dado independente** |
| Câmeras Wi-Fi plug-and-play e fechaduras digitais | Linha própria | TP-Link, Xiaomi, Positivo [E30]; Imou (Dahua) via cross-border [E36] | Varejo e e-commerce | Importados | **Pior estrutura de Segurança:** comparação de preço direta, II zero no cross-border e dispensa do instalador |
| Controle de acesso (controladoras, catracas, facial) | Fábrica em Santa Rita do Sapucaí/MG | **Control iD** (fabricante brasileira de catracas e faciais [E39]); Hikvision | Instalador e integrador | Control iD e Intelbras locais | Competição de engenharia local. Share de 27% (2020) e 29% (c.2022) [BTG21; E30] |
| Alarmes de intrusão e incêndio | Linha própria (Engesul, 2013) | JFL (Brasil) [FRE p.26] | Instalador | Locais | Nicho com marcas locais e custo de troca do instalador (painéis, programação) |
| Automação de portões e comunicação condominial | Interfonia, vídeo-porteiro | PPA, Garen (Brasil) [FRE p.26]; Hikvision | Instalador | Locais | Mesmo comprador (instalador de condomínio). Favorece a cesta da Intelbras |

**TIC**

| Submercado | Intelbras | Concorrentes | Canal | Leitura |
|---|---|---|---|---|
| Roteadores Wi-Fi de varejo | Linha própria | **TP-Link** (21% dos roteadores na América Latina, pesquisa de 2020 [E28]), Multilaser | Varejo e e-commerce | Escala global; cross-border |
| Redes empresariais (switches, APs) | Linha própria, em expansão [Rel. p.8] | Cisco, Huawei, TP-Link [FRE p.26] | Integradores de TI | **Espaço real:** PME atendida pelo mesmo instalador. Concorrência forte no topo |
| GPON (OLT e ONU para provedores) | Fabricação em SJ; acordo FiberHome 2024–jan/2026 [E27] | Huawei [FRE]; FiberHome, livre desde jan/2026 [E27] | **Direto a provedores**, com crédito | Comprador técnico sensível a preço, com risco de crédito. A Intelbras optou por "maior controle de preços e crédito" [FRE p.25] |
| Cabos ópticos e UTP, cabeamento estruturado | Fábrica de Tubarão | Furukawa [FRE]; Prysmian e Lightera (autoras do pedido de antidumping) [E17] | Distribuidor e integrador | Melhor momento de TIC: antidumping + capacidade cheia |
| Telefonia corporativa e comunicação unificada | PABX (legado desde 1987), Khomp | Logitech, Motorola [FRE] | Integrador | Base instalada legada. Mercado migra para nuvem |
| CPE 5G / FWA | Com a Qualcomm, feito em SJ [E23] | Fabricantes globais de CPE | Operadoras | Nicho. Quem compra é a operadora |

**Energia**

| Submercado | Intelbras | Concorrentes | Canal | Leitura |
|---|---|---|---|---|
| Nobreaks | Linha própria | **SMS (Legrand), descrita como líder de UPS no Brasil** [E29]; TS Shara [FRE]; Schneider [FRE] | Distribuidor, varejo, TI | Mesmo canal de Segurança. A Intelbras é desafiante, não líder |
| Fontes, baterias, proteção | Linha própria | Schneider, WEG [FRE] | Distribuidor | Complemento da obra |
| Carregadores de veículo elétrico | AC e DC | WEG, Schneider [FRE] | Instalador e condomínio | 613 mil eletrificados (+64%) [FRE p.26]. Mercado pequeno, crescendo rápido |
| Solar on e off-grid (kits) | Renovigi; share de 1,9% | Distribuidores de kits e fabricantes globais de módulos e inversores [DATA NEEDED: nomes e shares] | **Integrador solar (canal próprio)** | Commodity global. A Intelbras não tem escala nem canal diferenciado |

### 3.2 Escala global: onde a Intelbras é pequena

| Empresa | Receita 2025 | Lucro líquido | Escala vs Intelbras | Fonte |
|---|---|---|---|---|
| Hikvision | RMB 92,51 bi (US$12,95 bi), +0,01% | RMB 14,20 bi (+18,5%) | **16,2x**; só o exterior (US$3,81 bi) = **4,8x** | E1 |
| Dahua | RMB 32,29 bi (≈US$4,5 bi) [ESTIMATIVA, câmbio ~7,18] | n.d. | **~5,6x** | E2 |
| Intelbras | R$4.460 mi (≈US$0,80 bi à PTAX média de 5,58) | R$483,7 mi | 1x | DFP; E11 |

[INFERÊNCIA] Em P&D de núcleo, compras de chips e escala industrial, a Intelbras perde por uma ordem de grandeza. Só pode vencer onde a escala relevante é **local**:
- canal;
- treinamento;
- assistência;
- regime fiscal;
- disponibilidade de estoque.

### 3.3 Market share: crítica ao MIDI

**Como o MIDI funciona [FRE 1.4.c, p.23–24]**
- Ferramenta paga sobre a base Comex Stat;
- algoritmos de IA cruzam "mais de 300 fontes";
- o resultado é share em **R$**, calculado só para a controladora.

| Mercado | Share Intelbras | #2 | #3 | Fonte | Métrica | Limitação |
|---|---|---|---|---|---|---|
| Segurança (BU) | 44% (2025); 43% (2024) | Hikvision [share: DATA NEEDED] | Por nicho: Control iD (acesso), JFL (alarme), PPA e Garen (portões) [DATA NEEDED] | FRE 1.4 | R$, importações (proxy de sell-in), controladora | Não auditado. Produção CKD em Manaus de rivais pode ser mal atribuída à marca. Não mede sell-out. Sem desvio-padrão |
| CFTV (2020) | 43%; mercado R$2,2 bi | — | — | BTG21 s.11 | R$ | Definição diferente da BU |
| CFTV (c.2022) | 54% | — | — | E30 (citando a companhia) | R$ | Não reconciliável com 43% (2024) da BU |
| Controle de acesso | 27% (2020); 29% (c.2022) | Control iD [DATA NEEDED] | Hikvision | BTG21; E30 | R$ | Não divulgado separadamente depois |
| TIC (BU) | 9% (2025 e 2024) | Huawei, TP-Link, Cisco [DATA NEEDED] | Furukawa | FRE | R$ | **Universo ampliado:** em 2020, redes (25%) + comunicação (18%) somavam R$3,3 bi |
| Roteadores (América Latina) | n.d. | **TP-Link 21%** (#1) | — | E28 (2020) | Pesquisa regional | Antiga e regional |
| Energia sem solar | 19% (2025 e 2024) | SMS/Legrand ("líder") [E29] | TS Shara | FRE; E29 | R$ | "Power" era 10% em 2020, em outra base |
| Solar | 1,9% (2025); 2,1% (2020) | [DATA NEEDED] | — | FRE; BTG21 | R$ | Mercado inclui módulos e inversores. A Intelbras vende kits |

**Share histórico reconstruído [ESTIMATIVA]**

| | 2020 | c.2022 | 2024 | 2025 | Leitura |
|---|---|---|---|---|---|
| Segurança (BU, comparável) | ~34%¹ | n.d. | 43% | 44% | **Se as bases forem comparáveis**, houve ganho de ~10 p.p. em 2020–24, seguido de estabilidade |
| CFTV isolado | 43% | 54% | n.d. | n.d. | Ganho entre 2020 e 2022. Depois, não divulgado |
| TIC | ~23%¹ | n.d. | 9% | 9% | A "queda" é mudança de universo |

¹ Receita do segmento ÷ (soma dos mercados do BTG21 em R$). Segurança: 1.148 ÷ 3.400 ≈ 34%. TIC: 771 ÷ 3.300 ≈ 23%.

**Classificação**
- **Segurança:** "share alto e estável" é **comprovado** no curto prazo (2024–25). "Share estruturalmente crescente" é **não comprovado**.
- **TIC:** share baixo e estável num universo amplo.
- **Energia sem solar:** estável.

**Share × resultado**
- Em 2025, a estabilidade de share em Segurança veio com **queda de margem bruta** (34,8% → 33,2%).
- [INFERÊNCIA] O share foi defendido com preço. A liderança não é sinônimo de pricing power.

### 3.4 Testes de vantagem competitiva (framework de "Como Analisar Empresas")

| Vantagem alegada | Fonte (apêndice) | Evidência a favor | Evidência contra | Classificação |
|---|---|---|---|---|
| Escala de canal, treinamento e marca (custo fixo nacional) | Escala | 370 mil qualificações; 500 pontos; 98% dos municípios [FRE] | SG&A não dilui: 20,3% → 17,4% → 19,3% [Planilha] | **MODERADA** contra entrantes regionais; **FRACA** contra globais |
| Escala industrial e de compras | Escala / custo | SMD de 450 mi de componentes por mês [FRE p.20] | Imobilizado ~15% da receita; Hikvision 16x; "poucas opções" de chipset [FRE p.31] | **FRACA** |
| Escala de P&D | Escala | R$179 mi (~4% da receita) [FRE 2.10] | Parte é obrigatória (Lei de TICs); tecnologia de núcleo vem da Dahua e da Qualcomm | **FRACA** |
| Fidelidade do instalador (Itec, níveis, Pontua) | Captividade | Share de 43–44% estável; 90 mil ativos | Integradores multimarca; FRE admite migração [p.97]; Pontua é replicável | **MODERADA** em Segurança; **FRACA** em TIC e Energia |
| Exclusividade do distribuidor (Mais Verde) | Captividade | 95% de adesão [FRE p.7] | Voluntária, paga (2–9%), reversível | **MODERADA**, durável enquanto as condições forem superiores às dos rivais |
| Custo de troca do usuário final (software, apps) | Captividade | ~R$140 mi de receita recorrente [FRE 1.2] | ~3% da receita; plug-and-play; cross-border | **FRACA** |
| Marca | Captividade | 71% de reconhecimento; NPS 71 [FRE p.11, dados da companhia] | Sem prêmio de preço mensurado | **NÃO COMPROVADA** como pricing power |
| Vantagem fiscal de produção local | Custo | R$460 mi; alíquota efetiva de 0,74% | Compartilhada (Multilaser/Hikvision na ZFM); prazos legais; ROIC ≈ Selic | **MODERADA e temporária**; mais durável em Manaus |
| Sourcing via Dahua | Custo / barganha | Plataforma líder global; 225 dias de prazo | ~40% do CPV de Segurança; contrato até 2028; poder do fornecedor | **FRACA como vantagem**; é risco |
| Disponibilidade local (estoque de 173 dias) | Serviço / captividade | Instalador compra à pronta-entrega | Custa capital: ciclo de caixa de 145 dias | **MODERADA** |

**Os três testes de evidência do apêndice**

| Teste | Segurança | TIC | Energia |
|---|---|---|---|
| Share alto e estável | ✔ 43–44% | ✘ 9% | ~ 19% sem solar; 1,9% em solar |
| Retorno acima do custo de capital | ✔ ~28% (estimativa), mas ~14,7% sem o ICMS-AM | ✘ ~7,5% | ✘ ~6% |
| Retenção e fidelidade | NÃO COMPROVADA (sem churn divulgado) | NÃO COMPROVADA | NÃO COMPROVADA |

### 3.5 O canal de distribuição

**Os programas e sua função econômica [FRE 1.2, p.6–9; 1.4, p.22]**

| Programa | O que a Intelbras dá | O que exige | Mecanismo econômico [INFERÊNCIA] | Replicável? |
|---|---|---|---|---|
| **PCI** para distribuidores | Marketing cooperativo, BI, leads, descontos, **rotação de estoque ocioso**, **proteção de preços** | Metas quadrimestrais de sell-in; **reportar estoque e sell-out**; seguir a política de preço; não vender ao consumidor | Troca disciplina de preço e dados de sell-out pela absorção do risco de estoque do canal | Exige portfólio amplo e balanço forte |
| **PCI** para revendas (Ouro, Prata, Bronze, Registrado) | Descontos, treinamento exclusivo, **suporte a registro de projeto** e consultoria técnica | Metas quadrimestrais; ≥2 profissionais treinados; presença online; reportar sell-out | O registro de projeto protege a revenda que gerou a oportunidade e evita leilão de preço entre revendas | Sim (prática comum de fabricantes) |
| **Mais Verde** | 2–9% de desconto; prioridade em marketing, lançamentos e recebimento | Exclusividade voluntária nas linhas | A Intelbras compra espaço de prateleira | Sim, para quem tiver caixa |
| **Intelbras Pontua** | Pontos trocados por combustível, contas, plotagem | Comprar em distribuidor autorizado | Fidelidade comprada; leva a compra ao canal formal | Sim |
| **Itec / UNI** | 370 mil qualificações em 2025; mais de 1.000 cursos; gestão para canais | — | Custo de aprendizado → custo de troca | **Lento:** acumulado em décadas |
| **Assistência técnica** | Rede credenciada nacional, troca expressa [FRE p.9] | — | Reduz o risco do instalador perante o cliente | Médio |
| **Proteção de preços** | Compensa o canal quando o preço cai | — | Transfere ao balanço da Intelbras o risco de deflação tecnológica | Sim, com balanço |
| Sell-in / sell-out | — | Reporte obrigatório | "Relação estável" [Rel. p.6] → menor risco de empurrar estoque | — |

**Por que um instalador venderia Intelbras e não Hikvision, TP-Link ou Huawei?**

| Fator | Intelbras | Hikvision | TP-Link | Huawei | Peso no residencial e PME [INFERÊNCIA] |
|---|---|---|---|---|---|
| Disponibilidade e giro | ~500 pontos; estoque de 173 dias | Distribuidores + Multilaser | Varejo e e-commerce | Projetos e provedores | **Alto** |
| Margem do revendedor | [DATA NEEDED] | [DATA NEEDED] | [DATA NEEDED] | [DATA NEEDED] | Alto, mas **não medido** |
| Suporte e treinamento em PT-BR | Itec; 1,9 mi de atendimentos por WhatsApp [FRE p.8] | [DATA NEEDED] | Baixo no canal profissional | Forte em grandes contas | **Alto** |
| Garantia e assistência | Rede nacional, troca expressa | [DATA NEEDED] | Varejo | Contrato | Médio-alto |
| Confiança na marca (cliente final) | 71% de reconhecimento (companhia) | Forte entre técnicos | Forte no varejo | Forte em telecom | Médio |
| Cesta única (CFTV + acesso + rede + nobreak) | ✔ | CFTV + acesso | Rede | Rede e telecom | **Alto em condomínios e PMEs** |
| Crédito | Via distribuidor | Via distribuidor | Varejo | Direto | Médio |
| Leads | A marca gera leads e repassa ao canal [FRE p.8] | [DATA NEEDED] | — | — | Médio |
| Proteção comercial | Registro de projeto | [DATA NEEDED] | — | Programas de parceiros | Médio |
| Preço unitário | [DATA NEEDED] | Referência global | Referência global | Referência global | Alto em projetos e varejo |

**Conclusão [INFERÊNCIA].** O instalador não escolhe pelo preço da câmera. Escolhe pelo **custo total de fazer o serviço**: achar o produto, saber instalar, ter suporte e não voltar ao cliente por defeito.
- **Funciona em Segurança residencial e PME**, onde o instalador especifica.
- **Funciona menos em projetos e GPON**, onde a engenharia compara especificação e preço.
- **Funciona menos no varejo**, onde o consumidor compara.

**"90 mil revendedores: vantagem ou consequência do share?" Ambos.**
- [ESTIMATIVA] Receita por revendedor:
  - 2020: R$2.134 mi × 77% ÷ 80 mil ≈ **R$20,5 mil/ano**;
  - 2025: R$4.460 mi × 68% ÷ 90 mil ≈ **R$33,7 mil/ano**.
- A base cresceu 12,5%; a receita, 109%. A rede **amadureceu**.
- O ativo é a profundidade da relação, não o número de revendedores.

**Teste do flywheel**

| Elo | Status | Evidência |
|---|---|---|
| Fidelização → maior sell-out | Parcial | Relação sell-in/sell-out estável [Rel. p.6] |
| → Maior giro do distribuidor | **Não evidenciado** | Estoque da própria Intelbras subiu: 144–217 dias [Planilha] |
| → Preferência e capilaridade | Evidenciado | 95% no Mais Verde; pontos 370 → 500 |
| → Mais vendas | Parcial | Só em Segurança (+18% a.a. em 2019–25) |
| → Maior escala → melhores condições | **Contradito** | ROIC 31% → 15%; SG&A sem diluição; margem bruta de Segurança ~39% (2020) → 33% |

**Veredito.** O **loop curto** gira:

> treinamento → especificação → disponibilidade → volume em Segurança

O **loop longo** não aparece nos números:

> escala → custo menor → condições melhores

O canal é **moat defensivo** (protege share e margem bruta), não motor de expansão de margem.

### 3.6 Dahua: aumenta o moat ou cria dependência?

| Dimensão | Fato | Fonte |
|---|---|---|
| Acordo | Cooperação de 31/12/2018, por 10 anos, renovável. Intelbras compra CFTV (câmeras e gravadores) **exclusivamente/prioritariamente** da Dahua. Dahua dá à Intelbras exclusividade dos "Produtos Dahua" no Brasil, mais 6 meses após o fim | FRE 1.2, 11.3; DFP NE 32 |
| Saídas | Intelbras pode comprar de outro se o preço for ≥5% maior, se houver falha técnica ou falência. Se a Dahua rescindir, a Intelbras compra por mais 3 anos | FRE 11.3 |
| Custo | Compras de R$729 mi (2025) e R$1.187 mi (2024); 36% dos gastos com fornecedores; [ESTIMATIVA] ~40% do CPV de Segurança | DFP NE 32; FRE 1.4.e |
| Financiamento | Saldo de R$449 mi = 43% do passivo com fornecedores. [ESTIMATIVA] Prazo implícito: 156 dias (2024) → **225 dias** (2025) | DFP NE 31/32 |
| Sensibilidade | [ESTIMATIVA] Se o prazo cair para 90 dias: +R$269 mi de capital → ROIC pré-IR LTM de 18,8% → **17,1%** | Cálculo |
| Societário | 7,56% do capital; um conselheiro, que administra a Dahua Technology Brasil; venda autorizada em até 36 meses (ago/2025) | FRE 7.3; E37 |
| Precedente | FiberHome (GPON): exclusividade iniciada em jan/2024 e encerrada em 12/01/2026. "Ambas poderão atuar com outros parceiros" | E27 |
| Entrada direta | A Hikvision entrou com montador local em meses, com R$6 mi de investimento [E3]. A Imou (Dahua) já chega via cross-border [E36] | E3, E36 |

**Resposta [INFERÊNCIA]**
- **No curto prazo, aumenta o moat:**
  - dá acesso à tecnologia de um líder global sem P&D de núcleo;
  - financia ~7 meses de compras;
  - a exclusividade de marca impede a Dahua de disputar o mesmo canal.
- **No médio prazo, cria dependência estratégica maior que o moat que adiciona:**
  1. ~40% do CPV do segmento que gera 68% do lucro bruto está em um único contrato que vence em 2028;
  2. o acionista-fornecedor está saindo do capital;
  3. o precedente da FiberHome mostra que exclusividades de parceiros chineses terminam;
  4. o canal da Intelbras é exatamente o ativo que a Dahua precisaria para entrar sozinha. Isso dá à Dahua poder de barganha na renovação.

**Classificação: dependência > moat.**

---

## 4. Fatores macroeconômicos: canais de transmissão

| Variável | Leitura atual | Canal de transmissão | BU mais sensível | Linha | Sensibilidade [INFERÊNCIA] | Evidência |
|---|---|---|---|---|---|---|
| **Selic** | 13,75% (16/09/2026); cortes de 0,25 p.p. desde abr/2026, a partir de 14,75% [E10] | Crédito → duráveis, obras, capex de PMEs, financiamento solar, capital de giro de provedores | Solar > TIC (provedores e PMEs) > Segurança | Volume, provisão para perda de crédito (PCLD), custo de carregar estoque | Alta / média / baixa-média | FRE p.26 ("segmentos dependentes de financiamento"); PCLD de R$7,1 → 28,8 mi [Planilha] |
| **Renda real** | PIB per capita +1,9% (2025); mercado de trabalho "aquecido" | Consumo residencial; upgrade de Wi-Fi e câmeras | Varejo (16% das vendas) | Volume | Média | FRE p.27; E10 |
| **Construção civil** | Lançamentos +30,1% (2025); 86% MCMV | Obra → instalação no fim (24–36 meses depois do lançamento) | Segurança (acesso, interfonia, CFTV), TIC (cabeamento), Energia (nobreak, VE) | Volume em 2027–28 | Média, defasada | E8 |
| **Capex empresarial** | Copom vê "moderação gradual da atividade" | Projetos de rede, CFTV IP, telefonia | TIC empresarial; projetos de Segurança | Volume e mix | Média | E10; Rel. p.6 ("vendas impactadas pelo cenário") |
| **USD/BRL** | R$5,16 (jun/26; −5,9% no ano); média de 2025 R$5,58 vs 5,39 em 2024 | 80% do CPV em USD → custo de reposição → preço | Todas; maior em Energia solar | Margem bruta | **Alta** | DFP NE 25; E11, E12 |
| **Capex de telecom** | Banda larga +2,7% (2025); fibra 79%; PPPs 63% | Provedores compram GPON e cabos | TIC | Volume e crédito | Alta, mas em desaceleração | E25, E26 |
| **Investimento solar** | Adições −29%; investimento −40% (2025); Fio B 60% | Payback ↑ → demanda ↓ | Energia solar | Volume e preço | Alta | E20, E21 |

### 4.1 Os drivers que você sugeriu: teste

**Driver de Segurança 1 — insegurança no Brasil → veredito: MODERADO (sustenta, não acelera; depende da percepção)**
- **Fato.**
  - [DADO] O crime cai: MVI −8,2% em 2025 (19,1 por 100 mil, −31% desde 2012); homicídios −10%; roubos e furtos de celular −7,7% [E4].
  - [DADO] A percepção sobe: segurança como maior problema em 17% (out/24) → 38% (nov/25) → 30% (jun/26) [E5, E6].
- **Mecanismo.** A compra de segurança eletrônica é decidida por três coisas:
  - (i) risco **percebido** (disposição a pagar);
  - (ii) queda do preço por câmera (deflação tecnológica);
  - (iii) substituição de mão de obra: a portaria remota reduz de 15% a 50% a taxa condominial [E9].
- **Impacto.** Mesmo com a percepção no pico, a receita de Segurança cresceu só 4,9% em 2025 e 5,8% no 1S26. A companhia descreve o mercado como de "evolução moderada" [FRE p.24].
- **Linha.** Receita de Segurança, sobretudo residencial e condomínios.
- **Tese.** Não usar insegurança como acelerador no modelo. É piso de demanda. Se a percepção convergir para o crime medido, em queda, a compra residencial discricionária perde força.

**Driver de Segurança 2 — construção de casas e condomínios → veredito: MODERADO-FORTE, mas com defasagem; o retrofit pesa mais**
- **Fato.**
  - [DADO] Lançamentos +30,1% em unidades em 2025. De jan–out: 161.709 unidades, 85,9% MCMV; médio e alto padrão +14,3% [E8].
  - [DADO] 13,3 mi de unidades em condomínio; mais de 14 mil condomínios com portaria remota; o serviço cresceu 24% em 2024 [E7, E9].
- **Mecanismo.** Cada condomínio novo instala controle de acesso, interfonia/vídeo-porteiro, CFTV nas áreas comuns, cabeamento e nobreak. Isso acontece **no fim da obra**, 24–36 meses após o lançamento [INFERÊNCIA].
  - MCMV tem conteúdo por unidade menor que médio e alto padrão.
  - O estoque de 13,3 mi de unidades gera **retrofit** (portaria remota, reconhecimento facial), menos dependente de juros.
- **Impacto.** Lançamentos recordes de 2025 → demanda em 2027–28. Juros em queda ajudam o médio e alto padrão.
- **Linha.** Receita de Segurança (acesso e comunicação condominial), TIC (cabeamento) e Energia (nobreak, carregadores de VE).
- **Tese.** O melhor driver de volume para Segurança. **[DATA NEEDED]** Conteúdo em R$ por unidade, por padrão, para converter unidades em receita.

**Driver de TIC — 5G → veredito: FRACO como driver direto; levemente positivo via fibra e cabos**
- **Fato.** [DADO]
  - 80% da população coberta até o fim de 2026 [E22];
  - Intelbras e Qualcomm fabricam CPE 5G em SJ desde 2S22 [E23];
  - em 2023, a Intelbras esperava que o FWA chegasse a "até 20% da banda larga" [E24], mas a fibra tem ~79% [E25].
- **Mecanismo.**
  - (i) Quem compra CPE é a operadora, comparando com fabricantes globais.
  - (ii) O FWA **substitui parcialmente a fibra** dos provedores pequenos, que são os clientes de GPON da Intelbras.
  - (iii) O 5G exige backhaul de fibra, o que favorece cabos e Tubarão [INFERÊNCIA].
- **Impacto.** Não mensurável: receita de 5G não divulgada [DATA NEEDED].
- **Tese.** Não modelar 5G como alavanca de TIC. É opção pequena. O efeito líquido sobre GPON pode ser negativo.

### 4.2 Cadeia FATO → MECANISMO → IMPACTO → LINHA → TESE (macro)

| Fato | Mecanismo | Impacto | Linha | Tese |
|---|---|---|---|---|
| Selic 13,75% em queda gradual | Crédito ao consumo e às PMEs; custo de carregar estoque | Recuperação lenta em TIC empresarial e Energia sem solar; solar segue fraco com o Fio B | Receita, PCLD, resultado financeiro | Sensibilidade a juros: Energia > TIC > Segurança |
| Lançamentos recordes em 2025 | Instalação no fim da obra | Demanda em 2027–28 | Receita de Segurança e TIC | Driver defasado positivo |
| Banda larga +2,7% | Provedores com menos capex | GPON em queda (estratégia de redução da Intelbras) | Receita de TIC | GPON deixa de ser vetor |

---

## 5. Dinâmica de preços

### 5.1 Quem define o preço?

| Agente | Papel na formação do preço | Evidência |
|---|---|---|
| Fabricantes globais (Hikvision, Dahua, TP-Link, Huawei) | **Definem o preço FOB** (preço na origem) da tecnologia. Ele cai com a deflação tecnológica | "A evolução tecnológica pressiona os preços para baixo" [FRE 2.2, p.71]; Hikvision 16x |
| Câmbio | Converte o FOB em reais. 80% do CPV | FRE 2.2; DFP NE 25 |
| Componentes (memória, chips) | Choques globais de custo. Em 2026, a crise de DRAM e NAND causada pela demanda de IA [E34] | Rel. p.7: "elevação dos custos dos materiais… commodities" |
| Intelbras | Define o preço local **dentro de uma faixa**. Reajusta "quando julgamos necessário, observando… as diferentes dinâmicas de mercado" [Rel. p.2] | "O mercado define os preços" [FRE p.71] |
| Distribuidores | Seguem a política de preço do PCI. Absorvem parte via desconto Mais Verde | FRE p.7 |
| Cross-border | Teto de preço no varejo para produto simples | E15 |

**Resposta [INFERÊNCIA].** O nível de preço é definido pela **paridade de importação**: FOB global × câmbio × tributos. A Intelbras decide o **momento** do repasse e um pequeno prêmio de serviço ou marca, que não está medido.

### 5.2 Landed cost e defasagens

**Landed cost** é o custo do produto posto no Brasil: preço na origem + frete + tributos de importação.

**Cadeia do landed cost**

| Componente | Moeda | Comentário |
|---|---|---|
| FOB (produto acabado Dahua ou ODM asiático, ou placas, chipsets, memória, PCB, ABS) | USD | Chipsets com "poucas opções" [FRE p.31]; memória em alta em 2026 [E34] |
| + Frete internacional e seguro | USD | [DATA NEEDED] |
| + II | — | Câmera CMOS: 14% pela TEC (ou Ex 0%). Insumos com PPB na ZFM: redução |
| + IPI | — | Isento na ZFM; câmera: 13% fora [E35] |
| + PIS/COFINS-importação | — | Creditáveis no regime não cumulativo |
| + ICMS-importação | — | Benefícios estaduais [DFP NE 23] |
| **= Landed cost** | | |
| → Estoque a **custo médio** | | **173 dias** de CPV; importações em andamento de R$318 mi (~37 dias) [DFP NE 8] |
| → **Preço Intelbras** a **custo de reposição** | | Reajuste "quando necessário" |
| → Preço do distribuidor | | Desconto Mais Verde de 2–9%; margem do distribuidor [DATA NEEDED] |
| → Preço do revendedor ou instalador | | Inclui mão de obra; margem [DATA NEEDED] |
| → Preço ao consumidor | | No varejo, comparado ao cross-border |

**As defasagens [INFERÊNCIA a partir de DFP NE 8 e 25 e do Release]**
1. **Dólar sobe hoje.** O estoque antigo, comprado a câmbio menor, protege o CPV por ~2 trimestres.
2. **Se a Intelbras reajusta a custo de reposição** (preço sobe já, CPV sobe depois), a margem **sobe temporariamente**. Foi o 2T26: +2,4 p.p. sobre o trimestre anterior [Rel. p.3].
3. **Se a concorrência impede o reajuste**, a margem **cai** quando o estoque caro chega ao CPV. Foi 2024: 33,9% → 29,0%.
4. **Dólar cai.** O preço de reposição cai antes do custo médio, e a margem é comprimida (2025).
5. **NDF** (contrato a termo sem entrega física, usado como hedge): prazo médio de 90 dias e cobertura de ~50% dos fornecedores em USD [DFP NE 25]. Amortece o caixa, não a margem.

### 5.3 USD/BRL × margem bruta: o histórico

| Período | Margem bruta | Dólar (fim de período) | O que aconteceu |
|---|---|---|---|
| 1T23–3T23 | 31,6% / 34,4% / 32,4% | Dez/23 ≈ 4,84 [ESTIMATIVA: 6,19 ÷ 1,279] | Normalização após 2022 (pico de solar com margem baixa) |
| 4T23 | 26,9% reportada (29,5% ajustada) | — | Ajustes não recorrentes |
| 1T24 → 4T24 | 33,9% → 31,5% → 29,3% → 29,0% | Dez/24 = 6,19 (+27,9% no ano) | Dólar sobe → repasse incompleto → **−4,9 p.p.** |
| 1T25 → 4T25 | 29,4% → 29,3% → 30,9% → 30,7% | Mar/25 = 5,74; Dez/25 ≈ 5,50 (−11,1%) | Dólar cai → o preço acompanha → sem expansão |
| 1T26 → 2T26 | 30,7% → **33,1%** | Jun/26 = 5,16 (−5,9%) | **Dólar cai e a margem sobe:** custo de componentes em USD subiu (memória) → reprecificação a custo de reposição |

Fontes: [Planilha]; E11, E12. Dólar de jun/25 ≈ 5,47 [ESTIMATIVA].

**Leitura [INFERÊNCIA].** A correlação simples dólar × margem é **fraca e de sinal instável**. O que explica a margem é a seguinte relação:

> Margem bruta ≈ f( custo de reposição − custo médio do estoque ) × grau de repasse

O custo de reposição depende do **câmbio e do preço dos componentes em dólar**. Em 2026, o choque de componentes dominou o câmbio.

**Erro comum.** Concluir que "dólar caindo = margem subindo". No 1S26 o dólar caiu e a margem subiu por outro motivo (componentes). A margem tende a voltar quando o estoque novo, mais caro, chegar ao CPV. A companhia diz isso no release.

### 5.4 Sensibilidade [ESTIMATIVA]

**Fórmula**

> ΔMargem bruta ≈ −(% do CPV em USD) × Δcâmbio × (CPV ÷ Receita) × (1 − repasse)

**Passo a passo para +10% no dólar**
- Δmargem = −0,80 × 10% × 69,9% × (1 − repasse) = **−5,6 p.p. × (1 − repasse)**.
- Em R$: 0,80 × 3.117,8 × 10% = **+R$249 mi de CPV**.
- Reajuste necessário para manter a margem em %: **+8%** (= 0,8 × 10%).
- Cada 1 p.p. de margem bruta ≈ **R$45 mi** de EBITDA.

**Efeito financeiro (balanço).** ±10% no dólar = **∓R$26 mi** [DFP NE 25].
- Pequeno porque o hedge cobre ~50% da posição.

**Conclusão.** A exposição cambial está **no custo, não na receita** (as vendas são quase todas no Brasil). Por isso o pricing power é a variável crítica da margem. E o pricing power é limitado à velocidade do repasse.

### 5.5 Cadeia FATO → MECANISMO → IMPACTO → LINHA → TESE (preços)

| Fato | Mecanismo | Impacto | Linha | Tese |
|---|---|---|---|---|
| 80% do CPV em USD; 173 dias de estoque | Custo médio defasado vs preço a reposição | Margem oscila ±2–5 p.p. | Margem bruta | Modelar margem normalizada (~30–31%), não a do pico |
| Crise de memória em 2026 [E34] | Custo global sobe para todos → reajuste setorial | Ganho temporário no 2T26 (33,1%) | Margem bruta | Reverte em 2–3 trimestres, segundo a companhia |
| "O mercado define os preços" | Paridade de importação | A Intelbras não fixa o nível de preço | Margem bruta | Liderança ≠ pricing power |

---

## 6. Supply chain

| Elemento | Dado | Fonte | Relação com margem e capital de giro [INFERÊNCIA] |
|---|---|---|---|
| Polos próprios | São José/SC (todas as BUs); Manaus/AM (Segurança; expansão de R$200 mi); Santa Rita do Sapucaí/MG (acesso); Tubarão/SC (cabos, perto da capacidade) | FRE 1.4.a; Rel. p.8; E38 | O mapa fabril segue o mapa fiscal. Manaus cresce porque o regime sobrevive |
| Ásia | Fornecedores na China, Coreia e Vietnã para "complementação de portfólio" | FRE p.19 | Produto acabado importado → exposição direta a câmbio e frete |
| Concentração | Dahua com 36% dos gastos com fornecedores; FiberHome sem exclusividade desde 2026 | FRE 1.4.e; E27 | Poder de barganha do fornecedor ↑ |
| Semicondutores | "Poucas opções" de chipset; troca pode suspender operações | FRE p.31 | Risco de ruptura > risco de preço |
| Memória (2026) | Escassez de DRAM e NAND; preços de DRAM +80% a +170% (relatos); capacidade direcionada a IA; compradores pequenos expostos | E34 | Margem com volatilidade; compradores pequenos (como a Intelbras) ficam no fim da fila |
| Estoques | 1.474 (2025): acabados 733; matéria-prima 428; importações em andamento 318; provisão de obsolescência 73 (2024: 47) | DFP NE 8 | Estoque estratégico = proteção de disponibilidade, mas custa capital e gera obsolescência |
| Financiamento de fornecedores | Fornecedores + risco sacado (antecipação a fornecedores via banco) = R$1.049 mi; Dahua = 43% | DFP NE 31/32 | Risco de "funding" se as condições mudarem |
| Geopolítica | Disputas EUA–China entre os 5 maiores riscos; Dahua sob restrições nos EUA | FRE 4.2, p.119 | Restrição a chips norte-americanos para fornecedores chineses pode afetar o portfólio CFTV |
| Lead time | [DATA NEEDED] | — | Define o tamanho do estoque de segurança |
| % importado | ~80% do CPV atrelado a moeda estrangeira; "em sua maioria importados" | FRE 2.2; p.20 | O conteúdo nacional é montagem, não componente |

---

## 7. Mini-teses por BU

### Segurança

> **MERCADO** ~R$6,2 bi implícitos pelo MIDI [ESTIMATIVA]; crescimento estimado de +2,5% em 2025; a Abese (R$14 bi, +16,1%) inclui serviços
> ↓
> **DRIVERS** Retrofit de condomínios (13,3 mi de unidades; portaria remota +24%) > obras defasadas (lançamentos +30%) > percepção de risco (cíclica) > migração analógico → IP/IA
> ↓
> **POSIÇÃO** 44% de share (estável); liderança no canal instalador
> ↓
> **VANTAGEM** Canal (MODERADA), Manaus (MODERADA e durável), cesta para condomínios.
> **DESVANTAGEM** Tecnologia de terceiros (Dahua ~40% do CPV); plug-and-play exposto ao cross-border
> ↓
> **IMPACTO** 68% do lucro bruto; lucro bruto/capital de 67%; ROIC ~28% (~14,7% sem o ICMS-AM)

**Estrutural, ganho de share ou ambos?**
- **2024–25: crescimento de mercado** (share 43 → 44%).
- **2020–24:** possível ganho de share, mas não comprovável com o MIDI.
- **Daqui em diante:** crescimento ≈ mercado, de um dígito médio nominal [INFERÊNCIA].

### TIC

> **MERCADO** ~R$10,9 bi implícitos (universo amplo); "sem expansão relevante" [FRE p.25]; banda larga +2,7%
> ↓
> **DRIVERS** Redes empresariais de PMEs; cabeamento (antidumping); 5G fraco
> ↓
> **POSIÇÃO** 9% de share
> ↓
> **DESVANTAGEM** Rivais com escala global e silício próprio; compradores técnicos multimarca; GPON com risco de crédito e sem a exclusividade FiberHome.
> **VANTAGEM** Canal de PMEs, cabos nacionais
> ↓
> **IMPACTO** Margem bruta de 25,7%; ROIC ~7,5% (< Selic)

**Por que o share é menor que em Segurança [INFERÊNCIA]**
1. O instalador de Segurança não é quem especifica redes de provedores ou corporativas.
2. A Intelbras não tem parceiro tecnológico com exclusividade equivalente à da Dahua (a da FiberHome acabou).
3. O universo do MIDI inclui segmentos dominados por Huawei e Cisco.

**Espaço real de ganho**
- **Cabeamento estruturado:** antidumping até ~2030; limitado pela capacidade de Tubarão.
- **Redes empresariais de PMEs:** mesmo canal, cresce "de forma constante" [Rel. p.8].

### Energia sem solar

> **MERCADO** Nobreaks, fontes, baterias e carregadores de VE; share de 19% (estável)
> ↓
> **DRIVERS** Obras e escritórios (nobreak); eletrificação (613 mil VEs, +64%)
> ↓
> **POSIÇÃO** Desafiante; SMS/Legrand é a líder
> ↓
> **VANTAGEM** Mesmo canal e cliente de Segurança.
> **DESVANTAGEM** Líder estabelecido com rede própria
> ↓
> **IMPACTO** Margem da BU sobe com a saída de solar (2T26: lucro bruto +12% com receita −13,5%) [Rel. p.8]

### Solar (separado)

> **MERCADO** Adições −29% (15 → 10,6 GW); investimento −40% (R$54,9 → 32,9 bi); Fio B de 60% (2026) a 90% (2028); II sobre módulos ↑; restrições de conexão na rede [E21]
> ↓
> **POSIÇÃO** 1,9% de share (2,1% em 2020); canal próprio (integradores, Renovigi)
> ↓
> **DESVANTAGEM** Commodity global sem diferenciação, sem escala e fora do canal instalador
> ↓
> **IMPACTO** Explica a maior parte da queda de 31% de Energia em 2025

**Problema setorial ou de execução?** Os dois.
- **Setorial:** queda de volume e de preço por watt. [ESTIMATIVA] R$3,66 bi/GW → R$3,10 bi/GW, ou −15% por watt.
- **Execução:** a entrada via aquisição exigiu canal próprio, fora do loop do instalador. Em 3T25 a companhia decidiu priorizar rentabilidade [Rel. p.8].
- **Conclusão:** a queda de Energia **não** significa deterioração de todo o segmento.

---

# PARTE III — Especificação dos slides

*Formato: 16:9, quatro quadrantes, título-conclusão, subtítulo cinza, linha verde fina. Intelbras em verde (#009B4E); concorrentes e benchmarks em cinza ou preto. Fonte no rodapé. Regras completas em `instrucoes_apresentacao_equity_research.md`.*

---

### Slide 1 — Regulação

**Título:** Incentivos equivalem a 95% do lucro, mas funcionam como paridade contra importados; o risco econômico está nos R$280 mi fora da ZFM

**Subtítulo:** O lucro contábil depende do regime fiscal, mas a perda econômica relevante é menor e tem data: 2029 e 2033.

**Mensagem central:** sem incentivos, o EBIT de 2025 seria negativo, mas o ROIC com incentivos é igual à Selic. Eles colocam a Intelbras em paridade com o importado, não acima dele. O que está em risco é a parte fora de Manaus.

**I. (superior esquerdo) O EBIT de 2025 só existe por causa dos incentivos**
- **Gráfico:** waterfall.
  - Barras: EBIT sem incentivos (−34,5) + ICMS-AM 180,0 + ICMS SC/MG/PE 156,4 + Lei de TICs 123,3 = EBIT 425,2.
  - Callouts grandes: **10,3%** da receita · **85%** do EBITDA · **95%** do lucro líquido.
- **Fonte:** DFP NE 23; DRE 2025.
- **Conclusão:** o lucro contábil é, em sua maior parte, incentivo.

**II. (superior direito) Cada incentivo tem uma data**
- **Gráfico:** linha do tempo de 2026 a 2075.
  - Lei de TICs até 2029.
  - ICMS até 2032, com faixa "redução 2029–32 compensada pelo Fundo".
  - SUDAM até 2033.
  - ZFM até 2073, em verde.
  - Marco: "IPI só para produtos da ZFM a partir de 2027".
- **Fonte:** DFP NE 23; E18; E19.
- **Conclusão:** o incentivo mais valioso (AM, R$180 mi) é o mais durável.

**III. (inferior esquerdo) Perda contábil ≠ perda econômica**
- **Tabela:** BASE / PARCIAL / ELIMINADO × repasse de 0%, 50% e 75%, mostrando a variação do lucro líquido.
  - PARCIAL: −58% / −29% / −14%.
  - ELIMINADO: −95% / −48% / −24%.
  - Destaque verde: caso econômico central do PARCIAL, **−21%**.
- **Fonte:** cálculo próprio sobre DFP 2025.
- **Conclusão:** o valor em risco depende do repasse e da reação dos rivais.

**IV. (inferior direito) Paridade, não margem extra**
- **Gráfico:** barras horizontais.
  - ROIC pré-IR de 2025: **15,1%** (verde).
  - Selic: 13,75–14,75% (cinza).
  - EBIT sem incentivos: −0,8% de margem.
  - Nota: "Multilaser/Hikvision também na ZFM".
- **Fonte:** Planilha; E10; E3.
- **Conclusão:** o incentivo traz o retorno até o custo de capital.

**Layout**
- Waterfall no quadrante I, ocupando 55% da largura.
- Callout "95%" em verde a 40pt, acima do waterfall.
- Seta verde da faixa "ZFM 2073" (II) até a barra ICMS-AM (I).
- Círculo verde em "−21%" (III).

**SO WHAT:** modelar os incentivos como linha explícita, com degrau em 2030 (Lei de TICs) e em 2033 (ICMS fora da ZFM), aplicando repasse. O valor em risco é de ~R$100–280 mi de lucro, não de R$460 mi.

---

### Slide 2 — Canal

**Título:** O moat da Intelbras está no canal, não no hardware: a exclusividade de 95% dos distribuidores protege share em Segurança, mas é comprada e não gera escala de custo

**Subtítulo:** O canal defende margem bruta e volume; não explica expansão de margem nem de retorno.

**Mensagem central:** o instalador escolhe Intelbras pelo custo total de fazer o serviço. O canal é pago com desconto, prazo e estoque, e o retorno caiu enquanto a rede crescia.

**I. Fluxo do dinheiro e da especificação**
- **Esquema:** Intelbras → ~500 pontos (**68%** das vendas) → 90 mil instaladores → usuário. Varejo 16% e integradores 16% em cinza.
  - Callouts: R$6,1 mi por ponto por ano; **R$33,7 mil por instalador por ano** [ESTIMATIVA].
- **Fonte:** FRE 1.4.b; cálculo.
- **Conclusão:** o distribuidor agrega; o instalador especifica.

**II. O contrato econômico com o canal**
- **Tabela de duas colunas** ("Intelbras dá" × "Canal entrega"):
  - Intelbras dá: proteção de preço, rotação de estoque, leads, desconto de 2–9%.
  - Canal entrega: exclusividade (**95%**), dados de sell-out, metas quadrimestrais, não vender ao consumidor.
- **Fonte:** FRE 1.2, p.6–7.
- **Conclusão:** a fidelidade é comprada, e portanto replicável por quem pagar mais.

**III. O custo do canal não dilui**
- **Gráfico:** linhas de 2019 a 2025.
  - SG&A/receita: 20,3 → 17,4 → 19,3%.
  - Ciclo de caixa: 68 → 145 dias.
- **Fonte:** Planilha.
- **Conclusão:** o ganho de escala de 2021–22 foi revertido.

**IV. Flywheel testado**
- **Diagrama:**
  - loop curto em verde (treinamento → especificação → disponibilidade → volume);
  - loop longo em cinza tracejado (escala → custo → condições);
  - selo "ROIC 31% → 15%".
- **Fonte:** análise; Planilha.
- **Conclusão:** o canal é moat defensivo, não motor de expansão.

**SO WHAT:** o canal justifica share estável e margem bruta de Segurança acima da dos rivais de varejo. Não justifica premissas de alavancagem operacional: SG&A deve ficar em ~19% da receita.

---

### Slide 3 — Segurança

**Título:** Segurança concentra o valor, com 68% do lucro bruto e ROIC de ~28%, mas cresce com o mercado, e metade do excesso de retorno é o incentivo de Manaus

**Subtítulo:** O valuation deve ponderar a economia de Segurança e tratar ganho de share como não comprovado.

**Mensagem central:** só Segurança rende acima da Selic. O share está estável e a margem caiu. O retorno extra depende de Manaus.

**I. Receita por BU, 2019–2025 e 1S26**
- **Gráfico:** barras empilhadas, Segurança em verde e as demais em cinza.
  - Anotações: "+18% a.a. em 2019–25"; "+5,8% no 1S26".
- **Fonte:** Planilha.
- **Conclusão:** Segurança é o núcleo estável.

**II. ROIC estimado por segmento**
- **Gráfico:** barras.
  - Segurança 28% (verde), com a parte hachurada "sem ICMS-AM: 14,7%".
  - TIC 7,5% e Energia 5,9% (cinza).
  - Linha tracejada da Selic em 13,75%.
- **Fonte:** DFP NE 31; cálculo.
- **Conclusão:** só Segurança cria valor, e metade é fiscal.

**III. Share sem série comparável**
- **Gráfico:** pontos de share com quebras de série: 43% (2020, CFTV) · 54% (c.2022, CFTV) · 43% (2024, BU) · 44% (2025, BU).
  - Anotação: "mudança de definição".
- **Fonte:** BTG21; E30; FRE.
- **Conclusão:** estável no curto prazo; ganho estrutural não comprovado.

**IV. Crescimento = mercado**
- **Gráfico:** barras.
  - Receita +4,9% vs mercado implícito +2,5% (2025).
  - Margem bruta: 34,8% → 33,2%.
- **Fonte:** FRE; DFP NE 31; cálculo.
- **Conclusão:** o share foi defendido com preço.

**SO WHAT:** premissa de receita de Segurança ≈ mercado, de um dígito médio. A margem de Segurança é a variável que mais move o EBIT.

---

### Slide 4 — Preços e câmbio

**Título:** O preço é ancorado no custo global e no câmbio; a Intelbras captura margem apenas na defasagem de ~170 dias de estoque

**Subtítulo:** A exposição cambial está no custo, não na receita. O pricing power se resume à velocidade do repasse.

**Mensagem central:** a margem oscila ±2–5 p.p. conforme a diferença entre custo de reposição e custo médio do estoque. A margem do 2T26 é parcialmente transitória.

**I. Margem bruta trimestral × dólar**
- **Gráfico:** duas linhas, de 1T23 a 2T26.
  - Margem em verde; dólar em fim de período em cinza.
  - Anotações: "2024: dólar +28% → margem −4,9 p.p."; "2T26: reposição de componentes → +2,4 p.p."
- **Fonte:** Planilha; E11, E12.
- **Conclusão:** câmbio sozinho não explica a margem.

**II. Cadeia do landed cost e defasagens**
- **Fluxo horizontal:** FOB → frete → II → IPI → PIS/COFINS → ICMS → estoque → CPV.
  - Callouts: **173 dias** de estoque; **R$318 mi** em trânsito.
- **Fonte:** DFP NE 8.
- **Conclusão:** o choque chega ao CPV em ~2 trimestres.

**III. Sensibilidade**
- **Tabela pequena:**
  - +10% no dólar → +R$249 mi de CPV → **−5,6 p.p.** sem repasse.
  - Reajuste necessário: **+8%**.
  - Hedge: **50%** dos fornecedores em USD.
  - Efeito financeiro: ∓R$26 mi.
- **Fonte:** DFP NE 25; cálculo.
- **Conclusão:** o risco é operacional.

**IV. Quem define o preço**
- **Esquema em funil:** fabricantes globais (FOB) → câmbio → paridade de importação → faixa da Intelbras.
  - Citação: "o mercado define os preços".
- **Fonte:** FRE 2.2, p.71.
- **Conclusão:** liderança ≠ pricing power.

**SO WHAT:** usar margem bruta normalizada de ~30–31% [INFERÊNCIA], não os 33,1% do 2T26. Choques de desvalorização abrupta são assimétricos contra a Intelbras.

---

### Slide 5 — Dahua

**Título:** A Dahua dá tecnologia e financia 225 dias de capital de giro, mas concentra ~40% do custo de Segurança num contrato que vence em 2028

**Subtítulo:** A parceria aumenta o moat no curto prazo e cria a maior dependência estratégica da tese.

**Mensagem central:** um único fornecedor-acionista concentra custo, financiamento e governança. O precedente da FiberHome mostra que exclusividades terminam.

**I. Peso da Dahua**
- **Gráfico:** barras.
  - Compras: R$1.187 mi (2024) → R$729 mi (2025).
  - Linha de % dos gastos com fornecedores: 28,6% (2021) → 36% (2025).
- **Fonte:** DFP NE 32; FRE.
- **Conclusão:** concentração crescente.

**II. A Dahua como financiadora**
- **Callouts:** saldo de **R$449 mi**; prazo implícito de **225 dias**.
  - Barra: ROIC de 18,8% → 17,1% se o prazo cair para 90 dias.
- **Fonte:** DFP NE 31/32; cálculo.
- **Conclusão:** parte do ROIC é crédito do fornecedor.

**III. Linha do tempo de riscos**
- 2007 parceria → 2018 acordo de 10 anos → 2019 participação de 7,56% → ago/2025 venda autorizada → **dez/2028 vencimento**.
- Linha paralela em cinza: FiberHome, de jan/2024 a jan/2026, "exclusividade encerrada".
- **Fonte:** FRE; E27; E37.
- **Conclusão:** existe o precedente de fim de exclusividade.

**IV. Balança moat × dependência**
- **Matriz de duas colunas:**
  - Moat: tecnologia, financiamento, exclusividade de marca.
  - Dependência: ~40% do CPV, poucos chipsets, conselheiro da Dahua Brasil, Imou no cross-border.
- **Fonte:** FRE; E36.
- **Conclusão:** dependência > moat.

**SO WHAT:** a renovação de 2028 é o principal evento de risco da margem de Segurança. Cada +1% no preço da Dahua equivale a ~R$7 mi de lucro bruto [ESTIMATIVA: 1% × R$729 mi].

---

### Slide 6 — Drivers de Segurança (sugeridos)

**Título:** A demanda de Segurança segue a percepção de risco e a obra, não o crime: o medo sobe com o crime em queda, e os lançamentos recordes só chegam à instalação em 2027–28

**Subtítulo:** Insegurança é piso de demanda. Construção e retrofit de condomínios são o motor, com defasagem.

**Mensagem central:** usar entregas de obra e retrofit como âncora de volume. A percepção de insegurança traz ciclicidade, não aceleração estrutural.

**I. Crime × percepção**
- **Gráfico:** duas linhas.
  - MVI por 100 mil (cinza, em queda: 19,1 em 2025).
  - % que cita segurança como maior problema (verde: 17% → 38% → 30%).
- **Fonte:** E4, E5, E6.
- **Conclusão:** o driver é percepção.

**II. Lançamentos → instalação**
- **Gráfico:** barras de lançamentos 2024–25 (+30,1%), com a parcela MCMV de 86%.
  - Seta "24–36 meses" até a "instalação em 2027–28".
- **Fonte:** E8.
- **Conclusão:** demanda defasada.

**III. Estoque de condomínios = retrofit**
- **Callouts:** **13,3 mi** de unidades; **mais de 14 mil** condomínios com portaria remota; serviço **+24%** (2024).
- **Fonte:** E7, E9.
- **Conclusão:** driver maior e menos cíclico.

**IV. O que chegou à Intelbras**
- **Gráfico:** barras de receita de Segurança: +4,9% (2025), +5,8% (1S26).
  - Nota: "mercado em evolução moderada".
- **Fonte:** Planilha; FRE p.24.
- **Conclusão:** os drivers sustentam, não aceleram.

**SO WHAT:** projetar Segurança com base em obras defasadas e retrofit, com crescimento de um dígito médio. O upside vem de 2027–28, não de 2026.

---

### Slide 7 — Juros

**Título:** Juros altos comprimem Energia e TIC mais que Segurança, criando sensibilidades distintas dentro do portfólio

**Subtítulo:** O corte da Selic beneficia primeiro as BUs dependentes de financiamento, justamente as de pior retorno.

**Mensagem central:** a sensibilidade a juros segue a ordem Solar > TIC > Segurança. O ciclo de cortes ajuda o volume, mas não muda a estrutura.

**I. Selic** — linha: 14,75% → 13,75% (abr–set/2026). Fonte: E10.

**II. Crescimento por BU (2025 / 1S26)** — barras: Segurança +4,9% / +5,8%; TIC −8,0% / +13,7%; Energia −31,0% / −12,4%. Fonte: Planilha.

**III. Matriz de transmissão** — linhas são variáveis e colunas são BUs, com intensidade em tons de verde. Fonte: seção 4.

**IV. Provisão para perda de crédito** — barras: R$7,1 mi (2024) → R$28,8 mi (2025). Fonte: Planilha.

**SO WHAT:** juros em queda reabrem volume em TIC e Energia, mas essas BUs rendem abaixo da Selic. Crescer nelas só cria valor com margem maior.

---

### Slide 8 — TIC e 5G (sugerido)

**Título:** TIC tem 9% de share porque enfrenta escala global e compradores técnicos; o espaço real está em redes empresariais e cabeamento, não em GPON nem 5G

**Subtítulo:** O mercado é grande, mas a vantagem de canal da Intelbras vale pouco onde quem especifica é engenheiro.

**Mensagem central:** GPON está maduro e sem exclusividade de parceiro. O 5G é nicho de CPE. O cabeamento tem preço protegido, mas capacidade limitada.

**I. Receita de TIC, 2019–25 e 1S26**
- **Gráfico:** barras, com a anotação "GPON ↓, cabeamento e redes ↑".
- **Fonte:** Planilha; Rel. p.7–8.
- **Conclusão:** a mudança de mix está em curso.

**II. Escala dos rivais**
- **Gráfico:** barras.
  - Hikvision US$12,95 bi; Dahua ~US$4,5 bi (cinza).
  - Intelbras US$0,8 bi (verde).
  - Nota: TP-Link com 21% dos roteadores na América Latina.
- **Fonte:** E1, E2, E28.
- **Conclusão:** em TIC, a escala é global.

**III. Drivers**
- **Callouts:**
  - banda larga **+2,7%**;
  - fibra **79%**;
  - PPPs **63%**;
  - 5G em **80%** da população;
  - antidumping de **5 anos**;
  - FiberHome sem exclusividade desde **jan/2026**.
- **Fonte:** E17, E22, E25, E26, E27.
- **Conclusão:** um driver protegido (cabos); os demais fracos.

**IV. Retorno**
- **Gráfico:** barra do ROIC estimado de 7,5% vs Selic de 13,75%.
- **Fonte:** DFP NE 31.
- **Conclusão:** priorizar retorno, não volume.

**SO WHAT:** TIC não deve ser modelada como história de ganho de share. Projetar cabeamento limitado pela capacidade e redes empresariais. O 5G é opção.

---

### Slide 9 — Energia e solar

**Título:** Energia sem solar é um negócio de canal defensável; solar é commodity global em contração e explica a queda de 31% do segmento

**Subtítulo:** A queda de Energia não significa deterioração de todo o negócio.

**Mensagem central:** o mercado solar caiu 29% em volume e 40% em investimento, e a Intelbras saiu por decisão de rentabilidade. O restante cresce com margem melhor.

**I. Receita de Energia, 2019–25**
- **Gráfico:** barras, com pico de R$1.408 mi em 2022 e R$753 mi em 2025.
- **Fonte:** Planilha.

**II. Mercado solar**
- **Gráfico:** barras de 15 → 10,6 GW.
  - Linha do Fio B: 45% → 60% → 75% → 90%.
- **Fonte:** E20, E21.

**III. Share**
- **Gráfico:** solar 2,1% → 1,9% vs Energia sem solar 19% (líder: SMS/Legrand).
- **Fonte:** BTG21; FRE; E29.

**IV. O núcleo melhora**
- **Callouts do 2T26:** receita **−13,5%** e lucro bruto **+12%**.
- **Fonte:** Rel. p.8.

**SO WHAT:** avaliar Energia sem solar pelo canal (como um "satélite" de Segurança) e solar como opção de baixo valor. A queda do segmento é sobretudo solar.

---

### Slide 10 — Regras de importação

**Título:** As regras de importação protegem cabos e o canal profissional, mas o II zero no cross-border expõe o varejo plug-and-play

**Subtítulo:** O efeito líquido depende do mix: ganho em cabeamento, risco no varejo.

**Mensagem central:** antidumping e Anatel são barreiras úteis. O fim da "taxa das blusinhas" devolve ao importado direto o preço mais baixo em itens simples.

**I. Antidumping** — linha do tempo dez/2025 → ~2030, com US$2,42/kg (cabos) e US$47,46/kg (fibra). Fonte: E17.

**II. Fiscalização da Anatel** — callouts: 8,02 mi de produtos retirados desde 2018; 4.226 apreensões em CDs na Black Friday de 2024. Fonte: E13, E14.

**III. Cross-border** — regime: II de 20% (ago/24) → 0% (mai/26), mais ICMS de 17–20%; encomendas −11% em 2024. Fonte: E15, E16.

**IV. Mapa de exposição** — matriz categoria × canal: câmeras Wi-Fi e roteadores no varejo (16%) em cinza escuro = exposto; cabos e CFTV profissional em verde = protegido. Fonte: FRE 1.4.b.

**SO WHAT:** risco de margem no varejo plug-and-play a partir do 2S26. Preço protegido em cabos até ~2030, com volume limitado pela capacidade.

---

# PARTE IV — Síntese da tese setorial

**1. Em quais mercados a Intelbras tem vantagem competitiva comprovável?**
- **Só em Segurança residencial, condominial e de PMEs**, vendida pelo instalador. Três evidências:
  - share alto e estável (43–44%);
  - retorno acima do custo de capital (~28% estimado);
  - canal cativo (95% de exclusividade).
- **Em TIC e Energia, não há evidência:** share de 9% e 19% e ROIC abaixo da Selic.

**2. Qual a origem da vantagem?**
- Em ordem de evidência:
  1. **Canal**: exclusividade e capilaridade;
  2. **Treinamento**: 370 mil qualificações por ano;
  3. **Tributos**: Manaus explica ~metade do excesso de retorno de Segurança;
  4. **Assistência e disponibilidade**: estoque de 173 dias, rede nacional.
- **Não vem de:** escala industrial, tecnologia própria de núcleo ou sourcing. Neste último, a Dahua é dependência.
- **Marca:** não comprovada como pricing power.

**3. Quais vantagens os concorrentes podem replicar?**
- A vantagem fiscal (Multilaser/Hikvision já está na ZFM).
- Os descontos e o Pontua.
- A proteção de preço (exige balanço).
- O sourcing (os rivais são os próprios fabricantes).

**4. Quais são difíceis de replicar?**
- A base de 90 mil instaladores treinados, construída em décadas.
- A exclusividade simultânea de ~95% dos distribuidores, que exige portfólio amplo e balanço para proteger o canal.
- A escala local em Manaus para Segurança.

**5. Onde a Intelbras está ganhando share?**
- Comprovado: **em nenhuma BU em 2025** (todas estáveis).
- Indícios sem série comparável:
  - CFTV em 2020–22 (43% → 54%);
  - controle de acesso (27% → 29%);
  - cabos ópticos em 2026, por causa do antidumping [Rel. p.8].

**6. Onde está perdendo?**
- **Solar:** 2,1% → 1,9%, por decisão de rentabilidade.
- **GPON:** retração deliberada; fim da exclusividade FiberHome.
- **Provável no varejo plug-and-play** a partir de mai/2026 (cross-border), ainda não mensurado.

**7. Qual BU tem a melhor estrutura setorial?**
- **Segurança.** O comprador é o instalador (o canal pesa), há cesta de produtos para condomínios e o incentivo de Manaus é durável.

**8. Qual tem a pior?**
- **Solar**, que é commodity global, com Fio B e sem canal próprio diferenciado.
- Entre as BUs reportadas, **TIC**: rivais 5–16x maiores, compradores técnicos e ROIC estimado de 7,5%.

**9. Que variáveis explicam a margem bruta?**
1. Diferença entre custo de reposição e custo médio do estoque: câmbio × componentes em USD × 173 dias.
2. Velocidade de repasse, limitada pela paridade de importação.
3. Mix entre BUs (Energia e TIC ~25% vs Segurança 33%).
4. ICMS incentivado: +5,7 p.p. na margem reportada.
5. Custo da Dahua (~40% do CPV de Segurança).
6. Deflação tecnológica (−1 a −2 p.p. por ano em Segurança, de 2020 a 2025 [INFERÊNCIA: ~39% → 33%]).

**10. Quais três fatores têm maior capacidade de alterar o EBIT/EBITDA em 3–5 anos?**
1. **Transição dos incentivos fora da ZFM (2029–2033):** R$280 mi brutos; ~R$100 mi no caso econômico central.
2. **Renovação com a Dahua (2028):** cada 1% no preço = ~R$7 mi; perda da plataforma = risco à margem de 33% de Segurança.
3. **Pricing e câmbio:** 1 p.p. de margem bruta = R$45 mi; +10% no dólar sem repasse = −R$249 mi.

Para o ROIC, há um quarto fator: o capital de giro do canal (ciclo de caixa de 132–145 dias).

**11. Quais são os maiores riscos para a tese?**
1. Não renovação, ou renovação pior, com a Dahua.
2. Lei de TICs não renovada em 2029 e incentivos de SC/MG/PE sem compensação.
3. Contestação da exclusão das subvenções da base de IR/CSLL (R$156 mi).
4. Desvalorização abrupta do real com a concorrência impedindo repasse.
5. Cross-border e plug-and-play reduzindo a relevância do instalador.
6. Crise de memória e chips (fornecedor pequeno no fim da fila).

**12. O que o mercado provavelmente está subestimando? [INFERÊNCIA]**
- **A favor:**
  - a parcela mais valiosa do incentivo (Manaus, R$180 mi) é a mais durável (2073) e foi reforçada pela reforma (IPI só para produtos da ZFM). A manchete "95% do lucro" exagera o risco econômico;
  - há potencial de liberação de capital de giro (ciclo de 145 → 132 dias no LTM).
- **Contra:**
  - o risco Dahua 2028, agravado pela saída da Dahua do capital e pelo precedente FiberHome;
  - a reabertura do cross-border no plug-and-play desde mai/2026;
  - o caráter transitório da margem do 2T26, que a própria companhia reconhece.
- **Contexto do sell-side:**
  - BTG: "barata não basta" (2026 como ano de reorganização) [E31];
  - JPMorgan rebaixou para neutro de olho no 2S26 [E32].
- [INFERÊNCIA] O debate do mercado parece centrado no curto prazo (margem e 2S26), não na estrutura fiscal e de fornecimento.

---

# PARTE V — Matriz setorial (1 = muito baixo · 5 = muito alto)

*Nas linhas de intensidade competitiva e de risco, nota alta é desfavorável.*

| Atributo | Segurança | TIC | Energia |
|---|---|---|---|
| Crescimento | 3 | 2 | 2 (sem solar: 3; solar: 1) |
| Market share | 5 | 2 | 3 |
| Pricing power | 3 | 2 | 2 |
| Intensidade competitiva (↑ pior) | 3 | 5 | 4 |
| Barreira de entrada | 4 | 2 | 2 |
| Moat de distribuição | 4 | 2 | 3 |
| Risco regulatório (↑ pior) | 3 | 4 | 4 |
| Risco cambial (↑ pior) | 4 | 4 | 5 |
| Rentabilidade | 5 | 2 | 2 |
| Perspectiva estrutural | 4 | 2 | 2 (sem solar: 3) |

**Justificativas**

| Atributo | Segurança | TIC | Energia |
|---|---|---|---|
| **Crescimento** | +4,9% (2025) e +5,8% (1S26); mercado implícito +2,5% em 2025; obras defasadas e retrofit dão suporte | −8,0% (2025) e +13,7% (1S26, com base fraca); "sem expansão relevante" [FRE]; banda larga +2,7% | −31% (2025); solar −29% em GW no país; carregadores de VE +64% na frota (base pequena) |
| **Market share** | 44%, líder [FRE] | 9% [FRE]; TP-Link lidera roteadores na região [E28] | 19% sem solar (desafiante da SMS/Legrand); 1,9% em solar |
| **Pricing power** | Repassa custos (2T26), mas não fixa o nível: margem de ~39% → 33,2% | Compradores técnicos; GPON com "controle de preço e crédito" defensivo | Solar é commodity; nobreak com líder estabelecido |
| **Intensidade competitiva** | Hikvision com montagem local; cross-border no plug-and-play; Control iD e JFL em nichos | Huawei, Cisco e TP-Link com escala global; FiberHome agora livre | SMS/Legrand, Schneider, TS Shara e WEG; solar pulverizado e global |
| **Barreira de entrada** | Canal exclusivo + 90 mil instaladores + ZFM, mas a Hikvision entrou com R$6 mi via Multilaser [E3] | Baixa no varejo e em redes; temporária em cabos (antidumping) | Baixa em solar; média em nobreak (rede de assistência) |
| **Moat de distribuição** | 68% via distribuição; 95% exclusivos; instalador especifica | Integradores multimarca; GPON direto a provedores | Nobreak usa o mesmo canal (moderado); solar usa canal próprio (fraco) |
| **Risco regulatório** | ICMS-AM durável (ZFM); II zero no cross-border; SC até 2032 | Lei de TICs em 2029; ICMS SC até 2032; antidumping temporário | Fio B até 90% em 2028; II sobre módulos; restrições de conexão |
| **Risco cambial** | CFTV importado ou da Dahua em USD; 173 dias de estoque amortecem | Equipamentos e chips em USD | Módulos e inversores em USD, com deflação global |
| **Rentabilidade** | Margem bruta de 33,2%; lucro bruto/capital de 67%; ROIC estimado de ~28% (~14,7% sem ICMS-AM) | Margem bruta de 25,7%; lucro bruto/capital de 30,5%; ROIC estimado de ~7,5% | Margem bruta de 24,6%; lucro bruto/capital de 27,7%; ROIC estimado de ~6% |
| **Perspectiva estrutural** | Retrofit + obras + IP/IA + Manaus; risco Dahua em 2028 | Cabeamento e redes de PMEs; GPON e 5G fracos | Sem solar: estável, ligada a obras e VE; solar: estrutural negativa |

---

## Fontes externas

- **[E1]** Hikvision — [2025 full year and 2026 Q1 results](https://www.hikvision.com/en/newsroom/latest-news/2026/hikvision-2025-full-year-and-2026-first-quarter-financial-results/)
- **[E2]** Stock Analysis — [Zhejiang Dahua Technology, income statement](https://stockanalysis.com/quote/she/002236/financials/income-statement/)
- **[E3]** Forbes Brasil — [Multilaser assume gestão de produtos de segurança da Hikvision no Brasil (2022)](https://forbes.com.br/forbes-money/2022/04/multilaser-assume-gestao-de-produtos-de-seguranca-de-chinesa-hikvision-no-brasil/)
- **[E4]** CNN Brasil (Anuário FBSP) — [Mortes violentas caem 8,2% no Brasil em 2025](https://www.cnnbrasil.com.br/nacional/brasil/mortes-violentas-caem-82-no-brasil-em-2025-sete-estados-registram-alta/)
- **[E5]** Gazeta do Povo (Quaest) — [Violência é a maior preocupação dos brasileiros](https://www.gazetadopovo.com.br/republica/violencia-maior-preocupacao-brasileiros-aponta-quaest/)
- **[E6]** Portal Tela (Quaest, jun/2026) — [Violência lidera as preocupações do eleitorado](https://www.portaltela.com/noticias/politica/2026/06/04/violencia-lidera-as-preocupacoes-do-eleitorado-para-2026/); Poder360 — [Segurança e saúde são os maiores problemas](https://www.poder360.com.br/poder-pesquisas/seguranca-e-saude-sao-os-maiores-problemas-dos-brasileiros-diz-pesquisa/)
- **[E7]** Monitor Mercantil (Abese) — [Segurança eletrônica faturou R$14 bi em 2024](https://monitormercantil.com.br/seguranca-eletronica-faturou-r-14-bilhoes-em-2024-no-brasil/)
- **[E8]** InfoMoney (Abrainc/Fipe) — [Mercado imobiliário fecha 2025 com recordes](https://www.infomoney.com.br/business/mercado-imobiliario-fecha-2025-com-recordes-em-lancamentos-e-vendas-apesar-de-juros/); Portas — [Recorde de lançamentos em 2025](https://portas.com.br/noticias/mercado-imobiliario-bate-recorde-de-lancamentos-em-2025/); Abrainc — [Release de indicadores](https://cdn.abrainc.org.br/files/2026/2/Release_Indicadores_202601.pdf)
- **[E9]** SíndicoNet — [Mercado em crescimento](https://www.sindiconet.com.br/informese/mercado-em-crescimento-noticias-seguranca); Gazeta SP — [Portaria remota vira tendência](https://www.gazetasp.com.br/estado/portaria-remota-e-mercadinhos-viram-tendencia-em-condominios/)
- **[E10]** Atlas Público (BCB) — [Copom reduz Selic para 13,75%](https://atlaspublico.com.br/bcb/noticias/copom-reduz-selic-para-13-75pct-ao-ano-em-decisao-unanime-87748)
- **[E11]** Numerando — [Dólar 2025, médias anuais](https://numerando.com.br/cambio/dolar-americano/2025); [variação acumulada](https://www.numerando.com.br/indices/dolar/acumulado)
- **[E12]** InfoMoney — [Dólar fecha a R$5,16 no semestre](https://infomoney.com.br/mercados/dolar-fecha-a-r-516-no-semestre-o-que-esperar-ate-o-fim-de-2026)
- **[E13]** Teletime — [Operação Black Friday da Anatel usa IA para fiscalizar marketplaces](https://teletime.com.br/29/11/2024/operacao-black-friday-da-anatel-usa-ia-para-fiscalizar-marketplaces/); Hardware.com.br — [Anatel apreende produtos sem homologação](https://www.hardware.com.br/noticias/anatel-apreende-produtos-sem-homologacao-black-friday/)
- **[E14]** Olhar Digital — [Blitz da Anatel em Amazon, Shopee e Mercado Livre (2025)](https://olhardigital.com.br/2025/05/26/reviews/blitz-da-anatel-mira-eletronicos-piratas-na-amazon-shopee-e-mercado-livre/)
- **[E15]** Olhar Digital — [Governo anuncia fim da "taxa das blusinhas"](https://olhardigital.com.br/2026/05/12/pro/governo-anuncia-fim-da-taxa-das-blusinhas-sobre-itens-importados/); Santander — [Taxação de importados](https://www.santander.com.br/blog/taxacao-produtos-importados); Showmetech — [Congresso aprova fim da taxa](https://www.showmetech.com.br/congresso-aprova-fim-taxa-blusinhas-compras-ate-50-dolares/)
- **[E16]** Olhar Digital — [Compras internacionais recuam em 2024](https://olhardigital.com.br/2025/01/29/pro/taxa-das-blusinhas-compras-internacionais-recuam-mas-arrecadacao-bate-recorde-em-2024/)
- **[E17]** Teletime — [Feninfra critica antidumping sobre fibra óptica da China](https://teletime.com.br/05/01/2026/feninfra-critica-medida-antidumping-sobre-fibra-optica-da-china/); Normas Brasil — [Resolução Gecex 829/2025](https://www.normasbrasil.com.br/norma/resolucao-829-2025_488235.html)
- **[E18]** TaxGroup — [Zona Franca de Manaus e reforma tributária](https://www.taxgroup.com.br/intelligence/zona-franca-de-manaus-e-reforma-tributaria-o-que-muda-impactos-e-o-futuro-da-regiao/)
- **[E19]** TaxGroup — [Fundo de Compensação de Benefícios Fiscais](https://www.taxgroup.com.br/solutions/fundo-de-compensacao-de-beneficios-fiscais-na-reforma-tributaria/); Reforma Tributária — [Lei libera R$8,8 bi em 2025](https://www.reformatributaria.com/governo/lula-sanciona-lei-que-libera-r-88-bilhoes-em-2025-para-compensar-beneficios-fiscais-extintos-pela-reforma/)
- **[E20]** Esfera Energia — [Fio B e taxa de energia solar](https://blog.esferaenergia.com.br/geracao-distribuida/taxa-de-energia-solar?amp=1)
- **[E21]** eixos (Absolar) — [Expansão da energia solar retraiu 29% em 2025](https://eixos.com.br/solar/expansao-da-energia-solar-retraiu-29-em-2025-indica-absolar/)
- **[E22]** Agência Gov — [80% da população terá 5G até o fim de 2026](https://agenciagov.ebc.com.br/noticias/202603/80-da-populacao-brasileira-tera-acesso-ao-5g-ate-o-fim-de-2026)
- **[E23]** Canaltech — [Intelbras é a primeira a fabricar dispositivos 5G no Brasil](https://canaltech.com.br/telecom/intelbras-e-a-primeira-empresa-a-fabricar-dispositivos-5g-no-brasil-193655/)
- **[E24]** Teletime — [Intelbras aposta em FWA 5G com até 20% da banda larga (2023)](https://teletime.com.br/04/09/2023/intelbras-aposta-em-fwa-5g-com-ate-20-de-participacao-na-banda-larga/)
- **[E25]** TI Inside — [Banda larga fixa cresceu 2,7% em dezembro de 2025](https://tiinside.com.br/04/02/2026/acesso-a-banda-larga-fixa-cresceu-27-em-dezembro-de-2025/)
- **[E26]** Tribuna do Planalto — [Pequenas operadoras sustentam a concorrência na banda larga](https://tribunadoplanalto.com.br/anatel-afirma-que-pequenas-operadoras-sustentam-concorrencia-na-banda-larga-fixa/)
- **[E27]** Teletime — [Fim da exclusividade GPON da FiberHome (jan/2026)](https://teletime.com.br/12/01/2026/intelbras-anuncia-fim-da-exclusividade-na-venda-de-gpon-da-fiberhome/); [Acordo de 2023](https://teletime.com.br/25/10/2023/intelbras-vai-fabricar-produtos-da-chinesa-fiberhome-no-brasil/)
- **[E28]** Teletime — [Fornecedores líderes em IoT residencial na América Latina (2020)](https://teletime.com.br/24/01/2020/pesquisa-aponta-os-fornecedores-lideres-em-iot-residencial-na-america-latina/)
- **[E29]** DCD — [SMS (Legrand) oferece nobreaks para TI corporativa](https://www.datacenterdynamics.com/br/not%C3%ADcias/sms-oferece-nobreaks-para-mercado-corporativo-de-ti/); Zoom — [Marcas de nobreak](https://www.zoom.com.br/no-break/ts-shara)
- **[E30]** Genial — [Intelbras: o poder da distribuição](https://analisa.genialinvestimentos.com.br/setores/tecnologia/intelbras-s-a-intb3-o-poder-da-distribuicao/)
- **[E31]** Eu Quero Investir (BTG) — [Intelbras: barata não basta](https://euqueroinvestir.com/acoes/intelbras-barata-nao-basta-2026-arrumacao-da-casa)
- **[E32]** Money Times — [JPMorgan rebaixa Intelbras](https://www.moneytimes.com.br/apos-salto-nas-acoes-jp-morgan-rebaixa-recomendacao-de-intelbras-intb3-de-olho-no-segundo-semestre-lils/)
- **[E33]** Safra — [Intelbras 2T26: margens e lucro](https://oespecialista.safra.com.br/analise/intelbras-2t26-margens-lucro/)
- **[E34]** Guru3D — [Phison: crise de DRAM e NAND em 2026](https://www.guru3d.com/story/phison-warns-2026-dram-and-nand-crunch-could-wipe-out-budget-brands/); RedShark — [AI memory shortage](https://www.redsharknews.com/ai-memory-shortage-dram-nand-creative-industries)
- **[E35]** Buscador NCM — [NCM 8525.89.13](https://buscadorncm.com.br/ncm/85258913) (fonte secundária; validar na TIPI e na TEC)
- **[E36]** Pelando — [Câmera Imou vendida via AliExpress](https://www.pelando.com.br/d/imou-c-mera-ip-de-vigil-ncia-exterior-rastreamento-autom-tico-prova-de-intemp-ries-detec-o-humana-ai-bala-2c-2mp-2mp-aliexpress-55d1)
- **[E37]** FilingReader — [Dahua autoriza venda de 7,56% da Intelbras](https://filingreader.com/news-wire/shenzhen/2025-08-15/dahua-technology-to-sell-756-stake-in-intelbras)
- **[E38]** Teletime — [Intelbras vai investir R$200 mi em Manaus](https://teletime.com.br/27/04/2026/intelbras-vai-investir-r-200-milhoes-em-nova-fabrica-em-manaus/)
- **[E39]** Control iD — [Datasheet iDBlock Next (fabricação nacional)](https://www.controlid.com.br/manual/idblock-next-bqc-datasheet.pdf)

*Análise setorial para fins de estudo. Não é recomendação de investimento.*
