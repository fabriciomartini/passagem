# Passagem de serviço P-83 — publicação de teste

Conteúdo estático: `index.html` (página de entrada), `app.html` (aplicativo), `deck.html` (apresentação) e seus recursos.

## Publicar no GitHub Pages
1. Envie TODOS os arquivos desta pasta para a raiz do repositório `fabriciomartini/passagem` (branch `main`), inclusive `.nojekyll` e a pasta `_ds`.
2. No GitHub: Settings → Pages → Source: *Deploy from a branch* → Branch `main` / `/(root)` → Save.
3. Em ~1 min o site estará em https://fabriciomartini.github.io/passagem/

## Ligar ao Wix (fabriciomartini.com/passagemdeservico)
1. No editor Wix, crie a página **passagemdeservico** e defina o slug `/passagemdeservico`.
2. Adicionar → Incorporar código → **Incorporar um site** (iframe) → URL: https://fabriciomartini.github.io/passagem/ ; ajuste a altura (~720 px) e largura total.
3. Página → Permissões → **Protegida por senha**; envie a senha aos testadores.
4. Publique o site Wix. Os botões abrem app e apresentação em nova aba (fora do iframe), então câmera, microfone e tela cheia funcionam normalmente.

## Observações
- Cada testador vê apenas os dados do próprio navegador; no primeiro acesso são criados dados de exemplo.
- Administrador semeado: ADMIN / admin1234 — troque a senha em Administração → Usuários antes de divulgar.
