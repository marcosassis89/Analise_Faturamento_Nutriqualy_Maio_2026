# RELATÓRIO DE ANÁLISE DE DIVERGÊNCIA DE FATURAMENTO

**Empresa:** Nutriqualy Nutrição Hospitalar Eireli  
**Período Analisado:** 01/05/2026 a 31/05/2026  
**Data de Emissão:** 22/06/2026  
**Responsável:** MARCOS ASSIS (assisxp)

---

## 1. OBJETIVO

Este relatório tem como objetivo apresentar e justificar as divergências identificadas entre os valores de faturamento apresentados pela **Ponte de Comando** e pelo **Relatório de Vendas por Pedido** no período de maio de 2026. A análise visa esclarecer as diferenças e orientar a correta interpretação dos relatórios gerenciais.

---

## 2. METODOLOGIA

Foram extraídos os seguintes documentos do sistema:

- **Ponte de Comando** (Painel de Faturamento) – valor total de pedidos no período.
- **Relatório de Vendas por Pedido** – consulta parametrizada por pedido, com detalhamento de valores brutos, descontos, líquidos e fretes.
- **Relatório de Comissão de Vendedores** – para conferência do total de vendas e devoluções.
- **Planilha de Comparação** – contendo a conciliação pedido a pedido entre os valores da Ponte de Comando e do Relatório de Vendas.

A comparação foi realizada alinhando os mesmos 251 pedidos (documentos) do período, conforme critério de pesquisa definido (unidade: Nutriqualy Nutrição Hospitalar Eireli).

---

## 3. RESULTADOS DA ANÁLISE

### 3.1 Valores Apurados

| Indicador | Ponte de Comando | Relatório de Vendas por Pedido | Diferença |
|-----------|------------------|--------------------------------|-----------|
| **Faturamento Total (Pedidos)** | R$ 192.318,86 | R$ 191.090,67 | R$ 1.228,19 |
| **Total de Pedidos** | 251 | 251 | 0 |
| **Valor de Devoluções** | Não abatido | R$ 1.637,14 | – |
| **Total Líquido (Vendas – Devoluções)** | – | R$ 189.453,53 | – |

> *Observação:* O Relatório de Vendas por Pedido apresenta o valor líquido das vendas (R$ 191.090,67) e, separadamente, o total devolvido (R$ 1.637,14), resultando no total líquido de R$ 189.453,53. A Ponte de Comando, por sua vez, exibe o faturamento bruto dos pedidos, sem abater devoluções.

### 3.2 Composição da Diferença de R$ 1.228,19

A diferença entre os dois relatórios é explicada por itens que **não** compõem o valor líquido da venda de produtos, mas que são incluídos no faturamento total da Ponte de Comando:

| Componente | Valor (R$) |
|------------|------------|
| **Fretes** (valor do frete cobrado nas notas) | R$ 330,01 |
| **Outras Despesas** (taxas, ajustes manuais, despesas diversas) e **Alterações no Financeiro** | R$ 898,18 |
| **Total da Diferença** | **R$ 1.228,19** |

A soma desses valores (R$ 330,01 + R$ 898,18 = R$ 1.228,19) coincide exatamente com a diferença apurada (R$ 192.318,86 – R$ 191.090,67 = R$ 1.228,19), comprovando a consistência dos dados.

---

## 4. DETALHAMENTO DOS ITENS QUE COMPÕEM A DIFERENÇA

### 4.1 Pedidos com Frete (total de R$ 330,01)

Os seguintes pedidos apresentam valor de frete incluso no faturamento da Ponte de Comando, mas que não são considerados no valor líquido do Relatório de Vendas por Pedido:

| Nº do Pedido | Valor do Frete (R$) |
|--------------|----------------------|
| 19635        | 30,00                |
| 19637        | 40,01                |
| 19645        | 7,00                 |
| 19657        | 39,99                |
| 19685        | 30,00                |
| 19688        | 30,00                |
| 19736        | 90,01                |
| 19806        | 7,00                 |
| 19821        | 7,00                 |
| 19829        | 30,00                |
| 19890        | 12,00                |
| 19927        | 7,00                 |
| **Total**    | **330,01**           |

