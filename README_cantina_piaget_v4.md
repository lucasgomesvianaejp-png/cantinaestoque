# Cantina Estoque — V4

Atualização da V4:

- Abre cada nota importada no histórico.
- Mostra os itens importados em cada nota: produto, descrição original, quantidade, custo e preço de venda informado.
- Cria perfil por produto.
- No perfil do produto, mostra compras, vendas/baixas, lotes em estoque e histórico de preço.
- Adiciona tela de comparativo/ranking:
  - produtos que mais deram lucro;
  - produtos que mais venderam;
  - compras por produto;
  - estoque e lucro potencial.
- Adiciona controle de variação de preço de venda por data.

## Regra de preço de venda

Quando o preço de venda mudar, abra o produto e registre:

- data de início;
- novo preço;
- observação.

Nas próximas atualizações de estoque, o sistema usa o preço vigente na data da contagem. O preço usado em uma contagem fica salvo dentro do item da baixa, então alterações futuras não recalculam vendas antigas.

Exemplo:

- BUBBALOO era R$ 0,50.
- Em 01/07/2026 passou para R$ 1,00.
- Uma contagem com data 30/06 usa R$ 0,50.
- Uma contagem com data 01/07 ou depois usa R$ 1,00.

## Arquivos

- `index.html`: sistema completo em arquivo único.

## Como subir

Substitua o `index.html` atual no repositório GitHub por este novo arquivo e aguarde a Vercel atualizar o deploy.
