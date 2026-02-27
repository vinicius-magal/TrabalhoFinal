# 📦 PRO725 – Trabalho Final  
Modelagem de Dados • ETL (Apache Hop) • Dashboard (Metabase)

---

## 📑 Índice
- [🎯 Objetivo do Projeto](#-objetivo-do-projeto)
- [📘 Análise](#-análise)
- [🧩 Modelo Conceitual](#-modelo-conceitual)
- [🗂️ Modelo Lógico](#️-modelo-lógico)
- [🏗️ Modelo Físico](#-modelo-físico)
- [⚙️ ETL – Carga de Dados](#️-etl--carga-de-dados)
- [🔄 ETL – Transformação](#-etl--transformação)
- [📊 Dashboard – Metabase](#-dashboard--metabase)
- [▶️ Como Reproduzir o Projeto](#️-como-reproduzir-o-projeto)
- [👤 Autor](#-autor)

---

## 🎯 Objetivo do Projeto
Este projeto modela um sistema de pedidos, abrangendo análise, modelagem de dados, ETL e criação de dashboard analítico no Metabase.

Os seguintes itens exigidos foram atendidos:

1. GitHub organizado  
2. Análise  
3. Modelo Conceitual  
4. Modelo Lógico  
5. Modelo Físico  
6. ETL – Carga  
7. ETL – Transformação  
8. Dashboard  

---

## 📘 Análise  
📄 **Arquivo:**  
👉 [Análise – Projeto Final – PRO725](./docs/Análise%20-%20Projeto%20Final%20-%20PRO725.docx)

Conteúdo:  
- Descrição do problema  
- Escopo do sistema  
- Entidades relevantes  
- Regras de negócio  

---

## 🧩 Modelo Conceitual  
📄 **Arquivo:**  
👉 [Modelo Conceitual (brModelo)](./database/modelo_conceitual/ModeloConceitualFinal.brM3)

Inclui:  
- Entidades  
- Relacionamentos  
- Cardinalidades  

---

## 🗂️ Modelo Lógico  
📄 **Arquivo:**  
👉 [Modelo Lógico (brModelo)](./database/modelo_logico/ModeloLogicoFinal.brM3)

Inclui:  
- Tabelas  
- Atributos e domínios  
- Chaves primárias e estrangeiras  

---

## 🏗️ Modelo Físico  
📄 **Arquivo:**  
👉 [Modelo Físico – Script SQL](./database/modelo_fisico/Modelo%20Físico%20-%20Final.txt)

Inclui:  
- Estrutura final do banco  
- PKs e FKs  
- Tipos de dados  

---

## ⚙️ ETL – Carga de Dados  
📄 **Pasta:**  
👉 [ETL – Apache Hop](./etl)

Pipelines principais:  
- [cliente_corrigido_etl.hpl](./etl/cliente_corrigido_etl.hpl)  
- [produto_corrigido_etl.hpl](./etl/produto_corrigido_etl.hpl)  
- [pedido_corrigido_etl.hpl](./etl/pedido_corrigido_etl.hpl)  
- [contem_corrigido_etl.hpl](./etl/contem_corrigido_etl.hpl)  

Processos executados:  
- Leitura dos CSVs  
- Correção de inconsistências  
- Carga no banco  

---

## 🔄 ETL – Transformação  
Executado nos mesmos arquivos `.hpl`.

Inclui:  
- Padronização de dados  
- Conversão de tipos  
- Preparação para análises no Metabase  

---

## 📊 Dashboard – Metabase  
📄 **Arquivo:**  
👉 [Dashboard – Análise de Pedidos e Clientes](./dashboard/Metabase%20-%20Dashboard%20–%20Análise%20de%20Pedidos%20e%20Clientes.pdf)

Indicadores exibidos:  
- Total de clientes  
- Total de pedidos  
- Ticket médio  
- Faturamento total  
- Pedidos por status  
- Faturamento diário  
- Produtos mais vendidos  

---

## ▶️ Como Reproduzir o Projeto

### 🔧 1. Banco de Dados
1. Criar banco PostgreSQL  
2. Executar o script SQL em:  
   👉 `/database/modelo_fisico/Modelo Físico - Final.txt`

### 🔄 2. ETL – Apache Hop
1. Abrir Apache Hop  
2. Carregar arquivos da pasta `/etl`  
3. Ajustar caminhos dos CSV em `/dados`  
4. Executar os pipelines  

### 📈 3. Dashboard – Metabase
1. Conectar Metabase ao banco  
2. Criar perguntas e métricas  
3. Reproduzir o dashboard  

---

## 👤 Autor
**Vinicius Muniz Magalhães – UFOP**  
Disciplina: PRO725 – Engenharia da Informação  
