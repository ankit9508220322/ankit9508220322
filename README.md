<!-- ============ HEADER BANNER (animated wave) ============ -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=240&color=gradient&customColorList=12,14,18,24&text=Ankit%20Kumar%20Choubey&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Aspiring%20Data%20Analyst%20%7C%20Turning%20Data%20into%20Insights&descSize=18&descAlignY=58" alt="banner" />
</p>

<!-- ============ TYPING ANIMATION ============ -->
<p align="center">
  <a href="https://github.com/ankit9508220322">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=00F7FF&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Ankit+%F0%9F%91%8B;BCA+Student+%F0%9F%8E%93;Aspiring+Data+Analyst+%F0%9F%93%8A;Python+%7C+SQL+%7C+Power+BI+%7C+Excel;Turning+raw+data+into+insights+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ankit9508220322&label=Profile+Views&color=0e75b6&style=for-the-badge" alt="profile views" />
  <a href="https://github.com/ankit9508220322?tab=followers"><img src="https://img.shields.io/github/followers/ankit9508220322?style=for-the-badge&logo=github&color=8957e5" alt="followers" /></a>
  <a href="https://github.com/ankit9508220322?tab=repositories"><img src="https://img.shields.io/badge/Repositories-19-2ea44f?style=for-the-badge&logo=github" alt="repos" /></a>
</p>

<p align="center">
  <a href="https://ankit9508220322.github.io/Shope_meanu/"><img src="https://img.shields.io/badge/🌐_Live_Portfolio-Visit_Now-ff6b6b?style=for-the-badge" alt="portfolio" /></a>
  <a href="https://github.com/ankit9508220322"><img src="https://img.shields.io/badge/GitHub-Ankit_Kumar_Choubey-181717?style=for-the-badge&logo=github" alt="github" /></a>
  <a href="https://www.facebook.com/choubey.ji.731"><img src="https://img.shields.io/badge/Facebook-Connect-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="facebook" /></a>
</p>

---

## 👨‍💻 About Me

```python
class AnkitKumarChoubey:
    def __init__(self):
        self.role      = "Aspiring Data Analyst"
        self.education = "BCA Student"
        self.location  = "Rohtas, Bihar, India 🇮🇳"
        self.skills    = ["Python", "SQL", "Power BI", "Excel", "Data Visualization"]
        self.learning  = ["Advanced SQL", "Power BI", "Machine Learning"]
        self.goal      = "Start my career as a Data Analyst 🎯"

    def say_hi(self):
        print("Thanks for visiting my profile! ⭐")

Ankit = AnkitKumarChoubey()
Ankit.say_hi()
```

---

## 🧊 My 3D Contribution Graph

<!-- Generated automatically by the GitHub Action in workflows/profile-3d.yml -->
name: GitHub-Profile-3D-Contrib

on:
  schedule:
    - cron: "0 18 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v4
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & Push
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add -A .
          git commit -m "chore: update 3D contribution graph" || exit 0
          git push

## 🐍 Contribution Snake

<!-- Generated automatically by the GitHub Action in workflows/snake.yml -->
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

---

## 🛠️ Tech Stack <sub>(click to expand 👇)</sub>

<details open>
<summary><b>🐍 Programming & Data Analytics</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-Exploratory_Data_Analysis-ff9800?style=for-the-badge)

</details>

<details open>
<summary><b>📊 Data Visualization</b></summary>
<br>

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=plotly&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c9ac4?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

</details>

<details>
<summary><b>🗄️ Database</b></summary>
<br>

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</details>

<details>
<summary><b>📑 Office & Productivity</b></summary>
<br>

![Excel](https://img.shields.io/badge/MS_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Word](https://img.shields.io/badge/MS_Word-2B579A?style=for-the-badge&logo=microsoftword&logoColor=white)

</details>

<details>
<summary><b>🌐 Web Technologies</b></summary>
<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</details>

<details>
<summary><b>🚀 Development Tools</b></summary>
<br>

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</details>

---

## 🚀 Featured Projects <sub>(click any card to open the repo)</sub>

<p align="center">
  <a href="https://github.com/ankit9508220322/quiz_project">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ankit9508220322&repo=quiz_project&theme=tokyonight&hide_border=true" alt="quiz_project" />
  </a>
  <a href="https://github.com/ankit9508220322/Calculator_website">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ankit9508220322&repo=Calculator_website&theme=tokyonight&hide_border=true" alt="Calculator_website" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/ankit9508220322/MusicPlayer-">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ankit9508220322&repo=MusicPlayer-&theme=tokyonight&hide_border=true" alt="MusicPlayer" />
  </a>
  <a href="https://github.com/ankit9508220322/make-you-stopwatch-new-projects-">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ankit9508220322&repo=make-you-stopwatch-new-projects-&theme=tokyonight&hide_border=true" alt="Stopwatch" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/ankit9508220322/Pythone_Programe">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ankit9508220322&repo=Pythone_Programe&theme=tokyonight&hide_border=true" alt="Pythone_Programe" />
  </a>
  <a href="https://github.com/ankit9508220322/Age_calculate_project">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ankit9508220322&repo=Age_calculate_project&theme=tokyonight&hide_border=true" alt="Age_calculate_project" />
  </a>
</p>

<details>
<summary><b>📂 More projects & ideas I've built / am building</b></summary>
<br>

| Project | Type |
|---|---|
| 📊 Data Analytics Projects | Python · Pandas · Visualization |
| 📈 Startup Data Analysis | EDA · Insights |
| 🏏 IPL Data Analysis | EDA · Plotly |
| 🌦️ Weather Application | Web / API |
| 🎵 Music Player | HTML · CSS · JS |
| 🧮 Calculator | HTML · CSS · JS |
| 📝 Quiz Application | JavaScript |
| 🔐 Random Password Generator | Python |
| 🌐 Portfolio Website | HTML · CSS |

</details>

---

## 📊 GitHub Stats

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=ankit9508220322&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="stats" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ankit9508220322&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ankit9508220322&theme=tokyonight&hide_border=true" alt="streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=ankit9508220322&theme=tokyo-night&hide_border=true&area=true" alt="activity graph" />
</p>

---

## 📚 Currently Learning

<p align="center">
  <img src="https://img.shields.io/badge/Advanced_SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Data_Analytics-00C853?style=flat-square" />
  <img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Real--world_Data_Projects-8957e5?style=flat-square" />
</p>

## 🎯 Career Goal

> To start my career as a **Data Analyst** and use **Python, SQL, Power BI** and other analytics tools to turn raw data into meaningful insights.

---

## 📫 Let's Connect

<p align="center">
  <a href="https://github.com/ankit9508220322"><img src="https://img.shields.io/badge/GitHub-Ankit_Kumar_Choubey-black?style=for-the-badge&logo=github" /></a>
  <a href="https://ankit9508220322.github.io/Shope_meanu/"><img src="https://img.shields.io/badge/Portfolio-Visit-ff6b6b?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.facebook.com/choubey.ji.731"><img src="https://img.shields.io/badge/Facebook-Connect-1877F2?style=for-the-badge&logo=facebook&logoColor=white" /></a>
  <!-- LinkedIn: apni profile link yaha daalo -->
  <!-- <a href="https://www.linkedin.com/in/YOUR-ID"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a> -->
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1500&color=F7DF1E&center=true&vCenter=true&width=500&lines=%E2%AD%90+Thanks+for+visiting+my+profile!;Let's+turn+data+into+insights+together+%F0%9F%93%8A" alt="thanks" />
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=gradient&customColorList=12,14,18,24" alt="footer" />
