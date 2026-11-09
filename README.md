## Hi there 👋
I'm Sotimboyev Sadulla

<p align="center">
  

 <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="3px">
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:000000,50:4CAF50,100:000000&text=Hii%20I'm%20Sotimboyev%20Sadulla%20Welcome%20to%20my%20GitHub%20profile!&fontSize=30&fontColor=39FF14&animation=twinkling&fontAlignY=38"/>
</p>

 <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="3px">
<h1 align="center" style="color:#39FF14; text-shadow: 0 0 8px #39FF14, 0 0 20px #39FF14;">


<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=2800&pause=900&color=00F260&center=true&vCenter=true&width=820&lines=;I'm%20Al-xorazmiy+vorislari+IT+Student" />
</p>
### 🌐 Men bilan bog'lanish:

<p align="center">
  <a href="https://t.me/Sotimboyev_7" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
<h3 align="center">🎮 GitHub Faollik O'yini (Snake Game)</h3>
name: Generate Snake Animation

on:
  # Har 24 soatda avtomatik ishlaydi
  schedule:
    - cron: "0 0 * * *"
  
  # Qo'lda ham ishga tushirish imkoniyati
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    
    steps:
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}






