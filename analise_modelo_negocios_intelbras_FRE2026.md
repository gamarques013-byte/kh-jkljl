# Intelbras (INTB3) — Modelo de negócios

*Fontes primárias: Formulário de Referência 2026, versão 2 [FRE item, página]; planilha interativa 2T26 [Planilha]; Release 2T26 [Release, página]. Complementares: apresentação BTG CEO Conference 2021 [BTG21, slide] e imprensa [Ext.], usadas só para validar ou contestar a companhia. "Inferência:" marca conclusões minhas; "Estimativa:" marca cálculos meus.*

---

## Frase-tese

**O modelo de negócios da Intelbras funciona porque junta duas coisas. A primeira é um canal pulverizado e treinado: ~500 pontos de distribuição, mais de 90 mil instaladores e 68% das vendas. Esse canal transforma hardware de origem majoritariamente asiática em disponibilidade local e em escolha da marca pelo instalador. A segunda é um regime fiscal de produção nacional, cujo efeito equivaleu a 94% do lucro líquido de 2025. O canal sustenta volume e repasse de preço; o regime fiscal sustenta a margem.**

### Números-âncora

| Métrica | Valor | Fonte |
|---|---|---|
| Receita líquida 2025 | R$4.460 mi: Segurança 61%, TIC 22%, Energia 17% | FRE 1.3.b, p.15 |
| Lucro bruto 2025 | Segurança 67,5%, TIC 18,7%, Energia 13,8% do total | FRE 1.3.c, p.16 |
| Margem bruta 2025 (calculada) | Segurança 33,2%, TIC 25,7%, Energia 24,6% | FRE 1.3, p.15–16 |
| Mix de canais 2025 | Distribuição 68%, varejo 16%, integradores e contas nomeadas 16%; online irrelevante | FRE 1.4.b, p.22–23 |
| Base do canal | ~500 pontos de distribuição; mais de 90 mil revendedores e instaladores ativos | FRE 1.4.b, p.22 |
| Incentivos fiscais no resultado de 2025 | R$453,4 mi, ou **93,9% do lucro líquido** | FRE 2.11, p.86 |
| Dahua | 36,0% dos gastos com fornecedores (2025); saldo a pagar de R$524,4 mi | FRE 1.4.e, p.31; FRE 11.2, p.257 |
| CPV vinculado a moeda estrangeira | ~80% | FRE 2.2, p.71 |
| ROIC pré-IR | 31,2% (2019) → 15,1% (2025) → 18,8% (LTM 2T26) | Planilha; Release p.6 |

---

## A. Como gera valor e receita

### A1. O que vende: receita e lucro por segmento

| Segmento | Negócios (FRE 1.3.a, p.15) | Receita 2025 (Δ a/a) | Lucro bruto 2025 (% do total) | Margem bruta 2024 → 2025 | Market share* | Canais (FRE 1.4, p.17–19) |
|---|---|---|---|---|---|---|
| **Segurança** | CFTV, controle de acesso, alarme de intrusão, alarme de incêndio, Seventh (software) | R$2.730 mi (+4,9%) | R$907 mi (67,5%) | 34,8% → 33,2% | 44% (43% em 2024) | Todos os canais |
| **TIC** | Redes empresariais, redes ópticas (GPON), rádios, comunicação unificada, acessórios, cabeamento estruturado, Khomp, Décio (racks) | R$977 mi (−8,0%) | R$251 mi (18,7%) | 27,2% → 25,7% | 9% (9%) | Varejo, distribuição, contas nomeadas e **canal direto com provedores** |
| **Energia** | Fontes, proteção e armazenamento (nobreaks, baterias), solar on/off-grid; carregadores veiculares | R$753 mi (−31,0%) | R$185 mi (13,8%) | 24,7% → 24,6% | 19% ex-solar (19%); solar 1,9% | Distribuição, varejo, online; solar on-grid por "plataforma solar" |

\*Market share pela metodologia MIDI da própria Intelbras: dados de importação da base Comex Stat (governo federal), processados por ferramenta paga, em R$, só da controladora (FRE 1.4.c, p.23–24; FRE 1.2, p.10).
- **Não é dado independente**, e a metodologia de conversão para "tamanho de mercado" não é detalhada.
- Por ser baseado em importação, mede algo próximo do sell-in de produtos e componentes, não do sell-out.
- **Não há evidência pública independente suficiente para validar esses percentuais.**

**Peso econômico de cada segmento.**
- **Segurança é o motor de lucro:** responde por 61% da receita e 67,5% do lucro bruto.
- **Energia e TIC capturam menos margem por real vendido.** Em 2025, Energia perdeu 31% de receita e 31% de lucro bruto.

**Categorias mais relevantes dentro de cada BU.**
- **Segurança.** Os principais produtos são CFTV (câmeras e gravadores IP/analógicos) e controladores de acesso (FRE 2.2, p.70).
  - Inferência: CFTV é a maior categoria. A Dahua, cujos pagamentos são 36% dos gastos com fornecedores, fornece exatamente CFTV (câmeras + DVR), e o CPV de Segurança é 58% do CPV total (R$1.824 mi de R$3.118 mi).
  - Não há dado para confirmar a abertura por categoria.
- **TIC.** Cabeamento estruturado e redes empresariais ganharam peso; a venda de ativos de fibra óptica (GPON) caiu (FRE 2.2, p.70; Release p.7).
- **Energia.** Solar encolheu por decisão de rentabilidade; nobreaks e carregadores veiculares crescem (Release p.8).

### A2. Hardware, software e recorrência

- **Fato:** a receita é "substancialmente pela comercialização de produtos" (FRE 2.2, p.70).
- **Fato:** serviços de software proprietário geraram receita recorrente de ~R$140 mi em 2025 (FRE 1.2, p.10). Estimativa: ≈3,1% da receita.
- **Fato:** a Khomp foi comprada para "ampliar os negócios com receita recorrente" (FRE 1.1, p.2). A Seventh faz monitoramento de imagens e portaria remota (FRE 1.1, p.2).
- **Inferência:** a recorrência existe, mas é pequena demais para mudar o perfil econômico. A Intelbras é uma vendedora de hardware. O software funciona sobretudo como **custo de troca** para o instalador e o usuário: quem opera app, VMS ou portaria Intelbras tende a expandir o sistema com a mesma marca.

