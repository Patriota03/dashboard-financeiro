# Dashboard Financeiro

Controle de receitas e despesas, com meta de investimento, lançamentos recorrentes e comprovantes.

## Acessar

Disponível online: https://patriota03.github.io/dashboard-financeiro/

## Funcionalidades

- Resumo de saldo, receitas, despesas e taxa de economia por período
- Meta de investimento com progresso e estimativa de conclusão
- Lançamentos com categorias, busca e filtro por mês
- Lançamentos recorrentes (semanal, mensal, anual) com total de parcelas
- Comprovantes (foto ou arquivo) armazenados no IndexedDB
- Exportação para CSV e dados de exemplo

## Tecnologia

Aplicação 100% estática em um único arquivo HTML (sem servidor e sem build):

- HTML + CSS + JavaScript vanilla
- Chart.js via CDN
- localStorage para dados e IndexedDB para comprovantes
