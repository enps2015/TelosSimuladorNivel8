# Análise de Dados da Imobiliária Bezerra com Power BI

## 📚 Descrição do Projeto

Este projeto, parte da **Trilha Formação em Dados**, teve como objetivo desenvolver um dashboard interativo no Power BI para a Imobiliária Bezerra. O foco foi em analisar dados de vendas, imóveis e mercado imobiliário,  fornecendo insights acionáveis para melhorar a estratégia de vendas e o desempenho da empresa.  O dashboard foi construído com foco em clareza visual, storytelling e interatividade, utilizando as melhores práticas de design de dashboards.

## 🚀 Funcionalidades

- **Dashboard Interativo:**  Duas páginas com navegação intuitiva e filtros para explorar os dados.
- **Visualizações Claras:**  Gráficos e tabelas que comunicam os insights de forma eficaz.
- **Métricas e KPIs Relevantes:**  Acompanhamento do desempenho de vendas,  análise de mercado e identificação de oportunidades.
- **Storytelling com Dados:**  Narrativa que guia o usuário através dos insights, respondendo às perguntas de negócio.
- **Modelagem de Dados Robusta:** Esquema dimensional com tabelas fato e dimensão, otimizado para performance.
- **Fórmulas DAX Eficientes:**  Cálculos precisos e otimizados para as métricas e KPIs.


## 🛠️ Tecnologias Utilizadas

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query


## 📂 Estrutura do Projeto

- **/Dashboards_Imobiliaria_Bezerra.pbix:** Arquivo do dashboard do Power BI. ([link para download/visualização](https://app.powerbi.com/links/KoIuyJjNhQ?ctid=51a5b007-492b-4d5f-bbc1-dc9fb6fec249&pbi_source=linkShare&bookmarkGuid=05543295-9adf-4a1d-9f64-83483be73270))
- **/imagens:**  Imagens do dashboard e do modelo de dados.
- **README.md:**  Documentação do projeto.

## 📊 Análises e Insights

**Página 1: Desempenho de Vendas:**

* **KPIs:** Imóveis Vendidos, Imóveis Disponíveis, Comissão Média, Taxa de Conversão.
* **Gráficos:**
    * Tendência de vendas ao longo do tempo.
    * Top vendedores (ranking).
    * Matriz com vendas por tipo de imóvel, cidade e trimestre.
* **Filtros:** Vendedor, Data da Venda, Tipo de Imóvel, Cidade, Bairro.

**Página 2: Análise de Mercado e Imóveis:**

* **KPIs:**  Valor Total dos Imóveis Disponíveis, Valor Médio por Metro Quadrado.
* **Gráficos:**
    * Mapa de Imóveis Disponíveis.
    * Imóveis por Tipo e Cidade.
    * Valor Médio por Bairro e Tipo de Imóvel.
    * Valor Total dos Imóveis Disponíveis por Cidade (Gráfico de Rosca).
* **Filtros:** Os mesmos da página 1

## 💡 Desafios e Soluções

**Desafio:** Calcular o Valor Médio dos Imóveis por Bairro,  respeitando os filtros de outros campos.

**Solução:** Utilização da função `ALLSELECTED`  na medida DAX,  para remover os filtros da hierarquia de localização, mas manter o contexto de outros filtros.

**Desafio:**  Visualizar a relação entre valor do imóvel, metros quadrados, tipo de imóvel e bairro de forma clara.

**Solução:**  Substituição do gráfico de dispersão por um Gráfico de Rosca, que oferece uma visualização mais clara dos dados.

## ✨ Lições Aprendidas

- Aprimoramento das habilidades em Power BI, DAX e Power Query.
- Importância da modelagem de dados para a criação de dashboards eficientes.
- Aplicação de storytelling com dados para comunicar insights de forma eficaz.
- Design de dashboards com foco na clareza visual e usabilidade.

## 🚀 Próximos Passos

- Implementar drillthrough nos gráficos para análises mais detalhadas.
- Adicionar recursos de interatividade, como tooltips mais ricas.
- Explorar a integração com outras fontes de dados.


---

**Desenvolvido por:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eric-np-santos/) Eric Pimentel 

**Que a Força dos Dados esteja com você! 🚀 ✨** 
