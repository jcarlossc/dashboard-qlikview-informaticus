# 📌 Projeto BI – Loja de Informática (QlikView)

## 📌 Visão Geral

Este projeto tem como objetivo desenvolver um dashboard interativo em QlikView para análise de vendas de uma loja de informática, permitindo o 
acompanhamento de indicadores estratégicos como faturamento, volume de vendas e produtos mais vendidos.

O projeto foi construído seguindo boas práticas de BI, com:

* Modelagem de dados adequada
* Scripts de carga organizados
* KPIs claros
* Visualizações interativas
* Documentação completa para reprodução do ambiente

---

## 📌 Contexto do Negócio

A loja de informática comercializa produtos como:

* Impressoras
* Periféricos (mouse, teclado, monitores)
* Componentes de hardware
* Acessórios e suprimentos

O gestor precisa responder perguntas como:

* Qual o faturamento mensal, trimestral e anual?
* Quais produtos vendem mais?
* Quantidade de vendas por vendedor
* Commissão
* Margem
* Lucro

---

## 📌 Objetivos do Projeto

* Criar um painel gerencial de vendas
* Facilitar a tomada de decisão
* Padronizar indicadores de desempenho
* Demonstrar domínio prático do QlikView

---

## 📌 Tecnologias Utilizadas

* QlikView Desktop
* Banco de Dados SQL (fonte de dados)
* Conector ODBC: conexão com o banco de dados (extração)
* Modelagem associativa do Qlik
* Expressões Qlik (Set Analysis)
* Git/GitHub para versionamento

---

## 📌 Estrutura do Projeto

```
dashboard-qlikview-informaticus/
│
├── carregamento/
│   └── carregamento.qvw
│
├── dados_qvd/
│   ├── produto_qvd.qvd
│   ├── vendas_qvd.qvd
│   ├── vendas_transformada_qvd.qvd
│   └── vendedor_qvd.qvd
│
├── extracao/
│   └── extracao.qvw
│
├── fonte/
│   └── loja_info.sql
│
├── imagens/
│   ├── vendas_01.png
│   └── vendas_02.png
│
├── transformacao/
│   └── transformacao.qvw
│
├── visualizacao/
│   └── visualizacao.qvw
│
├── license
└── README.md
```

---

