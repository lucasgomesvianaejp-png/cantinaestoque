# Sistema Cantina Piaget — V3 base inicial 2026

Esta versão corrige a importação inicial da planilha.

## Correções desta versão

- A base inicial agora importa somente itens do ano de 2026.
- Apenas produtos com estoque atual maior que zero entram no estoque.
- Anos anteriores não entram na base inicial para evitar mistura com saldos antigos.
- Foi adicionado o botão **Apagar importação inicial antiga**, para remover a importação geral anterior do Firebase.
- A importação inicial 2026 não gera lucro e não mexe nos saldos de distribuição.

## Números da nova base inicial

- Produtos: 12
- Lotes: 12
- Estoque total: 619 unidades
- Valor em estoque pelo custo: R$ 532,40
- Lucro potencial estimado: R$ 230,10

## Como corrigir no sistema já publicado

1. Suba este `index.html` no GitHub.
2. Aguarde a Vercel atualizar o deploy.
3. Abra o sistema.
4. Vá em **Importar Nota**.
5. Clique em **Apagar importação inicial antiga**.
6. Depois clique em **Importar base inicial 2026**.

A limpeza remove somente os documentos criados pela importação inicial da planilha: produtos, lotes, itens, nota-base e aliases/apelidos. Ela não apaga saques, contagens ou lançamentos manuais feitos fora da base inicial.
