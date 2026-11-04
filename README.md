# Currículo virtual

O site está organizado em `site/`: `index.html` é a página inicial narrativa, e `experiencia.html`, `formacao.html`, `projetos.html`, `sobre.html` e `contato.html` são páginas próprias acessadas pelo menu. `styles.css`, `script.js`, os logos e a foto de perfil também ficam nessa pasta. O PDF para download fica em `site/Curriculo.pdf`.

Os arquivos de consulta e memória ficam fora da pasta do site: `Curriculo.pdf`, `FotoCurriculo.png` e `memoria-projeto-curriculo.md`. A cópia em `site/Curriculo.pdf` é a versão servida publicamente pelo botão de download.

Para visualizar localmente, abra `site/index.html`. Se estiver servindo a pasta raiz com `python -m http.server 4173`, acesse `http://localhost:4173/site/`.

## Publicação

O workflow em `.github/workflows/pages.yml` publica o conteúdo da pasta `site/` no GitHub Pages a cada envio para `main`. Ative GitHub Pages nas configurações do repositório e escolha `GitHub Actions` como fonte.

## Tecnologia

A versão atual usa HTML, CSS e JavaScript sem framework. Isso mantém o currículo estático leve e simples de publicar. Se a seção de projetos crescer para várias páginas de detalhe ou novas áreas de conteúdo, Astro é uma boa próxima etapa para compartilhar layouts e componentes sem adicionar JavaScript ao navegador por padrão.
