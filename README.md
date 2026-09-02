# Adaptação de Tipos de Telas

Protótipo/implementação para adaptação de layout a diferentes tipos e tamanhos de tela, mantendo a integridade visual e a usabilidade independente do dispositivo.

Badges
- ![Responsivo](https://img.shields.io/badge/responsive-yes-green)
- ![License](https://img.shields.io/badge/license-MIT-blue)

Sumário
- Sobre
- Demonstração
- Tecnologias
- Funcionalidades
- Como executar
- Estrutura do projeto
- Acessibilidade e responsividade
- Boas práticas
- Como contribuir
- Licença
- Contato

Sobre
Este repositório demonstra abordagens para tornar interfaces adaptáveis a diferentes tamanhos de tela (mobile, tablet, desktop), preservando proporções, legibilidade e comportamento interativo. Pode conter exemplos de CSS (media queries, flexbox, grid), componentes fluidos e patterns para imagens e tipografia.

Demonstração
- Se houver deploy (GitHub Pages, Netlify), adicione o link aqui.
- Para rodar localmente, veja a seção "Como executar".

Tecnologias
- HTML5 semântico
- CSS3 (Flexbox, Grid, Media Queries, unidades responsivas como rem, vw)
- JavaScript leve (opcional — para melhorias de interação)
- Imagens otimizadas (SVG/WebP quando aplicável)

Funcionalidades principais
- Layouts fluidos que se adaptam a diferentes larguras de tela
- Componentes que preservam proporção e alinhamento
- Navegação responsiva (menu colapsável)
- Imagens responsivas (srcset / picture) e lazy-loading (quando aplicável)
- Exemplos de breakpoints práticos e testes de alinhamento

Como executar

Opção 1 — abrir direto no navegador
- Abra o arquivo `index.html` no navegador (bom para protótipos simples).

Opção 2 — servidor HTTP simples (recomendado)
- Python 3:
  ```bash
  python -m http.server 8000
  # abra http://localhost:8000
