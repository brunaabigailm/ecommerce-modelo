# 🛒 Modelo Conceitual de E-commerce

Este projeto é parte do desafio proposto para o curso de Análise e Desenvolvimento de Sistemas. Ele representa um modelo conceitual de banco de dados para uma aplicação de comércio eletrônico, utilizando MySQL Workbench.

## 📌 Objetivo

Refinar e representar conceitualmente um sistema de e-commerce, considerando:

- **Clientes Pessoa Física e Jurídica** (uma conta pode ser PF ou PJ, mas não as duas);
- **Pagamentos** com múltiplas formas cadastradas por cliente;
- **Entrega** com status e código de rastreamento.

## 🧩 Arquivos

- `e-commerce.mwb` — Arquivo do modelo criado no MySQL Workbench;
- `e-commerce.png` — Imagem exportada do diagrama para visualização rápida.

## 🗂️ Estrutura do modelo

- **Cliente** com generalização para PF e PJ;
- **Pedido** com relação a produtos e entrega;
- **Produto** vinculado a estoque, fornecedores e vendedores terceiros;
- **Pagamento** separado por cliente com possibilidade de múltiplos registros;
- **Entrega** com atributos de status e código de rastreio.

## 🛠️ Ferramentas

- MySQL Workbench 8.0.41
- Git & GitHub

---

> Projeto desenvolvido por Bruna Abigail Milbradt — [brunaabigailm@gmail.com](mailto:brunaabigailm@gmail.com)