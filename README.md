# 📊 Projeto Integrador V — Apoio Decisório aos Negócios  
## Aplicação de Business Intelligence na análise de dados da Copa do Mundo FIFA 2022

---

## 📌 Descrição do Projeto

Este projeto tem como objetivo aplicar técnicas de **Business Intelligence (BI)** na análise de dados de jogadores da Copa do Mundo FIFA 2022, com o propósito de demonstrar como dados podem apoiar a **tomada de decisão estratégica no futebol**, especialmente no contexto de preparação para a Copa do Mundo de 2026.

A solução contempla todo o ciclo de dados:

- coleta de dados  
- processamento (ETL)  
- modelagem  
- análise  
- visualização  
- publicação  

---

## 🎯 Objetivos

- Identificar padrões de desempenho de jogadores  
- Construir indicadores analíticos (KPIs)  
- Desenvolver dashboards interativos  
- Demonstrar o uso de BI como ferramenta de apoio à decisão  

---

## 🧰 Tecnologias Utilizadas

| Tecnologia | Finalidade |
|---|---|
| Power BI Desktop | Desenvolvimento de dashboards e modelagem |
| Power Query | Processo de ETL (Extração, Transformação e Carga) |
| Power BI Service | Publicação e compartilhamento dos dashboards |
| CSV / JSON | Fontes de dados estruturadas |
| Linguagem M | Transformações no Power Query |
| GitHub | Versionamento e disponibilização do projeto |

---

## 🔄 Processo de ETL

O processo de ETL foi realizado no **Power BI Desktop**, utilizando o **Power Query**, e contemplou as seguintes etapas:

### 1. Extração
- Importação de 11 arquivos CSV e 1 JSON  
- Dados provenientes do dataset Kaggle  

### 2. Transformação
- Padronização de nomes de colunas (lowercase + underscore)  
- Tratamento de valores nulos e inconsistentes  
- Ajuste de tipos de dados  
- Remoção de colunas irrelevantes  
- Integração das tabelas  

### 3. Modelagem
- Tabelas principais:
  - `player_stats`
  - `player_passing`
  - `player_keepers`
- Chave de relacionamento: `player`

---

## 📐 Indicadores (KPIs)

### ⚽ Produtividade por tempo de jogo
### 🎯 Eficiência de passes
### 🧤 Eficiência de goleiros

---

## 📊 Dashboards

Foram desenvolvidos três dashboards interativos:

- Produtividade por tempo de jogo  
- Eficiência na troca de passes  
- Eficiência de goleiros  

### Recursos:
- KPIs  
- gráficos (barras e área)  
- filtros por posição, time e jogador  
- navegação entre páginas  

---

## ☁️ Publicação da Solução

Os dashboards foram publicados no **Power BI Service**, permitindo:

- acesso remoto via navegador  
- interatividade com filtros  
- compartilhamento com stakeholders  

---

## 🎥 Demonstração

O repositório inclui um vídeo demonstrativo contendo:

- explicação do ETL  
- modelagem de dados  
- construção dos dashboards  
- navegação e análise  

---

## 📁 Dataset

Fonte dos dados:

- Dataset: *FIFA World Cup 2022 Player Data*  
- Plataforma: Kaggle  

---

## ⚠️ Considerações

Este projeto **não tem como objetivo definir escalações reais**, mas sim:

> demonstrar como dados estruturados e técnicas de BI podem apoiar decisões estratégicas no futebol.

---

## 🚀 Como executar o projeto

1. Baixar o arquivo `.pbix`  
2. Abrir no Power BI Desktop  
3. Atualizar as fontes de dados (se necessário)  
4. Navegar pelos dashboards  

---

## 👥 Autores

- Akemi Vanessa Higa Hayashi  
- Gabriela Almeida Hirota  
- Hildo Celio Quixabeira de Souza  
- Kátia Jussara Silva de Santana  
- Letícia Martins de Oliveira  
- Sônia Gomes Caldas  
- Vinícius dos Santos Lima  

---

## 📚 Licença

Projeto acadêmico desenvolvido para fins educacionais.




