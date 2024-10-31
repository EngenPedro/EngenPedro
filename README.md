<h2 align="left">Sobre mim</h2>

###

<p align="left">- Estudante de Analista de Dados<br>- Engenharia de Promtp</p>

###

<img src="https://raw.githubusercontent.com/EngenPedro/EngenPedro/output/snake.svg" alt="Snake animation" />

###

<h2 align="left">Tecnologias</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-line-wordmark.svg" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg" height="40" alt="pycharm logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" height="40" alt="canva logo"  />
</div>

###

<h2 align="left">Estatísticas</h2>

###

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=EngenPedro&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=highcontrast&locale=pt-br&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=EngenPedro&locale=pt-br&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=highcontrast&hide_border=false&order=2" height="150" alt="languages graph"  />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=EngenPedro&radius=16&theme=high-contrast&area=true&order=5" height="300" alt="activity-graph graph"  />

  name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

</div>

###