**Produto isolado ou ecossistema?**
- A companhia afirma que o portfólio é "integrado, complementar" e oferece "solução completa" (FRE 1.2, p.10).
- Mecanismos citados por ela: TIC dá infraestrutura a Segurança (câmera IP por rádio, vídeo-porteiro Wi-Fi), e Energia "complementa praticamente todas as soluções" das outras BUs (FRE 1.4, p.17–18).
- **Inferência:** a integração acontece no nível do **projeto do instalador** (um condomínio leva CFTV + acesso + rede + nobreak), não de uma plataforma de software que prenda o cliente.

### A3. Quando o portfólio amplo cria valor econômico

| Mecanismo | Evidência | Leitura |
|---|---|---|
| Ticket por revendedor ↑ | Não divulgado | **Não há evidência suficiente nas fontes fornecidas para concluir.** |
| CAC ↓ | SG&A/receita: 20,3% (2019) → 19,3% (2025) [Planilha] | Não aparece diluição relevante |
| Share of wallet ↑ / exclusividade | "Distribuidor Mais Verde": ~95% dos distribuidores; quem adere concede, por iniciativa própria, **exclusividade nas linhas comercializadas**, em troca de 2–9% de desconto e prioridade em lançamentos e recebimento (FRE 1.2, p.7) | **Inferência:** só faz sentido para o distribuidor ser exclusivo se uma marca cobre a cesta do instalador. Aqui a amplitude do portfólio é condição da exclusividade |
| Utilização da rede ↑ | Pontos: 370+ (2020) → ~500 (2025); revendedores: ~80 mil → 90 mil+ [BTG21 s.4; FRE p.22] | A rede cresceu junto com o portfólio; não dá para separar causa e efeito |
| Poder de barganha ↑ | Nenhum cliente acima de 10% da receita (FRE 1.5, p.32) | Poder sobre o canal, mas pago com desconto e prazo (ver B) |
| Diluição de custo fixo | G&A/receita: 6,3% → 5,8%; vendas/receita: 13,9% → 13,5% (2019 → 2025) [Planilha] | Diluição pequena |
| Menor dependência de uma categoria | Segurança cresceu em 2025 (+4,9%) enquanto Energia caiu 31% | Sim, mas as categorias novas trouxeram volatilidade |

**Conclusão (inferência).** Portfólio amplo cria valor quando a nova categoria cumpre três condições:
1. tem o **mesmo comprador** (o instalador);
2. é vendida na **mesma ocasião de compra** (a obra);
3. **usa o mesmo canal**.

As duas linhas que não cumprem são as de pior margem e estão em poda:
- **Solar** veio por aquisição da Renovigi, com "rede capilar de parceiros" própria (FRE 1.1, p.2).
- **GPON** é vendido por canal direto a provedores e passou a ter "maior controle de preços e crédito" (FRE 1.4.c, p.25).

### A4. Unit economics conceituais

*Volume × preço × mix → receita → margem bruta → despesas → capital de giro → retorno*

| | Segurança | TIC | Energia |
|---|---|---|---|
| **Volume** *(hipótese)* | Obras, condomínios, PMEs; migração analógico → IP; mercado com "evolução moderada" (FRE p.24) | Projetos de TI/PME; capex de provedores; "sem expansão relevante do mercado" (FRE p.25) | Geração distribuída (juros), PMEs (nobreaks), veículos elétricos: 613 mil eletrificados, +64% (FRE p.26) |
| **Preço** (fato) | Política de **repassar aumentos de custo** (FRE 2.2, p.71); reajuste a custo de reposição no 2T26 (Release p.7) | GPON com controle de preço e crédito; cabos ópticos protegidos por antidumping (Release p.8) | Solar: commodity global *(inferência)* |
| **Mix** | CFTV IP, IA e software ganhando peso (FRE p.24) | Cabeamento e redes ↑, fibra ↓ | Solar ↓ → lucro bruto +12% a/a com receita −13,5% no 2T26 (Release p.8) |
| **Margem bruta** (fato) | 33,2% | 25,7% | 24,6% |
| **Despesa necessária** *(inferência)* | Treinamento, suporte, assistência, marca | Pré-venda técnica para integradores e provedores | Plataforma solar; financiamento a clientes via bancos parceiros (FRE p.19) |
| **Capital de giro** *(inferência)* | Estoque de muitos SKUs + prazo ao distribuidor | Crédito a provedores (motivo do controle no GPON) | Estoque de kits sujeito a deflação; mas a Intelbras recebe à vista nas vendas financiadas por bancos (FRE p.19) |

**Fatos que limitam o poder de preço (FRE 2.2.b, p.71):**
- repasse por perda de produtividade quando o volume cai "não é usual, uma vez que o mercado define os preços";
- "a evolução tecnológica pressiona os preços para baixo"; o tíquete médio se mantém com produtos novos;
- o estoque a custo médio amortece o câmbio.

**Inferência:** a Intelbras tem poder de repassar choques de custo, mas não de fixar o nível de preço. Ele é ancorado pelo preço global da tecnologia.

**Margem: o que explica a queda de 2025 (cálculo a partir do FRE 1.3).**
- A margem consolidada caiu de 30,75% para 30,10%.
- **Efeito mix: +0,64 p.p.**, porque Energia (margem menor) perdeu peso.
- **Efeito margem dentro dos segmentos: −1,30 p.p.**, sendo −0,95 p.p. de Segurança e −0,33 p.p. de TIC.
- Contexto: o dólar caiu 11,1% em 2025 (FRE 2.2, p.71). Com política de repasse e estoque a custo médio, os preços caem antes de o custo do estoque cair.
- No longo prazo, a margem de Segurança era 38–41% em 2017–20 [BTG21 s.13] e foi 33,2% em 2025. As bases podem não ser idênticas, mas a direção é clara.

