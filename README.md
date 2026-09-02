# edusidegum.github.io

Site pessoal estático — página "sobre" de Edu Sidegum, hospedada no GitHub Pages.

## Sobre

Página institucional de apresentação profissional: arquiteto de sistemas e consultor
técnico para pequenos e médios negócios. O site serve como ponto de entrada (landing)
para projetos digitais, com foco em estruturação de dados, visibilidade em mecanismos
de busca tradicionais e generativos, e aplicação criteriosa de IA como ferramenta de
aceleração.

## Estrutura do repositório

/
├── index.html      # Página "sobre" — entry point (retorna 200)
├── robots.txt      # Diretrizes de rastreamento (escopo de domínio)
├── 404.html        # Página de erro customizada
├── sitemap.xml     # Mapa do site para mecanismos de busca
└── assets/         # CSS, JS e imagens


## Stack

- **Hospedagem:** GitHub Pages (estático)
- **Linguagem:** HTML semântico
- **Dados estruturados:** Schema.org (Person / ProfessionalService) via JSON-LD
- **SEO:** sitemap.xml, robots.txt, canonical explícito, E-E-A-T com autoria comprovável
- **Performance:** Core Web Vitals (INP < 200ms), JS mínimo no LCP, sem tracking desnecessário

## Como rodar localmente

Pré-requisito: qualquer servidor HTTP estático (Python, Node, etc.).
```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
