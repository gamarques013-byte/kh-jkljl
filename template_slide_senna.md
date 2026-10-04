# Template visual de referência: slide "NVIDIA at a Glance" (case Senna)

*Medidas extraídas do PDF original: 960 × 540 pt, 16:9 (13,33 × 7,5 pol). Fonte Calibri. Na Intelbras, troca-se o verde NVIDIA pelo verde da marca e mantém-se o resto.*

## Anatomia

```
┌──┬──────────────────────────────────────────────────────────────────────┐
│▌ │ TÍTULO CURTO (verde escuro, 32pt bold)                               │
│N │ Subtítulo-tese em uma linha (cinza 7F7F7F, 18pt)                     │
│A ├───────────────────────────────────┬──────────────────────────────────┤
│V │ I. Microheadline argumentativa    │ II. Microheadline argumentativa  │
│  │ ───────────────(regra verde)───── │ ───────────────(regra verde)──── │
│S │      legenda do gráfico (itálico) │      legenda do gráfico (itálico)│
│E │      [visual]                     │      [visual]                    │
│Ç ├───────────────────────────────────┼──────────────────────────────────┤
│Õ │ III. Microheadline                │ IV. Microheadline                │
│E │ ─────────────────────────────     │ ─────────────────────────────    │
│S │      [visual]                     │      [visual]                    │
│  │                                   │                                  │
│3 │ ════════════════════ linha verde de rodapé ═══════════════════  [logo]│
└──┴ Source: …  (7pt cinza)                                               ┘
```

## Grid (polegadas, origem no canto superior esquerdo)

| Elemento | x | y | w | h | Estilo |
|---|---|---|---|---|---|
| **Barra lateral de navegação** | 0 | 0 | 0,30 | 7,50 | Preto `0D0D0D` |
| Abas da barra lateral (texto rotacionado 270°) | 0,03 | por seção | 0,24 | ~0,9 cada | 11pt bold; inativas em cinza `A6A6A6`. Ativa: caixa branca arredondada, texto verde da marca e um fio verde diagonal saindo da aba |
| Nº da página | 0,08 | 7,25 | — | — | 8pt, cinza, dentro da barra |
| **Título** | 0,41 | 0,03 | 12,8 | 0,42 | Calibri Bold 32pt, verde escuro (`5B910B` no original). **Curto** |
| **Subtítulo** | 0,41 | 0,44 | 12,8 | 0,26 | Calibri 18pt, cinza `7F7F7F`, uma linha. **É aqui que fica a tese/conclusão** |
| Coluna esquerda | 0,41 → 6,71 | | 6,30 | | |
| Coluna direita | 7,00 → 13,25 | | 6,25 | | Espaço entre colunas ≈ 0,3 |
| Microheadline I e II | coluna | 0,77 | coluna | 0,18 | Calibri Bold 12pt, preto, prefixo "I." "II." |
| Regra sob a microheadline | coluna | 0,95 | coluna | 1pt | Verde da marca, largura total da coluna |
| Legenda do gráfico | centro da coluna | 1,05 | | 0,18 | Calibri Italic 11pt, cinza `7F7F7F`, com unidade: "(US$ billion)", "(%)" |
| Legenda de séries | centro | 1,30 | | 0,15 | 10pt, marcadores quadrados; fica no topo, nunca na lateral |
| Área do visual I e II | coluna | 1,45 | | 2,30 | |
| Microheadline III e IV | coluna | 3,98 | | 0,18 | Idem |
| Regra III e IV | coluna | 4,14 | | 1pt | Idem |
| Legenda III e IV | centro | 4,25 | | | Idem |
| Área do visual III e IV | coluna | 4,55 | | 2,50 | |
| **Linha de rodapé** | 0,36 | 7,22 | 12,40 | 1,5pt | Verde da marca |
| Fonte | 0,41 | 7,35 | 9,0 | 0,12 | "Source: …", 7pt, cinza |
| Logo | 12,85 | 7,08 | 0,35 | 0,25 | Canto inferior direito |