**ROIC: margem × giro** [Planilha; ROIC pré-IR = EBIT / (dívida líquida + PL)]

| | 2019 | 2022 | 2024 | 2025 | LTM 2T26 |
|---|---|---|---|---|---|
| Margem EBIT | 10,8% | 10,9% | 11,4% | 9,5% | 11,3% |
| Giro (receita / capital empregado) | 2,88x | 2,41x | 1,58x | 1,58x | 1,66x |
| **ROIC pré-IR** | **31,2%** | 26,4% | 18,1% | **15,1%** | **18,8%** |

- O ciclo de caixa (DSO + DIO − DPO) foi de 68 dias (2019) para 145 (2025) e 132 (LTM 2T26).
- O capital de giro operacional (recebíveis + estoques − fornecedores − risco sacado) é R$1,60 bi, contra R$1,25 bi de imobilizado + intangível em 2025.
- **Inferência:** o retorno é determinado mais pelo **giro do capital** do que pela margem.

**Variáveis de maior impacto** *(hipóteses de modelagem)*

| Linha | Variáveis |
|---|---|
| Crescimento | Obras, condomínios e PMEs; juros (Energia); capex de provedores |
| Margem bruta | Câmbio × dias de estoque (80% do CPV é dolarizado); mix Segurança vs Energia/TIC; termos com a Dahua; incentivos fiscais |
| EBITDA | Despesa com vendas rígida em ~13,5% da receita |
| Estoque | Lead time da Ásia; nº de SKUs; obsolescência (risco nº 2 da própria companhia, FRE 4.2, p.119) |
| Contas a receber | Prazo ao canal; perdas de crédito: PCLD de R$7,1 mi (2024) → R$28,8 mi (2025) [Planilha] |
| ROIC | Ciclo de caixa e regime fiscal (que define o NOPAT) |

---

## B. Clientes, canais e distribuição

### B1. Quem é quem na cadeia

| Rota | % 2025 (FRE p.22) | % 2020 [BTG21 s.9] | Quem paga a Intelbras | Quem especifica | Quem instala | Usuário final |
|---|---|---|---|---|---|---|
| Intelbras → distribuidor → revendedor/instalador | **68%** | 77% | ~500 pontos de distribuição | Instalador | Instalador credenciado | Residências, condomínios, PMEs |
| Intelbras → varejista → consumidor | **16%** | 13% | Varejo físico e e-commerce | Consumidor ("fácil instalação") | Consumidor ou instalador | Residências |
| Intelbras → integrador / conta nomeada | **16%** | 10% | Integradores ("instaladores que compram direto da Companhia", inclusive em projetos multimarca) e grandes clientes atendidos pela fábrica | Integrador ou área técnica do cliente | Integrador; nas contas nomeadas, a base de instaladores Intelbras (FRE p.23) | Empresas, governo, cidades inteligentes |
| Intelbras → provedores (TIC) | dentro dos 16% *(inferência)* | — | Provedores de internet | Engenharia do provedor | Provedor | Assinante de banda larga |

**Leitura:**
- O cliente direto em 68% das vendas é o **distribuidor**.
- O **especificador** é o instalador.
- O **pagador econômico** é o usuário final.
- A distribuição perdeu 9 p.p. desde 2020, para varejo e projetos. **Inferência:** cresceram as rotas onde o comprador compara preço com mais facilidade.

### B2. Quantificação

| Indicador | Valor | Fonte |
|---|---|---|
| Pontos de distribuição | ~500, contando todas as filiais de cada parceiro | FRE 1.2, p.3 (nota 4) |
| Revendedores/instaladores ativos | Mais de 90 mil; todos os 26 estados + DF | FRE 1.4.b, p.22 |
| Cobertura | 98% dos municípios "com potencial de consumo eletrônico" (dado interno) | FRE 1.1, p.1 |
| Concentração | Nenhum cliente acima de 10% da receita | FRE 1.5, p.32 |
| **Estimativa:** receita por ponto de distribuição | R$4.460 mi × 68% ÷ 500 ≈ **R$6,1 mi/ano** | cálculo |
| **Estimativa:** receita por revendedor | R$4.460 mi × 68% ÷ 90 mil ≈ **R$34 mil/ano** (~R$2,8 mil/mês) | cálculo |

Ressalva da estimativa: os 68% são de "vendas", não necessariamente de receita líquida. "500 pontos" conta filiais, então há menos grupos econômicos do que isso.

### B3. Por que essa arquitetura existe

O instalador compra cerca de R$2,8 mil por mês. Atender diretamente 90 mil compradores desse porte exigiria crédito, cobrança e frete fracionado. **O distribuidor agrega demanda, estoca perto do instalador e carrega o crédito do micro-revendedor.**

O Programa de Canais (FRE 1.2, p.6–7) mostra o "contrato econômico" com o distribuidor:
- **O distribuidor se compromete a:** metas quadrimestrais de sell-in, **informar estoque e sell-out**, seguir política de preços, **não vender ao consumidor final**.
- **A Intelbras dá em troca:** fundo de marketing cooperativo, leads, relatórios de BI, descontos, **rotação de estoque de produtos ociosos** e **proteção de preços**.

