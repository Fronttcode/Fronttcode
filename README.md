## Olá, mundo! Meu nome é <strong>Jorge</strong>! 👋

<img src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" alt="ilustração de um computador" min-width="400px" max-width="400px" width="400px" align="right">

<p align="left"> 
  Sou Baiano, tenho 25 anos e sou <strong>Front-End Developer</strong>.

Cursando Analise e Desevolvimento de Sistema, Formado em Técnico Administração e atualmente estou aprendendo mais sobre experiência do usuário (UX/UI). Estou sempre empenhado em aprimorar minhas habilidades e aprender coisas novas. 

Estou sempre em busca de desafios e oportunidades para aprender e crescer. Se você estiver interessado em colaborar ou compartilhar ideias, não hesite em entrar em contato comigo. Adoro conhecer novas pessoas e explorar maneiras de tornar o mundo digital um lugar melhor.

<h2 align="left">
 💻 Tecnologias:
</h2>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Git](https://img.shields.io/badge/Git-E34F26?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-2C2D72?style=for-the-badge&logo=figma&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobe-photoshop&logoColor=white)
![Illustrator](https://img.shields.io/badge/Illustrator-FF9A00?style=for-the-badge&logo=adobe-illustrator&logoColor=white)


<p align="left">
  💌 Sinta-se a vontade para entrar em contato: ⤵️
</p>

<a href="https://www.linkedin.com/in/jorge-santos-oliveira-b005bb249/" title="LinkedIn" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

<a href="https://wa.me/+5574991952235" title="WhatsApp" target="_blank">
<img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
<br>
<br>
<table>
  <tr>
    <td>
      <img
        align="left"
        src="https://github-readme-stats.vercel.app/api?username=Fronttcode&theme=dark&hide_border=false&include_all_commits=true&count_private=true"
        alt="Github stats"
      />
    </td>
    <td>
      <img
        align="left"
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=Fronttcode&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact"
        alt="Github stats"
      />
    </td>
    <td>
      <br />
      <img
        align="left"
        src="https://github-readme-streak-stats.herokuapp.com/?user=Fronttcode&theme=dark&hide_border=false"
        alt="Github stats"
      />
    </td>
  </tr>
</table>

<br>

<p align="center">
  <a
    href="https://github.com/ryo-ma/github-profile-trophy"
    title="repositório de troféus"
  >
    <img
      width="800"
      src="https://github-profile-trophy.vercel.app/?username=Fronttcode&column=8&theme=darkhub&no-frame=true&no-bg=true"
    />
  </a>
</p>

<div align="center">
  <h3><b>Profile Visitor Count</b></h3>
</div>

<p align="center">
  <img
    src="https://profile-counter.glitch.me/Fronttcode/count.svg"
    alt="Ilustração do número de visitantes no perfil"
  />
</p>

# snk

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/platane/platane/main.yml?label=action&style=flat-square)](https://github.com/Platane/Platane/actions/workflows/main.yml)
[![GitHub release](https://img.shields.io/github/release/platane/snk.svg?style=flat-square)](https://github.com/platane/snk/releases/latest)
[![GitHub marketplace](https://img.shields.io/badge/marketplace-snake-blue?logo=github&style=flat-square)](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)
![type definitions](https://img.shields.io/npm/types/typescript?style=flat-square)
![code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

Generates a snake game from a github user contributions graph

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image.

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

## Usage

**github action**

```yaml
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
```

[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L26-L33)

If you are only interested in generating a svg, consider using this faster action: `uses: Platane/snk/svg-only@v3`

**dark mode**

For **dark mode** support on github, use this [special syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) in your readme.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```

**interactive demo**

<a href="https://platane.github.io/snk">
  <img height="300px" src="https://user-images.githubusercontent.com/1659820/121798244-7c86d700-cc25-11eb-8c1c-b8e65556ac0d.gif" ></img>
</a>

[platane.github.io/snk](https://platane.github.io/snk)

**local**

```
npm install

npm run dev:demo
```

## Implementation

[solver algorithm](./packages/solver/README.md)
