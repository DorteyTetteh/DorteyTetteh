![Dortey Tetteh Banner](./assets/DORTEYTETTEH.jpg)


I'm a software engineer who’s passionate about making coding accessible, empowering new developers through mentorship, and using technology to elevate communities.<br>I love simplifying complex tech like JavaScript and React, and helping others stay productive and consistent — especially through live coding sessions, Notion systems, and real-world project guidance.<br><br>Technologies I enjoy working with include React, WordPress, and Jamstack (JavaScript, APIs, Markup).<br>I’m the founder of Deloqistudios, and I also mentor aspiring developers through open-source and frontend projects.<br><br>My mission?<br>To build, teach, and inspire — one line of code at a time.


# 💻 Tech Stack
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)<br/> ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=flat&logo=firebase) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=flat&logo=vercel&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi) ![Next JS](https://img.shields.io/badge/Next-black?style=flat&logo=next.js&logoColor=white) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=flat&logo=SASS&logoColor=white)<br/> ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=flat&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=flat&logo=WordPress&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-a08021?style=flat&logo=firebase&logoColor=ffcd34) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white)

# 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=DorteyTetteh&theme=default&hide_border=false&include_all_commits=false&count_private=false)
![](https://nirzak-streak-stats.vercel.app/?user=DorteyTetteh&theme=default&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=DorteyTetteh&theme=default&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

<!--START_SECTION:waka-->

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}

<!--END_SECTION:waka-->