| Dimensão | Efeito | Evidência e leitura |
|---|---|---|
| Capilaridade | O distribuidor regional leva o produto ao instalador sem filiais da Intelbras | FRE p.22 |
| Custo comercial | A Intelbras não precisa de força de vendas para 90 mil contas, mas mantém promotores no varejo (26.382 visitas, 64.083 ações em PDV) e suporte (1,9 mi de atendimentos por WhatsApp) | FRE p.7–9. Despesa com vendas: 13,5% da receita [Planilha] |
| Estoque | Proteção de preços e rotação de estoque ocioso **transferem para a Intelbras parte do risco de estoque do canal** *(inferência)* | Estoque: 144–217 dias (2019–25) [Planilha] |
| Logística | Lotes grandes para ~500 pontos; CDs em São José (44 mil m²) e Jaboatão-PE | FRE p.20 |
| Capital de giro | O crédito ao micro-instalador fica com o distribuidor, mas a Intelbras financia o distribuidor e admite risco de crédito com revendas | Prazo de recebimento: 79 → 96 → 103 dias (2019 → 2025 → LTM 2T26) [Planilha]; FRE 4.1, p.97 |
| Suporte | Leads gerados no atendimento da Intelbras "são direcionados aos nossos canais parceiros" | FRE p.8. **Inferência:** o canal depende da demanda que a marca gera |
| Lançamentos | Prioridade de lançamento para distribuidores "Mais Verde" | FRE p.7 |
| Informação | Dados de estoque e sell-out do canal; o release diz que a relação sell-in/sell-out "se manteve estável" | Release p.6. **Inferência:** reduz o risco de empurrar estoque e o efeito chicote |
| Barreira à entrada | A companhia diz que o relacionamento "dificulta a entrada de novos concorrentes" | FRE p.3 (afirmação da companhia) |

### B4. O instalador: custo de troca, fidelidade e exclusividade

| Mecanismo | Evidência | Avaliação |
|---|---|---|
| **Treinamento e certificação** | 370 mil qualificações em 2025 (FRE p.1); mais de mil cursos gratuitos no Itec e 2 mi de certificados acumulados (FRE p.14) | Cria familiaridade, ou seja, custo de reaprender outra marca |
| **Fidelidade** | Níveis Ouro, Prata, Bronze e Registrado; programa "Pontua" (pontos trocados por combustível, contas etc.) (FRE p.22) | Fidelidade em parte **comprada**, portanto replicável por quem tiver caixa |
| **Preferência de especificação** | Marca reconhecida por 71% dos brasileiros (pesquisa Ana Couto); NPS de 71% no 2S25 (FRE p.11) | Dados da companhia, com viés. Reduz o esforço de venda no residencial e PME |
| **Distribuição cativa** | **~95% dos distribuidores no "Mais Verde", com exclusividade voluntária nas linhas** (FRE p.7) | **Existe, mas é voluntária, reversível e paga** (2–9% de desconto) |
| **Custo de troca do usuário** | R$140 mi de receita recorrente de software; apps e portaria remota | Moderado em sistemas; baixo em itens isolados |
| **Network effect indireto** | Leads da marca → canal; base instalada → manutenção | Fraco: é escala de canal e aprendizado, não efeito de rede clássico |

**Limites (contra a narrativa da companhia):**
1. **Integradores** trabalham por definição em projetos "que envolvam eventualmente mais de uma marca" (FRE p.23).
2. **Varejo** (16%) compara preço lado a lado com outras marcas.
3. O próprio FRE admite que revendas podem "trabalhar diretamente com nossos concorrentes" (FRE 4.1, p.97).
4. A companhia cresce em **câmeras plug and play e fechaduras digitais** (FRE p.24): produtos que dispensam o instalador. **Inferência:** a Intelbras ajuda a reduzir a relevância do próprio canal.

### B5. Distribuição como parte do produto

**Por que um concorrente com tecnologia comparável não replica rápido a posição?**
- O instalador compra um pacote: equipamento + disponibilidade local + crédito do distribuidor + treinamento + assistência (rede credenciada em todo o país, FRE p.9) + marca + leads.
- Um entrante iguala o equipamento rapidamente. O resto depende de o distribuidor estocar.
- Com ~95% dos distribuidores em exclusividade voluntária de linha, o entrante precisa primeiro **comprar a saída** do distribuidor do programa, compensando o desconto de 2–9% e a prioridade perdidos, ou montar outro canal.

| Elemento | Classificação |
|---|---|
| Base de 90 mil instaladores treinados e familiarizados | **Estrutural** (acumulada em décadas; lenta de replicar) |
| Exclusividade voluntária de ~95% dos distribuidores | **Estrutural enquanto as condições econômicas forem superiores**; replicável por quem pagar mais |
| Marca junto ao consumidor (alto renome INPI; 71% de reconhecimento) | **Estrutural parcial** (pesa menos em projetos) |
| Regime fiscal de produção local | **Regulatório**: replicável por quem produzir na ZFM ou sob PPB, e revogável |
| Cobertura de 98% dos municípios, crédito, suporte, assistência, apps | **Replicável com investimento e tempo** |

---

## C. Produção, sourcing e fornecedores

### C1. Unidades produtivas (FRE 1.4.a, p.19–21)

| Unidade | O que faz |
|---|---|
| São José/SC | Desenvolve e produz para **todas as BUs**; linhas SMD; CD de 44 mil m² |
| Manaus/AM (ZFM, desde 2009) | BU Segurança; linhas SMD; expansão de ~R$200 mi em 2026–27 (Release p.3 e p.9; [Ext.]) |
| Santa Rita do Sapucaí/MG (Maxcom, 2006) | BU Segurança, foco em controle de acesso |
| Tubarão/SC | Cabos de fibra óptica e UTP |
| **Ásia (fábricas de fornecedores na China, Coreia e Vietnã)** | Produtos de "complementação de portfólio", com volumes ou características inadequados para produção nacional (FRE p.19) |

- **Capacidade:** SMD de ~450 mi de componentes/mês; injeção plástica de ~230 t/mês; teste funcional em 100% dos produtos (FRE p.20–21).
- A companhia descreve "elevado grau de verticalização" (FRE p.21).
- **Inferência:** a verticalização é na **montagem** (placa, gabinete, cabo), não no componente crítico.

### C2. Cadeia de suprimentos

