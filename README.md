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

```text
MiniProj1/
├── index.html                 # Página SPA única
├── style.css                  # Estilos, graffiti e responsividade
├── app.js                     # Vue 3, menu e interação
├── assets/
│   └── retrato-graffiti.jpg  # Ilustração artística, não fotografia
├── docs/
│   ├── wireframe-aprovado.png
│   └── memoria-descritiva.pdf
├── README.md
├── .gitignore
└── LINK_REPOSITORIO.txt
```

## Executar no Windows (PowerShell)

A forma recomendada é iniciar um pequeno servidor local. A partir da pasta `MiniProj1`:

```powershell
py -m http.server 5500
```

Abrir no Chrome: **http://localhost:5500/**

Para terminar, usar `Ctrl+C`. Em alternativa, pode abrir-se `index.html` diretamente no navegador, embora o servidor local seja mais fiável para testes.

**Importante:** o Vue.js é carregado de `cdn.jsdelivr.net` e a fonte de `fonts.googleapis.com`. Para a experiência completa é necessária ligação à Internet. Sem ligação, a página mantém a estrutura e a navegação, e os filtros usam uma alternativa em JavaScript. Esta contingência não substitui o Vue para efeitos de avaliação.

## Publicar no GitHub

1. Criar um repositório **público** ou com a visibilidade exigida pelo docente, com o nome exato **MiniProj1**.
2. No PowerShell, dentro da pasta do projeto:

```powershell
git init
git branch -M main
git add .
git commit -m "Tarefa 2.2 - SPA curricular em Vue.js"
git remote add origin https://github.com/SEU_UTILIZADOR/MiniProj1.git
git push -u origin main
```

Substituir `SEU_UTILIZADOR` pelo utilizador real e configurar autenticação GitHub quando solicitada. Se o repositório remoto já tiver conteúdo, é preciso integrar esse conteúdo antes de fazer o `push`.

3. Preencher `LINK_REPOSITORIO.txt` com o endereço real.
4. Submeter na plataforma o wireframe, os documentos produzidos e o ficheiro com o link do repositório, conforme o enunciado.

## Proteção de dados e correções pendentes

Este projeto **não publica morada, data de nascimento, telemóvel, documentos de identificação ou certificados pessoais**. O CV fornecido tem informação antiga, complementada com atualizações indicadas pela autora. Rever cuidadosamente as datas, cargos e descrições antes de publicar.

As redes sociais estão **intencionalmente inativas**: os ícones cumprem o requisito de apresentação visual, mas é necessário adicionar apenas os endereços públicos efetivamente autorizados. Não foram inventados perfis.

Os níveis das barras de competências são decorativos, não são uma autoavaliação numérica ou certificação. Os projetos estão descritos genericamente, sem expor informação institucional reservada.

## O que demonstra a SPA

O documento HTML é único. As navegações utilizam âncoras (`#quem-sou`, `#o-que-faco`, `#hobbies`) e não carregam páginas adicionais. O Vue 3 é utilizado num pequeno componente reativo de filtragem de projetos, preservando o âmbito do miniprojeto.
