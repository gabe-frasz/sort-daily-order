# Daily

Sorteia a ordem de fala da daily e acompanha quem já falou, para ninguém ficar de fora.

Um único `index.html`, sem dependências e sem backend. Funciona abrindo o arquivo direto no navegador ou hospedado como página estática.

## Como usar

- **Editar**: adiciona e remove pessoas. O switch marca quem faltou hoje.
- **Concluir** (ou clique no nome): marca quem já falou e passa a vez.
- **Nova daily**: sorteia uma nova ordem e zera os concluídos.
- **Desfazer**: volta a última ação.

Atalhos: `→` ou `espaço` concluem a pessoa atual; `Ctrl/⌘ + Z` desfaz.

A cada novo dia, a ordem é sorteada automaticamente e as ausências são zeradas.

## Dados

Tudo fica no `localStorage` do navegador de quem usa. Nada é enviado para servidor. Por isso, os dados não aparecem para quem abrir o mesmo link em outro navegador ou máquina, e se perdem se os dados do navegador forem limpos.

## Deploy (GitHub Pages)

1. O repositório precisa ser público no plano gratuito.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
