# 📊 Dashboard de Vendas no Excel

Este é um projeto simples de **análise de vendas** feito no **Microsoft Excel**, utilizando recursos de **Power Query**, **Power Pivot** e **DAX**.

---

## 🧠 Tecnologias Utilizadas

- **Excel com Power Query** – para importar e transformar os dados de arquivos CSV
- **Power Pivot** – para modelar o relacionamento entre tabelas e criar medidas
- **DAX (Data Analysis Expressions)** – para calcular Total de Vendas e Lucro
- **Tabela Dinâmica e Gráficos** – para montar o dashboard final

---

## 📄 Descrição dos Arquivos

- **clientes.csv**: Contém nome e região dos clientes
- **produtos.csv**: Lista os produtos com preço de custo e de venda
- **vendas.csv**: Registra cada venda, com data, produto, cliente e quantidade
- **Projeto-Vendas.xlsx**: Arquivo Excel com o modelo completo e dashboard

---

## 🛠️ Funcionalidades Desenvolvidas

- Importação automatizada dos dados via Power Query
- Modelagem com relacionamentos entre as tabelas (`Clientes`, `Produtos`, `Vendas`)
- Criação de medidas com DAX:
  - `TotalVendas`: calcula o total faturado
  - `LucroTotal`: calcula o lucro com base na diferença entre preço de venda e custo
- Dashboard interativo com:
  - Vendas por Produto
  - Lucro por Região
  - Gráficos e filtros dinâmicos
