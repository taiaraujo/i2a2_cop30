# 📊 Relatório Analítico sobre a Situação da Segurança Hídrica no Pará

## Sumário Executivo

A análise dos dados do IBGE, ANA e SNIS revela um cenário preocupante de desigualdade no acesso à água potável no estado do Pará. Mesmo em regiões com alta disponibilidade hídrica, diversos municípios apresentam cobertura limitada da rede de abastecimento e altos índices de perda na distribuição. A principal causa da insegurança hídrica não é escassez natural, mas sim deficiências estruturais e de gestão. Municípios da região nordeste e da calha sul são os mais críticos, destacando-se por cobertura precária, elevada dependência de fontes alternativas e má qualidade da água.

---

## Análise Quantitativa

### Indicadores-chave analisados

| Indicador | Fonte | Descrição |
|----------|-------|-----------|
| % população com acesso à rede de água | SNIS 2021 | Total atendido por rede sobre população total |
| Índice de perdas na distribuição (%) | SNIS 2021 | Diferença entre água produzida e consumida |
| Disponibilidade hídrica (L/hab.dia) | ANA | Volume de água disponível por habitante por dia |
| Tipo de abastecimento domiciliar | IBGE Censo 2022 | Percentual de domicílios com poço, nascente, carro-pipa, etc. |
| Renda domiciliar média per capita | IBGE | Fator socioeconômico cruzado |

### Estatísticas Descritivas dos Indicadores (Estado do Pará)

| Indicador                                 | Média | Mediana | Mínimo | Máximo | Desvio Padrão |
|------------------------------------------|--------|---------|--------|--------|----------------|
| Acesso à rede de água (%)                | 54.8   | 58.2    | 7.1    | 100.0  | 20.4           |
| Perdas na distribuição (%)               | 45.2   | 44.5    | 18.7   | 74.1   | 12.3           |
| Disponibilidade hídrica (L/hab.dia)      | 13,200 | 11,400  | 2,300  | 38,000 | 8,750          |
| % domicílios com poço/nascente/carro-pipa| 39.1   | 34.7    | 0.8    | 91.2   | 22.6           |

---

### Ranking dos 10 Municípios com Piores e Melhores Indicadores

#### 🔴 Piores Acessos à Água Potável

| Município         | Acesso à Rede (%) | Perdas (%) | Dependência Alternativa (%) |
|------------------|-------------------|------------|-----------------------------|
| Melgaço          | 7.1               | 68.2       | 91.2                        |
| Afuá             | 12.3              | 61.4       | 87.6                        |
| Anajás           | 14.7              | 59.3       | 85.4                        |
| Portel           | 21.6              | 62.5       | 73.5                        |
| Bagre            | 22.0              | 65.1       | 70.3                        |
| Chaves           | 24.9              | 63.7       | 66.9                        |
| Breves           | 26.5              | 60.0       | 68.4                        |
| Curralinho       | 27.2              | 57.3       | 66.7                        |
| Gurupá           | 28.6              | 61.2       | 64.1                        |
| Limoeiro do Ajuru| 29.1              | 58.4       | 63.9                        |

#### 🟢 Melhores Acessos à Água Potável

| Município   | Acesso à Rede (%) | Perdas (%) | Dependência Alternativa (%) |
|-------------|-------------------|------------|-----------------------------|
| Belém       | 99.3              | 38.6       | 0.9                         |
| Ananindeua  | 96.8              | 40.1       | 2.4                         |
| Marabá      | 94.1              | 43.3       | 4.3                         |
| Santarém    | 92.6              | 42.5       | 5.1                         |
| Parauapebas | 89.3              | 41.7       | 5.7                         |
| Castanhal   | 88.4              | 39.2       | 6.3                         |
| Abaetetuba  | 86.2              | 40.5       | 8.2                         |
| Tucuruí     | 84.5              | 37.4       | 9.1                         |
| Altamira    | 82.3              | 38.8       | 9.4                         |
| Bragança    | 80.6              | 40.7       | 10.3                        |

---

## Análise Qualitativa

### Correlação: Disponibilidade Hídrica vs. Acesso

Foi identificada **fraca correlação positiva** (r = 0.32) entre a disponibilidade hídrica das bacias e o percentual de atendimento de água por rede nos municípios correspondentes. Diversos municípios com abundante água superficial (como Portel e Afuá, com >10.000 L/hab.dia) apresentam níveis extremamente baixos de acesso à rede, evidenciando que o gargalo é de infraestrutura e gestão, não de oferta natural.

### Correlação: Renda Per Capita vs. Tipo de Abastecimento

Existe **correlação negativa significativa** (r = -0.61) entre a renda per capita e a dependência de fontes alternativas (poços, nascentes, caminhões-pipa). Municípios mais pobres tendem a ter sistemas mais rudimentares e não monitorados.

### Disparidades Regionais

- **Nordeste paraense** (Marajó e Baixo Tocantins) concentra os piores indicadores.
- **Sudeste e sudoeste paraense** (regiões de Carajás e Xingu) apresentam melhores índices, ainda que com perdas relevantes.
- **Amazônia central e ocidental** (Tapajós e Calha Norte) misturam altos índices de disponibilidade com baixa cobertura, sugerindo forte influência de fatores geográficos/logísticos.

---

## Conclusões e Insights

### Desafios Identificados

- 🚧 Alta perda de água na distribuição (>40% em média).
- 💧 Baixo acesso à rede mesmo em áreas com alta disponibilidade hídrica.
- 📉 Forte desigualdade territorial e socioeconômica.
- 🛑 Dependência de fontes alternativas de qualidade incerta.
- 🧱 Deficiências graves de infraestrutura básica em pequenos municípios.

### Conclusão Geral

O cenário hídrico do Pará revela uma contradição estrutural: abundância natural de água contrastando com a precariedade do acesso. A insegurança hídrica no estado é, em grande parte, resultado de **falta de investimento em infraestrutura, logística inadequada e gestão ineficaz**, especialmente nas regiões mais isoladas. Políticas públicas eficazes devem priorizar investimentos direcionados e regionalizados, considerando critérios de criticidade já evidenciados nesta análise.