## Paleta (só verde, preto e cinza)

| Uso | Original NVIDIA | Intelbras (equivalente) |
|---|---|---|
| Série principal / "o que importa" | Preto `000000` (Data Center) | Preto `000000` |
| Verde da marca (barras, regras, nomes) | `6DB90B` | `009B4E` |
| Verde escuro (título, 2ª série) | `5B910B` / `1A7A1F` | `006B35` |
| Verde médio (3ª série, bordas tracejadas) | `298A3B` | `2E8B57` |
| Verde claro (4ª série) | `7FD80F` | `7CC79A` |
| Texto secundário | `7F7F7F` | `7F7F7F` |
| Fundo de destaque | `EEEEEE` | `EEEEEE` |
| Barra lateral | `0D0D0D` | `0D0D0D` |

## Gramática dos visuais (o que copiar)

1. **Sem eixo Y e sem gridlines.** Rótulo de valor direto na barra ou no ponto. Só a linha de base do eixo X, em cinza claro.
2. **Barras empilhadas:**
   - valor de cada segmento **dentro** da barra (branco no preto, preto no verde);
   - **total acima** da barra (12pt);
   - a série principal fica embaixo, em preto.
3. **Linhas:**
   - rótulos como **caixinhas preenchidas na cor da série**, com texto branco (preto quando o fundo é claro);
   - marcadores ocultos;
   - linha de 2,25pt.
4. **Barras simples:** uma só cor (verde da marca), valor em cima, categoria embaixo, ordenadas da maior para a menor.
5. **Anotações analíticas no gráfico:**
   - **Caixa de destaque:** retângulo cinza `EEEEEE` com borda **pontilhada verde**, cobrindo o período relevante, e uma frase de 2 linhas acima ("Data center revenue surpasses gaming revenue").
   - **Colchete de CAGR:** linha tracejada cinza saindo do topo da 1ª barra, subindo e indo até a última, com "CAGR₂₀₁₈₋₂₀₂₄: 41,1%" em itálico cinza.
6. **Cartões (quadrante qualitativo):**
   - grade 2×2 de caixas com **borda tracejada verde-média** e sem preenchimento;
   - imagem à esquerda;
   - à direita, centralizado: nome em verde bold 14pt; depois 2–3 linhas bold 11pt (preço, ano); por fim a categoria em regular.
7. **Hierarquia de cor:** o "núcleo" da tese aparece em **preto** (Data Center); a marca, em tons de verde; nunca outra cor.

## Diferenças em relação ao deck anterior (`intelbras_modelo_negocios_FRE2026.pptx`)

| Elemento | Deck anterior | Template Senna |
|---|---|---|
| Navegação | Sem barra lateral | **Barra preta à esquerda com abas de seção** (ex.: Intelbras · Setor · Moat · Financeiro · Valuation · Cenários) |
| Título | Frase-conclusão longa, preto, 26pt | **Título curto em verde, 32pt**; a conclusão vai no **subtítulo cinza** |
| Microheadline | Bold com número romano | Igual, **mais a regra verde sob cada uma** |
| Legenda do gráfico | Ausente ou no corpo | **Itálico cinza centralizado, com unidade** |
| Rodapé | "SO WHAT" + fonte | **Linha verde + fonte 7pt + nº da página + logo** (o "so what" sai do slide e fica no subtítulo) |
| Gráficos | Nativos, com eixo | Sem eixo, rótulos diretos, caixas de destaque e colchete de CAGR |

## Ajuste ao padrão salvo em `instrucoes_apresentacao_equity_research.md`

O template é compatível com as instruções, com uma decisão de layout:
- o **título argumentativo** pedido nas instruções passa a ser o **subtítulo** (frase-conclusão de uma linha);
- o título vira um rótulo curto, como no case ("Intelbras at a Glance", "Incentivos fiscais").
