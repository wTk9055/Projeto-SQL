# Análise de Dados de Livros e Avaliações

## 📋 Descrição / Resumo Executivo

Este projeto realiza uma análise de um banco de dados de livros, autores, editoras e avaliações para extrair insights sobre tendências de publicação, popularidade de livros, desempenho de autores e padrões de engajamento dos usuários. O projeto utiliza SQL para consultas avançadas e Python para análise e visualização dos resultados.

## 🎯 Objetivos

* Quantificar o número de livros lançados após o ano 2000
* Identificar os livros mais populares baseados no volume de avaliações e suas classificações médias
* Determinar a editora com maior catálogo de livros extensos (+50 páginas)
* Analisar o autor com melhor desempenho em classificações (com volume significativo de avaliações)
* Calcular o engajamento médio de usuários ativos através de reviews

## 📊 Metodologia e Ferramentas

* **Linguagem de Programação:** Python
* **Bibliotecas Principais:** pandas, sqlalchemy
* **Banco de Dados:** PostgreSQL
* **Ambiente:** Jupyter Notebook

## 🗃️ O Conjunto de Dados

* **Fonte:** Banco de dados relacional hospedado em Amazon RDS
* **Descrição:** Dados relacionados a livros, autores, editoras, avaliações e reviews de usuários
* **Tabelas Principais:** books, authors, publishers, ratings, reviews
* **Escopo:** Inclui metadados de livros, informações de autores e editoras, além de avaliações e reviews dos usuários

## 🔍 Análise Exploratória de Dados (EDA)

* **Consultas SQL:** Foram realizadas consultas com junções, agregações e filtros para extrair métricas específicas
* **Análise de Tendências:** Identificação de 819 livros publicados após 2000, indicando um catálogo atualizado
* **Padrões de Engajamento:** Usuários que avaliam mais de 50 livros escrevem em média 24.33 reviews
* **Desempenho por Autor:** J.K. Rowling/Mary GrandPré obteve a maior classificação média (4.29) entre autores com mais de 50 avaliações

---

## 🚀 Como Executar este Projeto

### Pré-requisitos
* Python 3.8+
* Gerenciador de pacotes pip
* Acesso ao banco de dados remoto (credenciais fornecidas no notebook)

### Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/[seu-usuario]/analise-livros-avaliacoes.git

2. Navegue até o diretório do projeto:
   ```bash
   cd analise-livros-avaliacoes

3. Instale as dependências:
   ```bash
   pip install pandas sqlalchemy

## Execução
- Abra o Jupyter Notebook:
   ```bash
   jupyter notebook

- Execute as células do notebook notebook_SQL.ipynb em ordem.

---

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

---

Este projeto foi desenvolvido como parte do meu portfólio de Análise de Dados. Feedback é sempre apreciado!
