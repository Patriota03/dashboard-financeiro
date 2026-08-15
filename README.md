# Dashboard Financeiro

Painel de finanças pessoais, executado como site estático.

**Acesso:** https://patriota03.github.io/dashboard-financeiro/

## Recursos

- Controle de receitas e despesas
- Lançamentos recorrentes
- Metas de economia
- Sincronização na nuvem via GitHub API (repositório privado de dados)
- Exportar/importar backup (JSON ou CSV)

## Configuração da sincronização

1. No menu de sincronização, cole um *fine-grained token* com acesso de leitura/escrita
   (`Contents: Read and write`) apenas ao repositório privado de dados
   `dashboard-financeiro-dados`.
2. O token fica salvo apenas no `localStorage` do navegador, nunca no repositório.

> **Segurança:** nunca versionar arquivos de token (`*TOKEN*.txt`) nem backups de
> dados (`*.csv`) neste repositório público — eles estão protegidos pelo `.gitignore`.
