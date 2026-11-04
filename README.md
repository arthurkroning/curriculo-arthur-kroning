# Arthur Kröning — Currículo virtual

Currículo online de **Arthur Kröning**, com apresentação profissional, experiências, formação, projetos e canais de contato.

🌐 **Acesse o site:** [arthurkroning.github.io/curriculo-arthur-kroning](https://arthurkroning.github.io/curriculo-arthur-kroning/)

## Sobre o projeto

Este projeto transforma o currículo tradicional em uma experiência web responsiva, organizada em páginas próprias e com uma apresentação narrativa da trajetória profissional.

### Conteúdo

- **Início:** resumo profissional e marcos da trajetória.
- **Experiência:** histórico profissional e responsabilidades.
- **Formação:** cursos, certificados e descrições.
- **Projetos:** trabalhos de desenvolvimento e programação.
- **Sobre:** perfil, competências e interesses.
- **Contato:** formas de entrar em contato.
- Download do currículo em PDF.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- GitHub Pages e GitHub Actions para publicação

O site é estático e não precisa de framework, instalação de dependências ou processo de compilação.

## Executar localmente

Clone o repositório e entre na pasta:

```bash
git clone https://github.com/arthurkroning/curriculo-arthur-kroning.git
cd curriculo-arthur-kroning
```

Você pode abrir `site/index.html` diretamente no navegador. Para servir localmente usando Python:

```bash
python -m http.server 4173
```

Depois, acesse [http://localhost:4173/site/](http://localhost:4173/site/).

## Estrutura do projeto

```text
.
├── .github/
│   └── workflows/
│       └── pages.yml       # Publica o site no GitHub Pages
├── site/
│   ├── assets/             # Foto de perfil e logos
│   │   ├── css/
│   │   │   ├── base.css    # Tokens, navegação e estilos compartilhados
│   │   │   └── pages/      # Um stylesheet para cada página
│   │   └── js/
│   │       └── navigation.js # Menu móvel compartilhado
│   ├── index.html          # Página inicial
│   ├── experiencia.html
│   ├── formacao.html
│   ├── projetos.html
│   ├── sobre.html
│   ├── contato.html
│   └── Curriculo.pdf       # PDF disponível para download
└── README.md
```

## Publicação

O workflow em `.github/workflows/pages.yml` publica automaticamente o conteúdo de `site/` no GitHub Pages quando há alterações na branch `main`.

## Licença e uso

Este repositório apresenta o currículo e os materiais profissionais de Arthur Kröning. Para reutilizar o conteúdo pessoal, a foto ou o currículo em PDF, solicite autorização ao titular.
