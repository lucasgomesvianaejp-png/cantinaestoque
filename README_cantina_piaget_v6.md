# Cantina Piaget — V6

Esta versão mantém as melhorias da V5 e acrescenta duas correções importantes de fluxo:

## 1. Contagem respeitando a data

Na tela **Atualizar Estoque**, o sistema agora calcula o estoque de referência pela data da contagem.

Exemplo:
- Compra importada em 03/07/2026;
- Contagem feita em 02/07/2026.

A compra de 03/07/2026 não entra na apuração da contagem de 02/07/2026.

## 2. Ajuste positivo com estorno de lucro

Quando uma contagem encontra mais estoque do que o sistema esperava, o sistema registra ajuste positivo.

Se esse estoque a mais provavelmente veio de uma venda presumida anterior, a V6 tenta estornar automaticamente o lucro reconhecido a mais.

Exemplo:
- Contagem anterior: sistema entendeu que vendeu unidades demais;
- Contagem atual encontra unidades a mais;
- O sistema devolve essas unidades ao estoque e debita o lucro que tinha sido distribuído indevidamente.

O estorno entra como movimento de distribuição do tipo **ajuste**, separado dos saques.

## Mantido da V5

- Subunidades / itens por embalagem;
- Conversão de quantidade comprada para quantidade vendável;
- Perfil individual por produto;
- Histórico de compras e vendas por produto;
- Detalhe de nota importada;
- Ranking de lucro, venda, compra e estoque;
- Histórico de preço de venda por data.

## Arquivo principal

Use o arquivo `index.html` na raiz do repositório GitHub.
