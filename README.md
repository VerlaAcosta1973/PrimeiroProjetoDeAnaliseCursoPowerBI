# 📊 Análise de Vendas e Desempenho Comercial (2021 - 2023)

![Power BI](https://shields.io)
![Git](https://shields.io)
![Excel](https://shields.io)

## 📌 Sobre o Projeto
Este projeto consiste no desenvolvimento de um **Dashboard de Inteligência de Negócios (BI)** focado na análise do histórico de vendas de uma empresa no período de 2021 a 2023. O objetivo principal é consolidar bases de dados isoladas para extrair insights sobre faturamento, desempenho da equipe de vendas e comportamento dos clientes.

O projeto está sendo desenvolvido como parte do meu plano de estudos no curso de Power BI da **Hashtag Treinamentos**, aplicando conceitos práticos e estruturados de Business Intelligence desde os módulos iniciais.

---

## 📂 Estrutura das Bases de Dados
Os dados originais foram extraídos de planilhas eletrônicas do Microsoft Excel, divididos nas seguintes tabelas:

*   **Cadastro de Clientes:** Dados demográficos e identificação única dos consumidores.
*   **Cadastro de Vendedores:** Registro da equipe comercial responsável pelos atendimentos.
*   **Histórico de Vendas (2021, 2022 e 2023):** Três tabelas sazonais contendo os registros de transações, produtos vendidos, datas, quantidades e valores.

---

## 🛠️ Recursos e Etapas de Desenvolvimento

Apesar de estar nas etapas iniciais do desenvolvimento, o projeto já aplica boas práticas fundamentais de engenharia e análise de dados:

### ⚡ 1. Extração e Tratamento de Dados (Power Query)
*   **Consolidação de Bases:** Importação e unificação das tabelas de vendas anuais (2021, 2022 e 2023) em uma única base de fatos.
*   **Limpeza de Dados:** Tratamento de tipos de dados (texto, número, data), remoção de colunas desnecessárias e preenchimento de valores nulos.

### 📐 2. Modelagem de Dados
*   **Relacionamentos:** Criação de conexões entre as tabelas de cadastros (dimensões) e a tabela unificada de vendas (fatos), garantindo a integridade dos filtros do relatório.

### 📊 3. Visualização (Em Desenvolvimento)
*   Construção de indicadores fundamentais de desempenho comercial (KPIs).
*   Criação de visuais limpos e intuitivos para facilitar a tomada de decisão da diretoria.

---

## 📸 Demonstração do Dashboard

*(Espaço reservado para inclusão dos prints das telas do painel assim que a etapa visual for concluída)*

---

## 🚀 Como Executar este Projeto Localmente

1.  Certifique-se de ter o **Power BI Desktop** instalado (recomendado instalar via Microsoft Store).
2.  Clone este repositório na sua máquina:
    ```bash
    git clone https://github.com
    ```
3.  Abra o arquivo `CaseHashtag.pbix` no Power BI Desktop.
4.  *(Caso necessário)* Ajuste o caminho das fontes de dados do Excel no Power Query para apontar para a pasta onde os arquivos originais estão salvos no seu computador.
