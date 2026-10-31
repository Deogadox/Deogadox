# Olá, sou o Felipe Rios Miranda 👋

**Engenheiro de Dados | BI & Analytics | SQL Server · Python · Power BI | ETL e Automação**

Construo pipelines de dados ponta a ponta: **captura automatizada** (Python/Selenium), **carga e modelagem em SQL Server** e **dashboards em Power BI** com DAX avançado. Atualmente aprofundando em **Machine Learning** e **Engenharia de Dados em nuvem** (Databricks/PySpark, Azure) na pós-graduação em Data Analytics da FIAP.

📍 Feira de Santana, BA · 🌎 Aberto a oportunidades remotas

---

## 🔧 Stack

**Dados e BI**

<div>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white">
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white">
<img src="https://img.shields.io/badge/Azure_SQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white">
</div>

**Desenvolvimento web**

<div>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>

| Área | O que uso no dia a dia |
|---|---|
| **SQL Server / T-SQL** | Stored procedures, views, triggers, modelagem relacional e dimensional, tuning com índices, jobs no SQL Server Agent |
| **Python** | ETL com pandas e SQLAlchemy, RPA com Selenium, integração com SharePoint/SFTP, machine learning com scikit-learn |
| **Power BI** | Modelagem, DAX avançado (`SUMX`, `ISINSCOPE`, médias ponderadas, real × projetado), indicadores operacionais |
| **Em estudo** | Databricks e PySpark (trilha de Engenharia de Dados), Azure |

---

## 🚀 Projetos em destaque

### 🍷 [Classificação da qualidade de vinhos](https://github.com/Deogadox/wine-quality-classification) — Machine Learning
Modelo que prevê se um vinho tinto será de alta qualidade a partir de 11 medidas de laboratório. EDA com testes estatísticos, pré-processamento sem vazamento de dados, comparação de Regressão Logística, Random Forest e Gradient Boosting, ajuste de limiar para classe desbalanceada e interpretação com importância por permutação.
**Resultado:** acerta 3,7× mais que o acaso ao apontar um vinho excelente. · [🎬 Vídeo](https://youtu.be/bnD7dri3Oyg)
`Python` `scikit-learn` `pandas` `seaborn` · Tech Challenge FIAP (em grupo)

### 🛒 [Pipeline Olist E-Commerce](https://github.com/Deogadox/Tech_Chalenger) — Engenharia de Dados + BI
Pipeline ponta a ponta sobre dados reais de e-commerce: download automatizado com Python, carga em SQL Server via stored procedure e `BULK INSERT`, e relatório em Power BI com visão comercial e logística.
`Python` `SQL Server` `T-SQL` `Power BI` · Tech Challenge FIAP

### 🏭 STAR ERP — Sistema de gestão industrial *(repositório privado · projeto freelance)*
ERP para uma fabricante de produtos de limpeza automotiva, cobrindo compras, produção, estoque e vendas. Modelo relacional em SQL Server (convenção D_/F_, views de saldo de estoque calculadas dinamicamente e triggers), migração dos dados históricos que viviam em planilhas, relatório de custo × lucro por lote de produção, API em Node.js/Express e front-end em Next.js.
`SQL Server` `Azure SQL` `Node.js` `Next.js` `Vercel`

### 🥩 [GestCarnes](https://carcaca-pricing.vercel.app) — Precificação para açougues
Aplicação web com painel de gestão para calcular o preço de venda dos cortes a partir do custo da carcaça.
`Web app` `Vercel`

### 🩺 [Portfólio profissional — fisioterapia](https://portfolio-julia-fisio.vercel.app/)
Site institucional para uma fisioterapeuta, desenvolvido em React/Next.js e hospedado na Vercel.

---

## 💼 Experiência

### Analista de MIS Sênior — NeoBpo · *fev/2025 – set/2026*
Ambiente multi-cliente (MAPFRE, Sem Parar, Marsh, Tech Force).
- Pipelines de extração automatizada com **Python + Selenium** (Qlik Sense, Qlik Cloud, Evertrack), com sessões resilientes e anti-detecção via CDP — **eliminando de 1 a 3 horas de trabalho manual por dia**
- Dashboard de performance operacional em **Power BI** (rankings dinâmicos por quartil, ocupação e tráfego em tempo real) usado por supervisores para acompanhar **50 a 150 operadores**
- Debugging e otimização de **stored procedures e views** críticas em produção: violações de chave por gaps de vigência, gargalos em funções table-valued entre bancos e falhas de carga incremental
- Pipeline **SharePoint → SQL Server** com staging e validação defensiva (`TRY_CONVERT`/`NULLIF`), e tratamento de arquivos **SFTP** com encoding e separador não padrão
- ETL e medidas DAX de **real × forecast** para cliente de mobilidade/pedágio; automação do fechamento intraday de um cliente de seguros, com migração de alertas para **Power Automate**
- Monitoramento de jobs do **SQL Server Agent** e criação/ajuste de índices para resolver lentidão

### Analista de Dados — Grupo São Roque · *ago/2024 – fev/2025*
Suíte de relatórios gerenciais em **Power BI** (alimentada por SQL Server e rotinas Python) cobrindo toda a cadeia da distribuidora — recebimento, armazenagem, estoque, vendas, entregas e devoluções.
- **Gestão de estoques:** mais de **5,9 mil SKUs** segmentados por curva A–D, com excesso, risco de ruptura, dias de estoque (DDE) e margem/giro por comprador e fornecedor — apoio direto às decisões de compra
- **Avarias e vencimentos:** projeção de perda financeira por produto a vencer, com **mapa de calor sobre a planta do armazém** (rua, prédio, nível e apartamento) para localizar itens críticos
- **Devoluções:** análise de **Pareto (80/20)** das causas, separando responsabilidade entre Logística e Comercial
- **Entregas:** acompanhamento de mais de **16 mil entregas/mês** por rota, praça e carregamento, com sazonalidade diária e semanal
- **Vendas e recebimento:** pedidos antes × depois das 12h para planejar separação e faturamento; KPIs de descarga e tempo de pátio por fornecedor
- Queries SQL de extração e consolidação e tratamento automatizado em Python, reduzindo a preparação manual dos relatórios

### Estagiário de Dados — Seguros Unimed · *jun/2023 – jun/2024*
- Apoio à equipe de dados na construção de relatórios analíticos e planilhas avançadas
- Scripts em Python para automatizar tarefas repetitivas
- Primeira experiência profissional com SQL e ferramentas de BI em ambiente corporativo

---

## 🎓 Formação

- **Pós-graduação em Data Analytics** — FIAP *(em andamento, previsão 2027)*
- **Tecnólogo em Análise e Desenvolvimento de Sistemas** — FIAP *(2022–2024)*
- **Databricks: Transformação de Dados com PySpark** — Alura *(2026)* · Carreira Engenharia de Dados — Alura *(em andamento)*
- Data Visualization (80h) e Big Data & Analytics (60h) — FIAP · Python do Básico ao Avançado (64h) — Udemy

🌐 Português nativo · Inglês intermediário (leitura e escrita técnica)

---

## 📫 Contato

<div>
<a href="https://www.linkedin.com/in/felipe-rios-miranda-9052a7227/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://instagram.com/fe.mranda" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</div>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Deogadox/Deogadox/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Deogadox/Deogadox/output/github-contribution-grid-snake.svg" />
  <img alt="snake gif" src="https://raw.githubusercontent.com/Deogadox/Deogadox/output/github-contribution-grid-snake.svg" />
</picture>
