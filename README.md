# Personal Portfolio

Portfólio pessoal desenvolvido com **HTML5, CSS3 e JavaScript** para apresentar informações profissionais, formação acadêmica, habilidades técnicas e projetos desenvolvidos durante o processo de aprendizado em desenvolvimento web.

O projeto foi criado com foco na aplicação prática dos fundamentos de desenvolvimento front-end, incluindo estruturação semântica, estilização, responsividade, manipulação do DOM e interações com JavaScript.

## Demonstração

**Repositório:**  
https://kallebyalencar.github.io/personal-portfolio/

O projeto pode ser executado localmente diretamente pelo arquivo `index.html`.

## Funcionalidades

### Apresentação

A página inicial apresenta:

- Foto de perfil;
- Nome e apresentação profissional;
- Links para LinkedIn, GitHub e e-mail;
- Áudio de apresentação.

### Skills

Seção destinada à apresentação de habilidades técnicas e profissionais.

Entre elas:

- HTML5;
- CSS3;
- PostgreSQL;
- Git + GitHub;
- Comunicação;
- Colaboração;
- Adaptabilidade;
- Proatividade.

### Formação acadêmica

Apresentação das instituições e cursos realizados:

- **Microlins** — Pacote Office;
- **Instituto Federal do Ceará** — Técnico em Eletrotécnica;
- **Centro Universitário Paraíso** — Análise e Desenvolvimento de Sistemas.

### Projetos

A seção de projetos reúne aplicações desenvolvidas durante os estudos:

- **Calculadora** — calculadora web interativa desenvolvida com HTML, CSS e JavaScript;
- **Tesla** — interface inspirada no site da Tesla, desenvolvida com HTML e CSS;
- **Cafeteria** — página inspirada em cafeterias modernas, desenvolvida com HTML e CSS;
- **Monitoramento de Ruído** — aplicação desenvolvida com HTML, CSS e PHP para simulação do monitoramento de níveis de ruído urbano.

### Tema claro e escuro

A aplicação possui alternância entre tema claro e escuro.

A preferência selecionada pelo usuário é armazenada no navegador utilizando `localStorage`, permitindo que o tema seja mantido após atualizar ou retornar à página.

### Navegação

A página utiliza navegação interna entre suas diferentes seções, com rolagem suave e ajuste da posição considerando o cabeçalho fixo.

## Tecnologias utilizadas

### HTML5

Utilizado para estruturar semanticamente o conteúdo da aplicação.

Entre os principais elementos utilizados estão:

```html
<header>
<nav>
<main>
<section>
<article>
<figure>
<footer>
<audio>
<details>
<summary>
```

### CSS3

Utilizado para construir o layout, identidade visual e responsividade da aplicação.

Principais recursos utilizados:

- Variáveis CSS;
- Flexbox;
- CSS Grid;
- Responsividade;
- Pseudo-classes;
- Transições;
- Aspect ratio;
- Barras de progresso;
- Organização dos estilos em arquivos separados.

O projeto utiliza variáveis CSS para centralizar as principais cores da interface:

```css
:root {
    --fundo-principal: #f5f5f5;
    --texto: #222222;
    --texto-inverso: #ffffff;
    --destaque: #0077ff;
    --destaque-inverso: #66bbff;
    --fundo-card: #ffffff;
}
```

### JavaScript

Utilizado para adicionar interatividade à aplicação.

Principais funcionalidades:

- Alternância entre tema claro e escuro;
- Persistência do tema com `localStorage`;
- Alteração do ícone do botão de tema;
- Rolagem suave entre as seções;
- Manipulação do DOM;
- Eventos de interação.

## Organização dos estilos

Os estilos estão separados em arquivos para facilitar a organização e manutenção do projeto:

```text
css/
├── reset.css
├── responsive.css
└── style.css
```

### `reset.css`

Responsável pela normalização dos estilos padrão dos elementos HTML.

### `style.css`

Contém os principais estilos da aplicação, incluindo layout, componentes, cores, cards, menus, projetos e demais elementos visuais.

### `responsive.css`

Contém as regras responsáveis pela adaptação da interface para diferentes tamanhos de tela.

## Estrutura do projeto

```text
personal-portfolio/
├── assets/
│   ├── files/
│   │   └── apresentacao.mp3
│   │
│   └── img/
│       ├── *.png
│       ├── *.jpg
│       └── *.svg
│
├── css/
│   ├── reset.css
│   ├── responsive.css
│   └── style.css
│
├── js/
│   └── script.js
│
├── index.html
└── README.md
```

A pasta `assets` contém imagens, ícones e o arquivo de áudio utilizados pela aplicação.

## Como executar

O projeto é uma aplicação front-end sem dependências de backend.

Não é necessário instalar PHP, banco de dados, Node.js ou outros pacotes para executá-lo.

### 1. Clonar o repositório

```bash
git clone https://github.com/kallebyalencar/personal-portfolio.git
```

### 2. Entrar no diretório

```bash
cd personal-portfolio
```

### 3. Executar

Abra o arquivo:

```text
index.html
```

em um navegador moderno.

Também é possível utilizar o **Visual Studio Code** com a extensão **Live Server** para executar o projeto através de um servidor local.

## Responsividade

A aplicação possui regras específicas para diferentes tamanhos de tela através do arquivo:

```text
css/responsive.css
```

O layout utiliza **CSS Grid** e **Flexbox** para organizar os diferentes elementos da interface de forma responsiva.

## Design e identidade visual

A interface utiliza uma identidade visual baseada em tons claros, azul como cor de destaque e componentes organizados em cards.

Entre as características visuais estão:

- Layout baseado em cards;
- Cor azul para elementos de destaque;
- Bordas arredondadas;
- Barras de progresso;
- Ícones;
- Efeitos de hover;
- Transições;
- Tema claro e escuro;
- Layout responsivo.

## Limitações

As barras de skills possuem finalidade visual e representam uma estimativa das habilidades apresentadas, não constituindo avaliações objetivas ou certificações de proficiência.

O projeto não possui backend ou banco de dados integrado, pois seu objetivo é a apresentação pessoal e a prática de desenvolvimento front-end.

## Status

**Concluído** — projeto desenvolvido como parte dos estudos de desenvolvimento web e utilizado como portfólio pessoal.

## Autor

**Kalleby Alencar**

Estudante de Análise e Desenvolvimento de Sistemas e desenvolvedor em formação, com foco em desenvolvimento web e construção de fundamentos sólidos em programação.

**GitHub:**  
https://github.com/kallebyalencar

## Licença

Este projeto foi desenvolvido para fins educacionais e de portfólio.

Imagens, ícones, fontes, bibliotecas e outros recursos de terceiros utilizados no projeto permanecem sujeitos às respectivas licenças e direitos de seus proprietários.
