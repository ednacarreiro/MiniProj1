# MiniProj1 — Curriculum Vitae em Graffiti

**Tarefa 2.2 — Miniprojeto Single Page Application (SPA)**

Projeto académico de uma página única (`index.html`), inspirado num mural de graffiti e desenvolvido com **HTML5, CSS3, JavaScript e Vue.js 3**. A navegação é feita através de ligações internas, sem mudar de página.

## Funcionalidades

- Secções obrigatórias **Quem Sou Eu?**, **O que Faço?** e **Hobbies**.
- Navegação por âncoras e menu responsivo para telemóvel.
- Área de projetos com filtros interativos reativos em **Vue 3** (quando o runtime é carregado).
- Rodapé com ícones de LinkedIn, GitHub, Facebook, Instagram e e-mail, a configurar antes de publicação.
- Adaptação a ecrãs de computador, tablet e telemóvel.
- Respeito pela preferência de movimento reduzido e navegação por teclado.
- Conteúdo curricular selecionado do CV de 2024 e atualizado com informação profissional posterior.

## Estrutura


MiniProj1/
├── index.html                  # Página SPA única
├── docs/			# Pasta com a documentação
│   ├── wireframe.png
│   └── memoria-descritiva-SPA.pdf
├── README.md
├── .gitignore



## Proteção de dados e correções pendentes

Este projeto **não publica morada, data de nascimento, telemóvel, documentos de identificação ou certificados pessoais**.

As redes sociais estão **intencionalmente inativas**: os ícones cumprem o requisito de apresentação visual, mas é necessário adicionar apenas os endereços públicos efetivamente autorizados. Não foram inventados perfis.

Os níveis das barras de competências são decorativos, não são uma autoavaliação numérica ou certificação. Os projetos estão descritos genericamente, sem expor informação institucional reservada.

## O que demonstra a SPA

O documento HTML é único. As navegações utilizam âncoras (`#quem-sou`, `#o-que-faco`, `#hobbies`) e não carregam páginas adicionais. O Vue 3 é utilizado num pequeno componente reativo de filtragem de projetos, preservando o âmbito do miniprojeto.
