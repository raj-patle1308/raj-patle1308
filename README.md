# Hello, I'm Raj Patle! 👋  
### 💻 Aspiring Web Developer & Machine Learning Enthusiast  

Welcome to my GitHub profile! 😊 I’m passionate about **Web Development**, **Machine Learning**, and **Competitive Programming**. I love building intelligent solutions that solve real-world problems.  

---

## 📊 GitHub Stats  
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=raj-patle1308&show_icons=true&theme=radical" width="45%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=raj-patle1308&theme=radical" width="45%" />
</div>  

<br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=raj-patle1308&layout=compact&theme=radical" width="50%" />
</div>  

---

## 🔧 Tech Stack & Tools  
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="40"/>
</p>

---

## 🔗 Connect with Me  
<p align="center">
  <a href="https://www.linkedin.com/in/rajpatle1308/">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="mailto:rajpatlepro1308@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-red?style=for-the-badge&logo=gmail" />
  </a>
  <a href="https://www.instagram.com/rajpatle1308/">
    <img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  <a href="https://discord.gg/YOUR_DISCORD_LINK">
    <img src="https://img.shields.io/badge/-Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" />
  </a>
  <a href="https://codepen.io/rajpatle1308">
    <img src="https://img.shields.io/badge/-CodePen-black?style=for-the-badge&logo=codepen" />
  </a>
  <a href="https://medium.com/@rajpatle1308">
    <img src="https://img.shields.io/badge/-Medium-black?style=for-the-badge&logo=medium" />
  </a>
</p>

<p align="center">
  <img src="https://github.com/raj-patle1308/raj-patle1308/blob/output/github-contribution-grid-snake.svg" />
</p>


---

## 🐍 GitHub Contribution Snake Animation  
### **(Ensure It Loads Properly with GitHub Actions)**  

1️⃣ **Create a new workflow**: Go to **GitHub Actions** in your repo, then create a `.github/workflows/snake.yml` file.  
2️⃣ **Add the following code in `snake.yml`:**  

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"  # Runs daily at midnight
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake
        with:
          github_user_name: raj-patle1308
          outputs: dist/github-contribution-grid-snake.svg
      - uses: actions/upload-artifact@v3
        with:
          name: snake-animation
          path: dist/github-contribution-grid-snake.svg

