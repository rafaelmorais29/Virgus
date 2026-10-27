# Virginus

Site estático, sem dependências: abra `index.html` no navegador.

- `index.html`: estrutura da página.
- `styles.css`: cores, tipografia e layout (variáveis em `:root`).
- `data.js`: dados do acervo (`D` aparições, `TEM` templos, `IMG` imagens, `SH` nomes curtos).
- `app.js`: busca, filtros, detalhe, tema e ampliação de imagem.
- `assets/img/`: imagens `.webp`, uma por aparição, com o mesmo id usado em `IMG`.

Para adicionar uma aparição: inclua um objeto em `D` (copie um existente), um item em `TEM` e, se tiver imagem, um arquivo em `assets/img/` com entrada em `IMG`.
As imagens atuais são ilustrações geradas por IA, sem valor de registro histórico. Os dados precisam de revisão humana e confirmação de fontes.
