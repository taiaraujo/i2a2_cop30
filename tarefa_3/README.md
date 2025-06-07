# Desafio 2 - Método PACEF: Análise e Soluções para a Escassez Hídrica no Pará

Este repositório documenta o processo de engenharia de prompts desenvolvido para o **Desafio 2** do curso "IA para Projetos Sustentáveis". Nosso foco foi aplicar Modelos de Linguagem de Grande Escala (LLMs) para analisar e propor soluções para um problema socioambiental crucial: **a escassez de água potável em comunidades no interior do Pará**.

---

## 🎯 Objetivo do Projeto

O principal objetivo do projeto foi capacitar LLMs a:
* Identificar padrões relevantes sobre a escassez de água.
* Priorizar as regiões mais afetadas.
* Propor soluções de intervenção baseadas em Inteligência Artificial para mitigar o problema.

---

## 🛠️ Metodologia: Aplicação do Método P.A.C.E.F.

Utilizamos o **método P.A.C.E.F. (Papel, Ação, Contexto, Exemplo, Forma)** para criar e otimizar iterativamente os prompts. Esse processo foi essencial para garantir a clareza e precisão das instruções para a IA.

Para validar a robustez dos prompts, os executamos em três plataformas de LLM diferentes:
* **Google AI Studio** com Gemini 2.5 Flash Preview 05-20 (com Google Search ativado).
* **ChatGPT** (com os plugins Wolfram Alpha e SciSpace).
* **Anthropic** com Claude 3.5 Haiku.

---

## 🔄 Estrutura dos Prompts para Análise (Cadeia de Prompts)

Dividimos a análise em uma cadeia de três prompts principais, cada um com um papel distinto e interconectado, todos seguindo a estrutura P.A.C.E.F.:

### 1. Prompt Final 1 - O Analista de Dados

* **Papel:** Especialista em análise de dados e estatística, focado em saneamento básico e recursos hídricos.
* **Ação:** Realizar uma análise estatística detalhada de dados do IBGE, ANA e SNIS sobre o acesso à água potável no Pará. Isso inclui identificar indicadores, calcular estatísticas descritivas, cruzar dados para correlações e listar municípios críticos.
* **Contexto:** Criar uma base factual e objetiva para estudos de segurança hídrica e embasar políticas públicas.
* **Fontes Utilizadas:** Links diretos para Panorama Censo 2022 (IBGE), Cidades IBGE - Pará Panorama, Dados Abertos ANA, SNIS Geral e seus diagnósticos específicos (Água e Esgotos 2021, Relatório SINISA 2024, Diagnóstico Temático Gestão Técnica de Esgoto 2023), além do Imazon para contexto.
* **Resultados:** Os relatórios gerados por este prompt estão disponíveis na pasta `relatorios_prompt_1_analise_dados/`.

### 2. Prompt Final 2 - O Pesquisador

* **Papel:** Pesquisador socioambiental sênior com expertise em saneamento na Amazônia.
* **Ação:** Revisar criticamente os relatórios do "Analista de Dados" (Prompt 1) e, com pesquisa adicional, identificar padrões de escassez de água, priorizar regiões mais afetadas e explorar causas e impactos socioambientais.
* **Contexto:** Aprofundar a compreensão sobre a falta de acesso à água potável no Pará, considerando demografia, infraestrutura, disponibilidade e qualidade hídrica, e suas interconexões com saúde e desenvolvimento.
* **Fontes Utilizadas:** Os relatórios do Prompt 1 (disponíveis neste repositório) e pesquisa adicional em estudos de caso, notícias, documentos de ONGs e artigos científicos.
* **Resultados:** Os relatórios de pesquisa e priorização estão disponíveis na pasta `relatorios_prompt_2_pesquisa/`.

### 3. Prompt Final 3 - O Revisor e Propositor de Soluções

* **Papel:** Consultor estratégico em inovação e políticas públicas, especializado em IA para desafios socioambientais na Amazônia.
* **Ação:** Revisar e validar a análise de padrões e a priorização de regiões do "Pesquisador" (Prompt 2). Com base nesses resultados e conhecimento em IA, propor soluções de intervenção concretas e inovadoras para mitigar a escassez de água no Pará.
* **Contexto:** Traduzir insights em ações práticas e escaláveis usando o potencial da IA, considerando desafios logísticos, ambientais e sociais da Amazônia.
* **Fontes Utilizadas:** Os relatórios do Prompt 2 (disponíveis neste repositório) e conhecimento sobre IA e fontes de dados públicos/tecnologias aplicáveis (Programas Landsat e Copernicus, SNIRH, INMET, SIAGAS, Ministério da Saúde, WhatsApp Business API, modelos de ML, etc.).
* **Resultados:** Os relatórios com sugestões de intervenção estão disponíveis na pasta `relatorios_prompt_3_revisao_proposta_ia/`.

---

## 💡 Aprendizados e Insights

Este projeto destacou a importância da **engenharia de prompts como ferramenta estratégica** para direcionar LLMs na resolução de problemas complexos. Um aprendizado significativo foi a necessidade de **inputs estruturados e da inclusão direta de fontes de dados** para garantir a precisão das respostas, evitando informações simuladas. A **cadeia de prompts** mostrou-se um modelo eficaz para desmembrar problemas multifacetados em etapas lógicas, maximizando a utilidade das saídas dos LLMs.

---

## 📁 Estrutura do Repositório

* `tarefa_3/`: Pasta raiz do desafio.
    * `relatorios_prompt_1_analise_dados/`: Relatórios gerados pelo Prompt 1.
    * `relatorios_prompt_2_pesquisa/`: Relatórios gerados pelo Prompt 2.
    * `relatorios_prompt_3_revisao_proposta_ia/`: Relatórios gerados pelo Prompt 3.
    * `README.md`: Este arquivo.
