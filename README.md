### Hello World!, I'am Felipe Elvas 👋

<!--
**felipeelvas/felipeelvas** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
## Bem-vindo(a) ao perfil do Felipe Elvas 😁

 <div>
   <a href="https://github.com/felipeelvas">
   <img height="180em" src="https://github-readme-stats.vercel.app/api?username=felipeelvas&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
   <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=felipeelvas&layout=compact&langs_count=6&theme=tokyonight"/>

</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>
 
 <br>
 
 # ProjetoBuzzfeed
Click Here to access the quiz. [BuzzFeedClone](https://projeto-buzz-feed-ochre.vercel.app/)

<br>

 # AngularBlog
Project Angular-Blog => [Click Here](https://angular-blog-felipes-projects-8d758913.vercel.app/)
 
  ### Pra conteúdo sobre programação me segue a gente nas redes abaixo!
 
<div> 
    <a href="https://www.instagram.com/felipe_elvas/" target=" _blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
   <a href = "mailto:felipeelvas@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target=" _blank"></a>
  <a href="https://www.linkedin.com/in/felipe-elvas/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 
  ![Snake animation](https://github.com/felipeelvas/Felipe-Elvas/blob/output/github-contribution-grid-snake.svg)

</div>
<div>
  name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: felipeelvas
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
</div>
