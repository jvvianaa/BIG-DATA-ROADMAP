# 🗺️ Big Data Roadmap

Um guia interativo e visual de carreira para profissionais de dados, cobrindo desde os fundamentos absolutos até arquiteturas avançadas em nuvem e inteligência artificial.

![Preview do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Sobre o Projeto

O **Big Data Roadmap** é uma aplicação web single-page (SPA) estática projetada para ajudar estudantes e profissionais de tecnologia a trilharem o caminho de aprendizado no ecossistema de Big Data. 

A interface divide o conhecimento em fases cronológicas e pilares tecnológicos, permitindo que o usuário marque seu progresso em tempo real e visualize sua evolução global de forma dinâmica.

### 💡 Principais Recursos:
* **Estrutura por Fases:** Organizado do nível zero (Fundamentos) até o nível Sênior/Arquiteto.
* **Trilhas de Especialização:** Separação clara para caminhos em Engenharia de Dados, Ciência de Dados e Análise de Dados.
* **Persistência Local (LocalStorage):** O progresso das tarefas e certificações é salvo automaticamente no navegador, sem necessidade de banco de dados ou login.
* **Barra de Progresso Global e Individual:** Feedback visual imediato da evolução por área e no roadmap geral.
* **Estimativa de Mercado:** Visão realista das faixas salariais praticadas no mercado de dados.
* **Design Futurista e Responsivo:** Interface construída com tema escuro (*dark mode*), tipografia moderna (Syne & JetBrains Mono) e animações suaves de entrada.

---

## 🛠️ Tecnologias Utilizadas

Para manter o projeto extremamente leve, rápido e de fácil execução, foi utilizada a abordagem de desenvolvimento em arquivo único (*Single File Application*):

* **HTML5:** Estrutura semântica dos blocos e fases.
* **CSS3 (Moderno):** Uso avançado de *CSS Variables* para controle de paleta de cores, *CSS Grid* e *Flexbox* para responsividade, além de efeitos com `backdrop-filter` (glassmorphism).
* **JavaScript (Vanilla):** Lógica pura para renderização dinâmica dos componentes a partir de objetos estruturados, controle de estado do progresso e manipulação da API de `localStorage`.

---

## 📖 Estrutura do Roadmap

O conteúdo do roteiro de estudos está mapeado na aplicação através das seguintes etapas:

1. **Fase 0 — Fundamentos (0–6 meses):** Python básico e manipulação de dados (Pandas), Banco de Dados Relacionais (SQL) e Estatística Básica.
2. **Fase 1 — Ecossistema Big Data (6–12 meses):** Armazenamento e processamento distribuído (Hadoop, HDFS, Apache Spark) e pipelines básicos de ETL/ELT.
3. **Fase 2 — Cloud e Engenharia (1–2 anos):** Serviços de Nuvem (AWS/GCP), Mensageria/Streaming com Apache Kafka, modelagem de Data Warehouse (Snowflake/BigQuery) e orquestração avançada (dbt + Airflow).
4. **Fase 3 — Especialização (2–3 anos):** Dividido nas ramificações do mercado:
   * **Engenheiro de Dados:** Infraestrutura como código (Terraform), Kubernetes, Lakehouse e DataOps.
   * **Cientista de Dados:** Machine Learning (Scikit-learn, XGBoost) e MLOps (MLflow, FastAPI).
   * **Analista de Dados:** Business Intelligence (Power BI/Tableau) e Storytelling com Dados.
5. **Fase 4 — Sênior / Arquiteto (3+ anos):** Arquiteturas Lambda/Kappa, Governança de Dados, LGPD e pipelines de dados escalados para IA/LLMs.

---

## 🖥️ Como Executar o Projeto

Por ser uma aplicação baseada inteiramente no lado do cliente (client-side), **não é necessário instalar nenhuma dependência** (como Node.js ou pacotes externos).

O Projeto pode ser acessado pelo link: https://claude.ai/public/artifacts/c61f325a-b5a1-49ee-af9d-c1a3c4a75ea6

Caso queira exexutar via local, temos esse passo a passo:

1. Faça o clone deste repositório ou baixe o arquivo `bigdata_roadmap.html`.
2. Dê um duplo clique no arquivo `bigdata_roadmap.html` para abri-lo diretamente em qualquer navegador moderno de sua preferência (Chrome, Edge, Firefox, Safari).

*Dica de desenvolvimento: Se estiver usando o VS Code, você pode utilizar a extensão **Live Server** para rodar o projeto localmente com reload automático.*

---

Desenvolvido por IA focado em impulsionar o aprendizado contínuo na área de tecnologia.
