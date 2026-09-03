# Samuel de Azevedo — Ecossistema

Site estático responsivo, pronto para GitHub e Vercel.

## Endereços incluídos

- `/` — página inicial
- `/bio` — trajetória
- `/ngs` — Neuro Guitar System
- `/presets-pedaleiras` — loja Trucker Cap Tone Lab com botões individuais preparados para links da Eduzz
- `/apps` — aplicativos Trucker Cap
- `/cursos` — cursos e consultorias
- `/projetos` — projetos artísticos

## Publicar na Vercel

1. Extraia este ZIP.
2. Crie um repositório no GitHub e envie todo o conteúdo desta pasta.
3. Na Vercel, selecione **Add New > Project**.
4. Importe o repositório.
5. Em **Framework Preset**, escolha **Other**.
6. Não preencha Build Command nem Output Directory.
7. Clique em **Deploy**.

O arquivo `vercel.json` já configura URLs limpas e cache dos arquivos visuais.

## Domínio próprio

Depois do deploy, abra **Settings > Domains** na Vercel e adicione:

`samueldeazevedo.com.br`

A própria Vercel mostrará os registros que devem ser inseridos no Registro.br.

## Editar

- Textos e estrutura: arquivos `index.html`.
- Visual: `assets/site.css`.
- Menu mobile: `assets/site.js`.
- Seletor de idioma com Português Brasil, Espanhol e Inglês.
- Foto principal: `assets/samuel-hero.png`.