- **Matérias-primas:** semicondutores, placas de circuito impresso, plástico ABS, componentes passivos e embalagem, "em sua maioria importados" (FRE p.20, p.30). Commodities relevantes: cobre, estanho, terras raras, estireno (FRE 2.2.c, p.71).
- **Produtos acabados:** parte do portfólio é feita na Ásia (FRE p.30).
- **Moeda:** ~80% do CPV vinculado a moeda estrangeira; R$972,6 mi a pagar a fornecedores em moeda estrangeira no fim de 2025 (FRE 2.11, p.86). Hedge cobre 70% da carteira de fornecedores de importações nacionalizadas (FRE 5.1, p.142).
- **Componente crítico:** "existem poucas opções para escolha ou mudança dos chipsets"; trocar de fornecedor pode **suspender** parte das operações (FRE p.31).
- **Integração com fornecedores:** software IoT hospedado em nuvem de fornecedores; moldes de injeção da Intelbras nas fábricas deles (FRE p.31).
- **Concentração:** a Dahua respondeu por **36,0%** dos gastos com fornecedores em 2025 (FRE p.31). Em 2021 eram 28,6% ([Ext.], research citando o FRE de 2022). A concentração subiu.
- **Fornecedor substituível vs crítico** *(inferência)*:
  - substituíveis: embalagem, ABS, passivos, frete;
  - pouco substituíveis no curto prazo: chipsets e a plataforma de CFTV da Dahua.

### C3. A relação com a Dahua

**Fatos do acordo** (FRE 1.2, p.4; FRE 11.3, p.259–260; FRE 4.1, p.104–105):
- **Parceira desde 2007.** Acordo de cooperação de **31/12/2018**, por **10 anos** (até dez/2028), renovável.
- **Obrigação da Intelbras:** dar à Dahua **prioridade** de fornecimento de CFTV (câmeras + gravadores). Nos itens 1.4 e 4.1, o FRE chama isso de compra "**exclusiva**".
- **Obrigação da Dahua:** garantir à Intelbras **exclusividade na comercialização dos Produtos Dahua no Brasil**, durante o acordo e por mais 6 meses depois.
- **Saídas da Intelbras:** pode comprar de outro fornecedor se o preço da Dahua for **≥5% maior** que o de produto equivalente, se houver falha técnica ou de qualidade, falência da Dahua, ou descumprimento do acordo de acionistas pela Dahua B.V.
- **Renegociação:** preços, prazos e metas são negociados **anualmente**. A revisão de dez/2022 manteve os termos. Se rescindido pela Dahua, a Intelbras pode seguir comprando por 3 anos.
- **Exposição financeira:** saldo a pagar à Dahua de **R$524,4 mi** em 31/12/2025 (FRE 11.2, p.257). Estimativa: **~50%** de fornecedores + risco sacado, que somam R$1.049 mi [Planilha]. A Dahua é também **financiadora relevante do capital de giro**.
- **Ponto a conferir:** o "montante envolvido" desde 2018, R$680,7 mi, parece pequeno frente a 36% dos gastos de um único ano. Confirmar na nota explicativa 32 das demonstrações financeiras.
- **Societário:** a Dahua B.V. tem **7,56%** e um assento no conselho desde 2019. **O conselheiro indicado pela Dahua é administrador da Dahua Technology Brasil** (FRE 7.3, p.183). Em ago/2025, a Dahua autorizou vender seus 7,56% em até 36 meses ([Ext.] FilingReader, 15/08/2025).
- **Controle de comutatividade:** compradores no Brasil e na China fazem tomada de preço; o MIDI estima preços FOB de concorrentes; outros fornecedores são cotados em projetos novos (FRE 11.2, p.259).

| Benefícios | Riscos |
|---|---|
| **Tecnologia e P&D:** apoio da equipe de P&D da Dahua na China dá "mais agilidade" em Segurança (FRE 1.1, p.2) | **Concentração:** 36% das compras, na categoria que sustenta o segmento com 67,5% do lucro bruto |
| **Escala global** de um dos líderes mundiais de videomonitoramento (FRE p.4) | **Dependência tecnológica:** prioridade de compra até 2028; poucas alternativas de chipset |
| **Exclusividade de marca no Brasil:** em tese, impede a entrada dos Produtos Dahua por outro canal no país | **Poder de barganha:** o gatilho de 5% protege só contra preço muito fora de mercado; a renegociação anual favorece quem tem a tecnologia |
| **Custo:** preço de transferência monitorado via MIDI | **Conflito de interesse:** conselheiro da Dahua administra a subsidiária local do fornecedor; a fronteira de atuação da Dahua Brasil não é detalhada no FRE |
| **Financiamento:** R$524 mi a pagar | **Saída do capital:** a cláusula (d) liga a prioridade ao acordo de acionistas. **Não há evidência suficiente nas fontes fornecidas para concluir** o que acontece com o acordo se a Dahua vender toda a participação |
| | **Geopolítica:** o FRE cita disputas EUA–China entre os 5 maiores riscos (FRE 4.2, p.119); os EUA restringem equipamentos Dahua (fato público) |
| | **Câmbio:** compras em dólar; hedge de 70% |

**Que tipo de empresa a parceria cria? Depende da categoria** *(inferência a partir do FRE 1.1, 1.4 e 1.3)*

| Categoria | Papel predominante |
|---|---|
| CFTV | **Codesenvolvedora + montadora local** (SMD em Manaus e São José) **+ dona da marca** de uma plataforma Dahua; fato: "desenvolvidos em conjunto" (FRE p.19) |
| Controle de acesso, alarmes, incêndio | **Desenvolvedora + fabricante** (Automatiza e Engesul em 2013; Santa Rita do Sapucaí) |
| Comunicação corporativa (PABX, Khomp) | **Desenvolvedora + fabricante** (negócio de origem; primeiro PABX nacional em 1987, FRE p.1) |
| Cabos e racks | **Fabricante** (Tubarão; Décio) |
| Redes empresariais e GPON | Dona da marca / fabricante com tecnologia de parceiros ("de maneira própria ou em parceria com empresas globais", FRE p.14) |
| Complementos feitos na Ásia | **Dona da marca / distribuidora** |
| Solar | Integradora de kits; componentes majoritariamente importados *(inferência; não detalhado)* |

### C4. Onde a Intelbras realmente captura valor

