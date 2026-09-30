# Porsche Sales Performance Dashboard

Dashboard profissional de análise de vendas de veículos Porsche, construído em HTML, CSS e JavaScript puro. A página lê dados reais e atualiza KPIs, rankings, gráficos e insights em tempo real conforme os filtros selecionados.

## Visão geral

Este projeto apresenta uma interface de análise comercial para dados de vendas Porsche com:

- filtros interativos por modelo, ano, cidade e forma de pagamento
- KPIs dinâmicos de volume, faturamento e ticket médio
- ranking dos modelos mais vendidos
- evolução de vendas por período e estado
- análise por cidade e ano do modelo
- botão para limpar filtros
- visual premium e responsivo

## Arquivos do projeto

- [index.html](index.html) — arquivo principal do dashboard e da lógica interativa
- [porsche_database_sanitized(1).xlsx](porsche_database_sanitized(1).xlsx) — base de dados real usada para alimentar o dashboard

## Como abrir

Versão pública do dashboard: [Porsche Sales Performance](https://minaandressa2-max.github.io/DIOporsche/).

Para executar localmente, inicie um servidor na pasta do projeto:

```bash
python -m http.server 8000
```

Depois, abra este endereço no seu próprio computador:

```text
http://localhost:8000/index.html
```

## Funcionalidades principais

### Filtros dinâmicos
Os filtros alteram automaticamente:

- total de veículos
- faturamento total
- ticket médio
- ranking de modelos
- gráficos de evolução e distribuição
- insights do dashboard

### KPI e indicadores
A página calcula e exibe:

- total de veículos
- faturamento
- ticket médio
- quantidade de modelos presentes no recorte
- quantidade de cidades presentes no recorte

### Gráficos
Inclui visualizações para:

- evolução de vendas por período
- vendas por cidade/estado
- top modelos
- vendas por ano do modelo
- modelo mais vendido por cidade

### Limpeza de filtros
O botão "LIMPAR FILTROS" retorna o dashboard ao cenário completo sem perder a estrutura ou os dados atuais.

## Dados

Os números usados no dashboard vêm de uma base real fornecida em Excel, preservando os nomes das colunas e a lógica dos dados existentes. Não foram criados dados fictícios para a página.

## Tecnologias utilizadas

- HTML
- CSS
- JavaScript
- Chart.js

## Observações

O dashboard foi pensado para funcionar de forma real e interativa no navegador, com processamento dos dados no cliente por meio de JavaScript.
