# Cantina Estoque - V1

Sistema simples em HTML único para controle de estoque da cantina com Firebase Firestore.

## Arquivos

- `index.html`: aplicação completa.

## Como subir no GitHub

1. Crie o repositório no GitHub.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Faça o deploy pela Vercel selecionando esse repositório.

## Firebase necessário

Ative somente:

- Firestore Database

Para testar rapidamente, use regras temporárias de leitura/escrita abertas. Depois, quando o sistema estiver pronto, adicione autenticação e regras fechadas.

## Fluxo do sistema

1. Cadastrar produtos ou importar uma nota.
2. Importar XML/JSON da nota.
3. Conferir os produtos antes de lançar no estoque.
4. Associar produto da nota com produto do sistema.
5. Confirmar entrada no estoque.
6. Atualizar estoque contado.
7. O sistema calcula a baixa, o lucro e distribui automaticamente.
8. Registrar saques/pagamentos por conta: Lucas, Giro/Caixa, Escola, Juan e Dona Francisca.