| Etapa | Quem faz | Captura de valor pela Intelbras |
|---|---|---|
| P&D de núcleo (chipset, óptica, algoritmos de vídeo) | Parceiros e fornecedores | **Baixa:** paga no preço de compra |
| Engenharia de adaptação, firmware, homologação Anatel/Inmetro | Intelbras: >600 profissionais, labs de 3.200 m² (FRE p.10; homologação em FRE 1.6, p.33) | **Média:** é também condição para o incentivo fiscal (P&D obrigatório) |
| Compras | Intelbras (compradores no Brasil e na China) | **Média:** escala relevante localmente, pequena globalmente |
| Fabricação / montagem | Intelbras (4 fábricas) e Ásia | **Alta, mas por via fiscal**, não por custo industrial (ver abaixo) |
| Marca | Intelbras | **Alta** no varejo, residencial e PME |
| Distribuição, estoque e crédito | Intelbras + distribuidor | **Alta, mas intensiva em capital:** capital de giro de R$1,6 bi |
| Treinamento e relacionamento com instaladores | Intelbras (Itec, programas) | **Alta:** converte disponibilidade em especificação |
| Pós-venda | Intelbras + assistências credenciadas | **Média:** diferencia de importados sem representação |
| Software e recorrência | Intelbras (Seventh, Khomp, apps) | **Baixa em receita** (~3%); **média como custo de troca** |

**O componente fiscal (fatos: FRE 1.6, p.33–35; FRE 2.11, p.86; FRE 4.1, p.109–110).**
- **Efeito total:** os incentivos reconhecidos no resultado somaram **R$453,4 mi = 93,9% do lucro líquido de 2025**, líquidos das despesas vinculadas. Despesas de P&D ligadas aos incentivos: R$39,5 mi.
- **Federal (Lei de Informática/TICs):** crédito financeiro sobre investimento em PD&I, que exige **aplicar ao menos 4% do faturamento bruto incentivado** e cumprir PPB. Vale **até 31/12/2029**.
- **Zona Franca de Manaus:** isenção de IPI, redução do Imposto de Importação e crédito estímulo de ICMS (ICMS zero na saída), garantidos até 2073. Sudam: redução de 75% do IRPJ até 2033.
- **Estaduais:**
  - SC: ICMS efetivo de ~3% em produtos da Lei de Informática; importação com carga de 1,4%–2,5%.
  - MG: crédito presumido de 100%.
  - PE: crédito presumido até 2032.
  - Benefícios de "guerra fiscal" convalidados (LC 160) por 15 anos a partir de dez/2017.
- **Reforma tributária:** transição até 2033, com incerteza para incentivos fora da ZFM, segundo a própria companhia.

**Inferência:**
- Fabricar no Brasil cria valor sobretudo porque **destrava o regime fiscal** (e reduz prazo de entrega), não porque a fábrica seja mais eficiente.
- Os 93,9% **não significam** que o lucro sem incentivo seria de R$30 mi. Parte do benefício vira preço menor ao canal, e concorrentes importadores também usam benefícios estaduais de importação.
- Ainda assim, mostram que a **margem líquida do modelo é, em grande parte, política pública capturada**. É uma vantagem real, mas regulatória e com datas: 2029, 2033.

---

## D. Economias de escala, de escopo e poder de barganha

### D1. Escala: onde existe e onde não aparece

| Fonte de escala | Evidência | Leitura |
|---|---|---|
| Treinamento, marca, suporte, assistência (custos nacionais fixos) | 370 mil qualificações; mídia nacional; rede de assistência (FRE p.1, p.9, p.11) | **Existe contra entrantes regionais**; é o tipo de custo que um entrante não dilui |
| Produção | SMD de 450 mi de componentes/mês; Tubarão no limite de capacidade (Release p.8); imobilizado ≈ 15% da receita | Intensidade fixa baixa: **não é a fonte principal de vantagem** |
| Compras | CPV de R$3,1 bi; poucas opções de chipset | Escala local, não global |
| P&D | ~3% da receita historicamente (FRE p.10); R$179 mi em projetos em 2025, ≈4% (FRE 2.10, p.85); a lei exige 4% do faturamento incentivado | **P&D é parcialmente variável por lei:** a alavancagem é menor do que parece |
| SG&A | 20,3% (2019) → 17,4% (2022) → 19,3% (2025) [Planilha] | **Ganho de escala de 2021–22 revertido.** Manter o canal custa despesa recorrente |
| Resultado | Receita 2,6x (2019–25); margem EBITDA de 11,9% → 12,1% | **Não há evidência de economia de escala crescente** no período |

### D2. Escopo: a mesma rede vende Segurança + TIC + Energia?

- **Fatos:** Segurança é vendida em todos os canais. TIC e Energia em parte deles. A companhia descreve TIC e Energia como complementos de Segurança (FRE p.17–18). Os distribuidores aderem a exclusividade "nas linhas" (FRE p.7).
- **Inferência:** o mecanismo *mais SKUs → mais share of wallet → mais uso da infraestrutura comercial → mais relevância → mais capacidade de lançar* é **plausível dentro do trabalho do instalador** (acesso, cabeamento, nobreak).
- **Contra-evidência:**
  - as duas expansões que exigiram **outro canal** (solar via rede Renovigi, GPON via provedores) têm as **menores margens** e foram podadas;
  - o market share de TIC está parado em 9% e o de Energia ex-solar em 19% (FRE p.10).
- **Dados necessários para confirmar:**
  - número de segmentos comprados por revendedor ativo;
  - receita por revendedor;
  - participação dos distribuidores "Mais Verde" nas vendas por BU.

### D3. Matriz de poder de barganha

