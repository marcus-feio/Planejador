# Planejador Financeiro · InvestSmart

Ferramenta de planejamento financeiro para assessores: cadastro do cliente, fluxo mensal, patrimônio, projetos (investir × consórcio × financiamento), independência financeira, proteção, sucessão e relatório em PDF com apresentação interativa.

## Onde ficam os dados

**Nenhum dado de cliente fica neste repositório nem no GitHub.** O site contém apenas o aplicativo. Os dados são gravados:

1. no navegador de quem usa (salvamento automático), e
2. numa pasta escolhida pelo usuário em **"Numa pasta do computador"**: o app grava `planejador-financeiro.json` a cada alteração e uma cópia por dia em `backups/` (últimos 30 dias).

Recomendação: escolha uma pasta **dentro do OneDrive**. Assim os dados ficam com cópia na nuvem, histórico de versões e acesso de outros computadores.

Funciona no Chrome e no Edge (a gravação em pasta não está disponível no Safari e no Firefox).

## Nunca envie para este repositório

- arquivos `.json` de backup ou exportação;
- prints, PDFs ou planilhas com dados de clientes.

O `.gitignore` bloqueia arquivos `.json` e a pasta `backups/` por segurança.

## Como atualizar

Substitua o `index.html` pela nova versão (Add file → Upload files) e confirme. O site atualiza em 1 a 2 minutos. Os dados dos usuários não são afetados.

## Aviso

Estudos gerados são ilustrativos, com base nas informações do cliente e nas premissas informadas. Não constituem recomendação de investimento nem garantia de rentabilidade.
