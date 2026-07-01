# Cantina Piaget — V7

## O que mudou nesta versão

Esta versão inclui tudo da V6 e acrescenta a edição de notas já importadas, especialmente para corrigir itens comprados em embalagem e vendidos por subunidade.

Exemplo: pirulito comprado em 3 pacotes com 24 unidades por pacote.

- Qtd nota: 3
- Itens por embalagem: 24
- Qtd em estoque: 72 unidades vendáveis
- Custo unitário: custo total dividido por 72
- Preço de venda: preço por unidade vendável

## Como corrigir uma nota já importada

1. Abra o sistema.
2. Vá em Histórico.
3. Clique em Abrir na nota desejada.
4. Clique em Editar itens.
5. Ajuste quantidade da nota, itens por embalagem, custo total, produto associado e preço de venda.
6. Clique em Salvar correção da nota.

## Proteção importante

A edição direta da nota só é permitida enquanto nenhum lote daquela nota tiver sido baixado por uma contagem de estoque.

Se algum item daquela nota já tiver sido consumido em uma contagem, o sistema bloqueia a edição direta para não bagunçar:

- estoque FIFO;
- lucro já apurado;
- saldos de distribuição;
- histórico de baixa.

Nesse caso, o caminho correto é fazer um ajuste de estoque/correção posterior.

## Arquivo para subir

Suba apenas o arquivo:

- index.html

O arquivo com nome descritivo é só backup/referência da versão.