| Relação | Poder Intelbras | Poder contraparte | Motivo (fatos) |
|---|---|---|---|
| Intelbras × fornecedores | Limitado | Alto nos chipsets; baixo em insumos comuns | "Poucas opções" de chipset e troca pode suspender a operação (FRE p.31); 80% do CPV dolarizado |
| Intelbras × Dahua | Moderado | Alto | 36% das compras; prioridade até 2028. A Intelbras tem como contrapeso a exclusividade de marca no Brasil, o gatilho de 5% e o canal; a Dahua tem a tecnologia, R$524 mi a receber e subsidiária local |
| Intelbras × distribuidores | Alto | Baixo individualmente | Nenhum cliente acima de 10%; ~95% em exclusividade voluntária; metas de sell-in e política de preço. O custo: 2–9% de desconto, proteção de preço e prazo de ~100 dias |
| Intelbras × revendedores | Alto | Baixo individualmente, relevante coletivamente | ~R$2,8 mil/mês cada (estimativa); dependem de leads e pontos. Coletivamente especificam e podem migrar (FRE 4.1, p.97) |
| Intelbras × varejistas | Moderado | Moderado | 16% das vendas; a Intelbras mantém promotores e ações no PDV; o varejo compara preço com importados |
| Intelbras × integradores | Baixo a moderado | Alto | Projetos multimarca por definição (FRE p.23); comparação técnica e de preço; GPON/provedores exigiram "controle de preços e crédito" |
| Intelbras × consumidor final | Alto (indireto) | Baixo | Fragmentado; delega a escolha ao instalador; marca reconhecida. O limite é a deflação tecnológica (FRE 2.2, p.71) |

---

## E. Flywheel: teste da hipótese

| Elo | Evidência | Status |
|---|---|---|
| 1. Portfólio maior → relevância para o canal | Mais Verde (~95% em exclusividade de linha); pontos 370 → 500; revendedores 80 mil → 90 mil | **Evidenciado (correlação)** |
| 2. → Capilaridade e share of wallet | Capilaridade: sim. Share of wallet: não divulgado | **Parcial** |
| 3. → Volume | Segurança +18% a.a. (2019–25); share estável em 43–44% em mercado "moderado" | **Parcial** (só em Segurança) |
| 4. → Escala de compras, P&D e distribuição | SG&A estável; margem bruta de Segurança em queda; tecnologia vem da escala do parceiro | **Não evidenciado** |
| 5. → Oferta competitiva e lançamentos | Lançamentos contínuos (FRE 2.10, p.85), apoiados na Dahua | **Parcial** |
| 6. → Marca e relacionamento | NPS 71%, RA1000, alto renome (dados da companhia) | **Evidenciado** (com viés) |
| 7. → Entrada em novas categorias | Entrou em energia, solar, cabos, carregadores. Mas solar e GPON têm as piores margens e foram podadas | **Contradito** quanto a "entrada lucrativa" |
| Resultado: retorno crescente | ROIC de 31% (2019) → 15% (2025) → 18,8% (LTM 2T26) | **Contradito no ciclo 2021–24** |

**Veredito.**
- **Loop curto (forte):** instalador treinado → distribuidor exclusivo com estoque → disponibilidade local + marca → especificação → volume em Segurança → mais distribuidores aderem. Sustenta participação e repasse de preço.
- **Loop longo (fraco):** volume → escala → custo menor → entrada lucrativa em novas categorias. Não aparece nos números. O ganho de escala é capturado mais pelos parceiros de tecnologia e pelo regime fiscal do que pela Intelbras.
- **Evidências necessárias para confirmar:**
  - receita por revendedor ativo e compra cruzada entre BUs;
  - sell-out por distribuidor;
  - churn de revendedores;
  - ROIC por segmento;
  - custo de atender por canal.

---

## F. Principais fragilidades do modelo

| Fragilidade | Mecanismo | Linha afetada | Sinal já observado |
|---|---|---|---|
| **Fim ou alteração de incentivos** | Lei de TICs até 2029; Sudam até 2033; reforma até 2033 → créditos e alíquotas mudam | Margem, NOPAT, ROIC | Incentivos = 93,9% do lucro líquido (FRE p.86) |
| **Dependência da Dahua** | Renovação em dez/2028; saída do capital; renegociação anual → custo de CFTV ↑ ou troca de plataforma | Margem de Segurança (67,5% do lucro bruto) | 36% das compras; venda dos 7,56% autorizada ([Ext.]) |
| **Entrada agressiva chinesa** | Hikvision é concorrente nomeada (FRE p.26); importados entram pelo varejo e por integradores multimarca | Share, preço | Distribuição: 77% → 68% das vendas (2020–25) |
| **Commoditização / deflação tecnológica** | "A evolução tecnológica pressiona os preços para baixo" (FRE p.71) | Margem bruta | Segurança: ~39% (2020) → 33,2% (2025) |
| **E-commerce / desintermediação** | O consumidor compra direto e o valor da disponibilidade local cai. A companhia planeja integrar revendas ao e-commerce (FRE 2.10, p.84) | Volume e margem do canal | Online próprio irrelevante; varejo 13% → 16% |
| **Perda de relevância do instalador** | Plug and play, fechaduras digitais e nuvem dispensam a instalação | Base do loop curto | A própria Intelbras cresce nessas categorias (FRE p.24) |
| **Capital de giro** | Mais SKUs, importação longa, proteção de preço e prazo ao canal | ROIC, fluxo de caixa livre | Ciclo de caixa 68 → 145 dias [Planilha] |
| **Obsolescência de estoque** | Ciclo tecnológico curto (risco nº 2 da companhia) × ~5 meses de estoque | Margem (provisões) | Provisão: R$0,6 mi (2019) → R$54 mi (2025) [Planilha]; baixa de R$23,7 mi no 1S26 (Release p.15) |
| **Câmbio** | 80% do CPV dolarizado; repasse com defasagem; hedge de 70% | Margem cíclica | Dólar −11,1% em 2025 → efeito margem −1,3 p.p.; o 2T26 tem parte cíclica (Release p.2) |
| **Excesso de SKUs / complexidade** | Falha de controles, qualidade e TI são os riscos nº 1 e nº 3 (FRE p.119) | Receita, despesa | Migração do ERP no 1T25 travou o faturamento (Release p.2) |
| **Crédito do canal** | Financiar revendas e distribuidores | Despesa, recebíveis | PCLD: R$7,1 mi → R$28,8 mi (2024 → 25) [Planilha] |
| **Relação com distribuidores** | Exclusividade voluntária: se as condições piorarem, o distribuidor sai do programa | Volume, share | Não observado; sell-in/sell-out estável (Release p.6) |

