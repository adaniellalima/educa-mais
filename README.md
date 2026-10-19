<h1 align="center">Educa+</h1>

<p align="center">
  <img src="img/alunos.png" alt="Três crianças estudando juntas em uma mesa" width="180">
</p>

<p align="center"><em>Reforço escolar voluntário para jovens da comunidade</em></p>

<p align="center">
  <img src="http://img.shields.io/static/v1?label=STATUS&message=PROJETO%201%20CONCLUIDO&color=GREEN&style=for-the-badge" alt="Status: Projeto 1 concluído">
  <img src="http://img.shields.io/static/v1?label=ODS&message=4&color=C5192D&style=for-the-badge" alt="ODS 4">
  <img src="http://img.shields.io/static/v1?label=HTML5&message=VALIDADO&color=E34F26&style=for-the-badge" alt="HTML5 validado">
  <img src="http://img.shields.io/static/v1?label=CSS3&message=VALIDADO&color=1572B6&style=for-the-badge" alt="CSS3 validado">
</p>

## Índice

* [Descrição do projeto](#descrição-do-projeto)
* [Status do projeto](#status-do-projeto)
* [Funcionalidades](#funcionalidades)
* [Acesso ao projeto](#acesso-ao-projeto)
* [Como abrir e rodar o projeto](#como-abrir-e-rodar-o-projeto)
* [Estrutura do projeto](#estrutura-do-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Validação do código](#validação-do-código)
* [Créditos das imagens](#créditos-das-imagens)
* [Integrantes](#integrantes)

## Descrição do projeto

O **Educa+** é um site que conecta jovens voluntários a estudantes da comunidade que precisam de reforço escolar gratuito. Quem sabe uma matéria pode ensinar; quem tem dificuldade pode pedir ajuda, sem pagar nada.

- **Objetivo do serviço:** facilitar o encontro entre voluntários e estudantes para aulas de reforço.
- **Público-alvo:** estudantes do ensino fundamental e médio e jovens dispostos a ensinar como voluntários.
- **ODS atendido:** [ODS 4 – Educação de Qualidade](https://brasil.un.org/pt-br/sdgs/4), que busca assegurar educação inclusiva e equitativa e promover oportunidades de aprendizagem para todos.

Este projeto é a **Etapa 1 (HTML e CSS)** da disciplina Programação Web Front-End da UTFPR.

## Status do projeto

> 🚧 Etapa 1 (HTML e CSS) concluída. A Etapa 2 (JavaScript) ainda não foi iniciada. 🚧

## Funcionalidades

- `Cadastro`: formulário com 5 campos (nome, e-mail, data de nascimento, perfil e senha) para quem quer dar ou receber aulas.
- `Login`: acesso com e-mail e senha, que leva à página principal.
- `Página principal`: apresenta o projeto, explica quem pode participar, mostra como o serviço funciona e o ODS atendido.
- `Layout responsivo`: a página se adapta a telas de celular e de computador.

## Acesso ao projeto

- **Site publicado (GitHub Pages):** https://SEU-USUARIO.github.io/educa-mais/
- **Repositório:** https://github.com/SEU-USUARIO/educa-mais
- **Vídeo de apresentação:** LINK-DO-VIDEO

## Como abrir e rodar o projeto

O projeto usa apenas HTML e CSS, então não precisa instalar nada.

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/educa-mais.git
   ```
2. Abra a pasta no VS Code.
3. Abra o arquivo `index.html` no navegador (ou use a extensão Live Server).
4. Navegue pelo fluxo: cadastro (`index.html`) → login (`login.html`) → página principal (`principal.html`).

## Estrutura do projeto

```
educa-mais/
├── index.html        # Cadastro (5 campos), leva ao login
├── login.html        # Login (e-mail e senha), leva à página principal
├── principal.html    # Página principal do projeto
├── style.css         # Estilos de todas as páginas
├── img/              # Imagens usadas na página principal
├── validacao/        # Prints das validações do W3C
└── README.md
```

## Tecnologias utilizadas

- HTML5 com tags semânticas (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 (variáveis, Grid, Flexbox e media queries)
- Fontes do Google Fonts: Fredoka e Nunito
- Sem frameworks, conforme o enunciado da disciplina

## Validação do código

Os prints das validações estão na pasta `validacao/`:

- [W3C Markup Validator](https://validator.w3.org/) para o HTML
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) para o CSS

## Créditos das imagens

LISTE AQUI A ORIGEM DE CADA IMAGEM (site ou autor) usada em `img/`.

## Integrantes

| [<img src="https://github.com/SEU-USUARIO.png" width="115" alt="Foto de Daniella Lima"><br><sub>Daniella Lima</sub>](https://github.com/SEU-USUARIO) |
|:---:|

Currículo: [Daniella Lima](LINK-DO-CURRICULO)