# Cantina Piaget — V8

Esta versão inclui a V7 e adiciona o fluxo de correção quando uma nota já foi usada por uma contagem.

## Principal correção

Agora o Histórico de contagens possui botão para cancelar a contagem mais recente.

Fluxo recomendado para corrigir uma nota já usada:

1. Ir em Histórico.
2. Cancelar a última contagem que usou aquela nota.
3. Abrir a nota.
4. Editar os itens da nota, por exemplo o fator de embalagem do pirulito.
5. Salvar a correção da nota.
6. Lançar a contagem novamente.

## Regra de segurança

Só é possível cancelar contagens da última data registrada. Para mexer em algo antigo, cancele da mais recente para a mais antiga, preservando a linha do tempo do estoque, FIFO e distribuição de lucro.

## O que o cancelamento faz

- Remove a contagem.
- Remove créditos ou débitos de distribuição ligados à contagem.
- Recalcula o estoque com base nas notas e nas contagens anteriores.
- Remove lotes de ajuste positivo criados pela contagem cancelada, quando identificáveis.

## Subida

Use somente o arquivo `index.html` na raiz do GitHub/Vercel.