---

## 5 insights que realmente importam para a tese de investimento

**1. Os incentivos equivalem a 93,9% do lucro líquido (R$453 mi em 2025).**
- *Mecanismo:* produzir sob PPB, ZFM e Lei de TICs gera crédito federal, isenções e ICMS reduzido. Fabricar no Brasil vale mais pelo regime fiscal do que pelo custo industrial.
- *Consequência:* margem líquida e ROIC dependem de política pública com datas (Lei de TICs em 2029; Sudam e reforma em 2033). Os incentivos devem ser tratados como variável explícita no modelo, e a expansão de Manaus (R$200 mi) deve ser lida também como decisão fiscal.

**2. 68% das vendas passam por ~500 pontos, e ~95% dos distribuidores concedem exclusividade voluntária de linha em troca de 2–9% de desconto, proteção de preço e rotação de estoque.**
- *Mecanismo:* a Intelbras "compra" prateleira, disciplina de preço e dados de sell-out. Em troca, absorve parte do risco de estoque e do crédito do canal.
- *Consequência:* isso protege volume e o share de 44% em Segurança, mas tem custo recorrente. Despesa com vendas fica em ~13,5% da receita e o ciclo de caixa vai a 145 dias. A barreira sustenta a margem bruta, não a expansão do EBITDA.

**3. A Dahua é 36% das compras, tem R$524 mi a receber da Intelbras e um acordo de prioridade/exclusividade que vence em dez/2028.**
- *Mecanismo:* existe dependência mútua: a Intelbras tem exclusividade da marca Dahua no Brasil; a Dahua tem prioridade de venda e a tecnologia. O poder de barganha migra para a Dahua com a renegociação anual, a saída do capital e a subsidiária local, cujo administrador senta no conselho da Intelbras.
- *Consequência:* há um risco de evento concentrado sobre a margem de Segurança, que gera 67,5% do lucro bruto. A renovação de 2028 é a principal data da tese.

**4. Segurança gera 67,5% do lucro bruto, mas sua margem caiu de ~39% (2020) para 33,2% (2025).**
- *Mecanismo:* deflação tecnológica, câmbio com repasse defasado e preço ancorado na tecnologia global ("o mercado define os preços"). Em 2025, a melhora de mix (+0,6 p.p.) foi anulada pela queda de margem dentro dos segmentos (−1,3 p.p.).
- *Consequência:* crescer em Segurança não garante crescer em lucro bruto. A margem do 2T26 (33,1%) tem parte cíclica, segundo a própria companhia.

**5. A margem EBIT ficou estável (10–12%), mas o giro do capital caiu de 2,9x para 1,6x (2019–25). O capital de giro (R$1,6 bi) supera o imobilizado + intangível (R$1,25 bi).**
- *Mecanismo:* o modelo faz da Intelbras o estoque regulador e o financiador do canal. Com mais SKUs, importação longa e proteção de preço, o capital cresce mais rápido que o lucro.
- *Consequência:* o ROIC (15% → 18,8% no LTM 2T26) depende mais do ciclo de caixa do que da margem. *Estimativa:* 10 dias a menos de ciclo liberam R$86–125 mi, ou +0,6 a 0,9 p.p. de ROIC pré-IR.

---

## Visualizações recomendadas

| # | Gráfico | Mensagem a provar | Variáveis | Fonte | Formato |
|---|---|---|---|---|---|
| 1 | **Mix de receita por segmento + crescimento** | "Segurança é o motor: 61% da receita e 67,5% do lucro bruto; Energia e TIC vendem mais do que lucram" | Receita por segmento 2019–2025 (e 1S26); lucro bruto por segmento 2024–25; margem bruta por segmento | Planilha (Informações por Segmento); FRE 1.3, p.15–16 | Barras empilhadas de receita + par de barras 100% "receita × lucro bruto 2025" ao lado, com a cor principal só em Segurança |
| 2 | **Cadeia Intelbras → distribuidores → instaladores → usuário** | "O distribuidor agrega, o instalador especifica, a Intelbras financia e garante o estoque" | 68/16/16; ~500 pontos; 90 mil instaladores; R$2,8 mil/mês por revendedor (est.); prazo de recebimento ~100 dias; estoque ~144 dias; obrigações e benefícios do Programa de Canais | FRE 1.2, p.3 e p.7; FRE 1.4.b, p.22–23; Planilha | Fluxograma horizontal com largura proporcional ao % de vendas; setas anotadas com dinheiro, crédito e dados de sell-out |
| 3 | **Mix de canais** | "A distribuição ainda domina, mas varejo e projetos ganham peso, e esses compradores comparam preço" | % por canal 2020 vs 2025; % de distribuidores no Mais Verde (~95%) | BTG21 s.9 (dado do FRE 2021); FRE 1.4.b, p.22 | Duas barras 100% lado a lado + destaque "95% dos distribuidores com exclusividade voluntária" |
| 4 | **Flywheel testado** | "O loop curto (instalador → disponibilidade → marca) gira; o loop longo (escala → custo → novas categorias) não aparece nos números" | Os 8 elos com status da evidência; ROIC 31% → 15% → 18,8%; SG&A/receita | Esta análise; Planilha; FRE | Diagrama circular, elos coloridos por status, com painel lateral "loop curto × loop longo" |

---

### Fontes externas (validação)

- FilingReader, 15/08/2025: Dahua autoriza venda de 7,56% da Intelbras — https://filingreader.com/news-wire/shenzhen/2025-08-15/dahua-technology-to-sell-756-stake-in-intelbras
- Nord Research (28,6% das compras com a Dahua em 2021, citando o FRE) — https://www.nordinvestimentos.com.br/blog/intelbras-intb3-por-que-estamos-confiantes/
- Teletime, 27/04/2026: investimento de R$200 mi em Manaus — https://teletime.com.br/27/04/2026/intelbras-vai-investir-r-200-milhoes-em-nova-fabrica-em-manaus/

*Análise de modelo de negócios; não é recomendação de investimento.*