### 4.2 Pedidos com Outras Despesas e Alterações no Financeiro (total de R$ 898,18)

Foram identificados, por amostragem, pedidos que tiveram lançamentos manuais de outras despesas no pedido ou alterações no valor financeiro do pedido. Esses valores são incluídos no faturamento da Ponte de Comando, mas não refletem o valor líquido da venda de produtos. A lista completa desses pedidos é apresentada abaixo, sendo que a soma dos valores adicionados totaliza R$ 898,18.

**Pedidos com outras despesas:**

19640, 19642, 19643, 19649, 19650, 19653, 19663, 19673, 19676, 19681, 19687, 19695, 19702, 19703, 19705, 19708, 19709, 19712, 19713, 19714, 19719, 19720, 19725, 19731, 19735, 19746, 19749, 19751, 19752, 19753, 19757, 19759, 19761, 19769, 19771, 19773, 19776, 19783, 19798, 19800, 19807, 19810, 19812, 19817, 19823, 19827, 19830, 19837, 19838, 19839, 19845, 19849, 19850, 19851, 19852, 19860, 19862, 19863, 19868, 19870, 19871, 19881, 19889, 19895, 19898, 19900, 19901, 19902, 19904, 19905, 19906, 19909, 19914, 19915, 19926.

**Pedidos com alteração no financeiro (valores ajustados):**  
19811 e 19916.

---

## 5. VALIDAÇÃO CRUZADA – RELATÓRIO DE COMISSÃO DE VENDEDORES

O Relatório de Comissão de Vendedores (emitido separadamente) apresenta os seguintes totais:

- **Total de Vendas (bruto, sem devoluções):** R$ 191.090,67  
- **Total de Devoluções:** R$ 1.637,14  
- **Total Líquido:** R$ 189.453,53  

Esses valores são **idênticos** aos do Relatório de Vendas por Pedido, confirmando que a base de cálculo da comissão está correta e alinhada com o relatório de vendas, e não com a Ponte de Comando (que inclui fretes e outras despesas).

---

## 6. CONCLUSÃO

A divergência observada entre o **Faturamento da Ponte de Comando (R$ 192.318,86)** e o **Total do Relatório de Vendas por Pedido (R$ 191.090,67)** é decorrente exclusivamente da inclusão, na Ponte de Comando, de:

- **Fretes** (R$ 330,01);  
- **Outras despesas e ajustes financeiros** (R$ 898,18).

Esses valores não compõem o valor líquido da venda de produtos, motivo pelo qual não aparecem no Relatório de Vendas por Pedido. **Não há erro ou inconsistência nos sistemas**; trata-se de diferentes perspectivas de apuração:

- A **Ponte de Comando** reflete o faturamento total bruto, incluindo todos os acréscimos incidentes sobre o pedido (frete, outras despesas).
- O **Relatório de Vendas por Pedido** apresenta o valor líquido da mercadoria, sem os acréscimos, sendo a base adequada para cálculo de comissões e análise de rentabilidade de produtos.

**Recomenda-se** que, para fins de conciliação financeira e apuração de comissões, seja sempre utilizado o **Relatório de Vendas por Pedido** com a consulta parametrizada por **Pedido** (e não por Nota Fiscal), a fim de evitar a inclusão de notas de períodos anteriores e garantir a aderência ao período desejado.

---

## 7. ANEXOS

- Relatório da Ponte de Comando (faturamento de pedidos – maio/2026).
- Relatório de Vendas por Pedido (PDF – maio/2026).
- Planilha de Comparação detalhada (Ponte de Comando vs. Relatório de Vendas).
- Print da Comissão de Vendedores (maio/2026).

---

**Elaborado por:** MARCOS ASSIS (assisxp)  
**Data:** 22/06/2026  

---

*Este relatório visa esclarecer as diferenças apontadas e fornecer subsídios para a correta interpretação dos indicadores gerenciais da empresa.*

---
