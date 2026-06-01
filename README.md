# Portifólio de Análise de dados e BI- Luan Frederico

Olá, bem-vindo ao meu portfólio de projetos de **Análise de Dados!** Aqui, você encontrará estudos sobre problemas reais e/ou projetos acadêmicos envolvendo **SQL, Power BI, Python, R e Excel/Google Sheets**, com foco em **tratamento, organização, análise e interpretação de dados, além da criação de dashboards interativos e geração de insights estratégicos.** Explore os projetos e descubra como análise de dados pode transformar informações em decisões valiosas e impactantes!

## Case 1: Análise Estratégica de Vendas (SQL)

Este projeto simula um cenário real de uma empresa do setor de varejo que busca compreender seu desempenho comercial e financeiro a partir da análise estruturada de dados. Utilizando a base Contoso Retail Data Warehouse, o estudo tem como foco identificar padrões de **receita, lucratividade, comportamento de clientes e performance regional** para apoiar decisões estratégicas.

### Objetivos principais

- Analisar receita, custos, lucro e margem por produto, categoria e subcategoria

- Avaliar desempenho de vendas ao longo do tempo (crescimento e sazonalidade)

- Identificar padrões de consumo e concentração de receita por cliente

- Comparar desempenho entre regiões, lojas e países

- **Objetivo principal:** Gerar insights estratégicos para otimização comercial

### Principais etapas

- Consultas analíticas em SQL Server, utilizando:

  - SELECT, WHERE, GROUP BY, HAVING

  - CASE WHEN para segmentações estratégicas

  - JOINs entre tabelas fato e dimensões (modelo estrela)

  - CTEs para organização lógica das análises

- Análises por dimensões estratégicas:

  - **Produtos:** Faturamento, custo, lucro e margem por categoria e produto; identificação de produtos com alto volume e baixa margem.

  - **Clientes:** Ticket médio, frequência de compra e concentração de receita.

  - **Regional:** Comparação de desempenho entre regiões e lojas e identificação de mercados com maior potencial.

### Resultados esperados

- Identificação das principais fontes de receita e lucro por produto, categoria e subscategoria, perfil de cliente e região.

- Evidências para direcionamento de estratégias comerciais

- Base analítica estruturada para apoio à tomada de decisão orientada por dados

[Ver Projeto Completo](https://github.com/Luan-Frederico/Analise_vendas)

## Case 2: Análise de Vendas e Inteligência de dados (Power BI)

Este projeto tem como objetivo desenvolver uma solução completa de **Business Intelligence (BI)** para avaliar o **desempenho comercial**, a **eficiência de faturamento** e o **comportamento de compra** de uma carteira de clientes ativos. A análise e a estruturação dos dados foram conduzidas integralmente no **Power BI**.  
O foco do projeto foi aplicar lógica analítica, modelagem de dados e engenharia de fórmulas DAX para transformar tabelas transacionais brutas e descentralizadas em um **painel altamente interativo**. A solução desenvolvida visa **eliminar pontos cegos operacionais** e fornecer **diagnósticos rápidos e precisos** para dar **suporte estratégico à tomada de decisão**.

### Objetivos principais

- Consolidar e automatizar o acompanhamento dos **KPI's mestres** — Faturamento Total, Ticket Médio, Base de Clientes e Volume de Vendas — para fornecer à liderança um diagnóstico imediato e centralizado da performance organizacional.

- Avaliar a **evolução temporal do faturamento** (visão mensal) e identificar os principais pilares de receita através do ranking de performance por clientes e vendedores.

- Mapear a representatividade das receitas por categorias, subcategorias e produtos, permitindo identificar os itens que lideram o volume de vendas e sustentam o faturamento da operação.

- Utilizar métricas avançadas e visuais de análise profunda para identificar tendências, correlações e anomalias entre volume e receita, e rastrear o fluxo granular de cada transação (TKM) diagnóstico mais preciso.

- **Objetivo Principal:** Atuar como o pilar central da solução, convertendo o processamento analítico em recomendações práticas para mitigar gargalos operacionais, otimizar a rentabilidade da carteira e fundamentar escolhas táticas focadas no crescimento sustentável do faturamento, visando oferecer suporte estratégico à decisão do negócio.

### Principais etapas

- Desenvolvimento analítico no Power BI, utilizando:

    - **Power Query** para extração, limpeza e transformação de dados (ETL).
  
    - Relacionamentos e Modelagem Star Schema (Modelo Estrela) de 1:N entre tabelas fato e dimensões (Clientes, Produtos e Vendedores).

    - Fórmulas **DAX** para criação de camadas de medidas de inteligência comercial, desde KPI's básicos até indicadores avançados.

    - **Storytelling** para estruturação de dashboards interativos em Dark Mode, utilizando leitura em Z e navegação por botões.

- Análises por dimensões estratégicas:
  
    - **Produtos:** Faturamento e volume por categoria, subcategoria e produto individual; identificação de itens líderes de receita e análise da representatividade dos segmentos.

    - **Clientes:** Monitoramento de ticket médio, faturamento médio e mediano por conta; identificação de recorrência de compra e concentração de receita em perfis.
 
    - **Performance Comercial e Diagnósticos:** Evolução mensal do faturamento, ranking de desempenho por vendedor e uso de visuais de dispersão e decomposição para rastrear o fluxo granular da receita e identificar tendências/anomalias.

### Resultados esperados

- Identificação das principais fontes de receita por produto, categoria e subcategoria, perfil de cliente e performance da equipe de vendas.

- Evidências para direcionamento de estratégias comerciais, extraídas através de diagnósticos e análise de comportamento de compra.
  
- Base analítica e visual estruturada e automatizada para apoio à tomada de decisão orientada por dados (data-driven), eliminando pontos cegos e a morosidade na extração de indicadores.

[Ver projeto Completo](https://github.com/Luan-Frederico/Case2_Analise_vendas)
