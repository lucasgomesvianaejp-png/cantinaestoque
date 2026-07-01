# Cantina Estoque - Piaget V2

Sistema web simples em HTML único, conectado ao Firebase/Firestore.

## O que mudou nesta versão

- Inclui botão **Importar base inicial da planilha**.
- A base inicial importa somente produtos/lotes com estoque atual maior que zero.
- Itens com estoque zerado não entram no estoque.
- Alguns nomes antigos da planilha entram apenas como apelidos quando o produto ativo é evidente.
- A importação inicial não gera lucro e não cria saldo de distribuição. Ela apenas carrega estoque.

## Base inicial extraída da planilha

- Produtos ativos: 26
- Lotes com estoque: 56
- Valor em estoque pelo custo: R$ 2.281,85
- Lucro potencial estimado, se vender tudo pelos preços cadastrados: R$ 1.390,65

## Como usar

1. Suba o `index.html` para o GitHub.
2. Publique pela Vercel.
3. Abra o sistema.
4. Vá em **Importar Nota**.
5. Clique em **Importar base inicial da planilha**.
6. Depois disso, use normalmente: importar novas notas, atualizar estoque contado, gerar lucro e sacar por conta.

## Observação

A importação inicial tem proteção contra duplicidade: se a nota `BASE-INICIAL-PLANILHA` já existir no Firestore, o sistema não importa novamente.
