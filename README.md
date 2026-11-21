<h1 align="center">Aryamaan Roy Choudhury</h1>
<h3 align="center">Computer Engineering &amp; Computer Science &nbsp;|&nbsp; Northeastern University</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3200&pause=1100&color=F5A524&center=true&vCenter=true&width=640&lines=Software+engineering+for+sports+and+data;Machine+learning+%2B+quantitative+research;Seeking+a+Spring+2027+co-op+or+Summer+2027+internship" alt="Typing animation" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aryamaan-roy-choudhury-7830b6352/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://aryamaanroychoudhury.com" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-F5A524?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio" />
  </a>
  &nbsp;
  <a href="mailto:roychoudhury.a@northeastern.edu">
    <img src="https://img.shields.io/badge/Email-1F2937?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=Arya85693&style=for-the-badge&color=F5A524&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## About Me

I study Computer Engineering and Computer Science at Northeastern. Most of what I build sits where **sports and data** meet: I take raw match data, turn it into statistical models, test those models honestly against later data and against betting markets, and put the results on live websites that update without manual work.

| | |
|:--|:--|
| 🎓 **School** | Northeastern University · B.S. Computer Engineering & Computer Science · May 2028 |
| 🏅 **Honors** | GPA 3.81 / 4.00 · Dean's List · Eta Kappa Nu |
| 🧠 **Focus** | Sports analytics · Machine learning · Quantitative research · Full-stack development |
| 📍 **Based in** | Boston, MA |
| 🔎 **Looking for** | Spring 2027 co-op or Summer 2027 internship |

---

## Featured Projects

### 🎾 [Matchup DNA](https://www.matchupdna.com)

> **Tennis win probabilities, locked in before the first serve.** A Python research system that rates every ATP and WTA player from their full match history and gives each upcoming match a win probability, with a Next.js site showing the forecasts, what drove them, and how they scored.

**[Live site](https://www.matchupdna.com) · [Code](https://github.com/Arya85693/matchup-dna) · [Research paper](https://www.matchupdna.com/research/big-matches)**

| Result | |
|:--|:--|
| **361k+** | pro matches in the rating history |
| **65.9%** | winners picked across 31,791 matches (2021 – Oct 2026), 1.7 pts above always picking the higher-ranked player |
| **13,846** | matches back-tested against betting-market prices |

| Component | Detail |
|:--|:--|
| Ratings | Elo and surface-adjusted Elo, replayed match by match in date order |
| Models | Logistic regression and LightGBM on opponent-adjusted serve and return features, always tested on later years than they were trained on |
| Market test | Calibration, whether the model adds information to the market price, and simulated betting returns |
| Forecast store | Every forecast is saved before the match starts and never edited afterwards |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

#### 📄 Research paper: *Do Players Choke in Big Matches? Evidence from 26 Years of Professional Tennis*

Does a player's record in big matches (semi-finals, finals, late Grand Slam rounds) tell a forecast anything their Elo rating misses? **No:** big-match records vary about as much as chance predicts, and adding a player's clutch record did not improve out-of-sample forecasts.

| | |
|:--|:--|
| **130,460** | ATP and WTA matches analysed, 2000 – May 2026 |
| **7,476** | big matches forecast out of sample |
| **0 of 18** | trait tests significant after multiple-testing correction |

**[Read on the site](https://www.matchupdna.com/research/big-matches) · [PDF](https://aryamaanroychoudhury.com/research/big-match-choking-paper.pdf)** · *Working paper v4.0, not peer reviewed*

<br/>

### 📈 [Hoops Stock Market](https://hoopsstockmarket.com)

> **An NBA player market where prices move with real games.** Every NBA player has a stock price. A Python pipeline turns game data into player values, and a Next.js site lets you browse the market, see why a price moved, and paper-trade with simulated money.

**[Live site](https://hoopsstockmarket.com) · [Code](https://github.com/Arya85693/NBA-superstar-prediction)**

| Result | |
|:--|:--|
| **91k+** | NBA games processed into player prices |
| **500+** | players priced and tradable |
| **~30 min** | repricing cycle |

| Component | Detail |
|:--|:--|
| Fair Value | Moves slowly with on-court performance, priced from Hollinger Game Score after every game |
| Market Price | Adds projection, demand, sentiment and team context on top of Fair Value |
| Trading | $100k in simulated money per user, with their own login and portfolio |
| Pipeline | Python on GitHub Actions → Supabase (PostgreSQL) → Next.js trading site |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## Experience

| Role | Company | Dates | What I did |
|:--|:--|:--|:--|
| Software Engineering Intern | AdaptSkillAI | Feb – Oct 2026 | Built a learner dashboard, adaptive assessment logic and company registration flows for an adaptive learning platform (Next.js, TypeScript, Zod) |
| Web Development Intern | [StratEdge Africa](https://strat-edge-africa-website.vercel.app/) | Jan – Aug 2026 | Sole developer: designed, built, deployed and maintained the company's live multi-page Next.js website on Vercel *(source private, client project)* |
| Investment Analyst Intern | Weiss Asset Management | Jan – Feb 2022 | Built and presented a simulated $1M portfolio with Monte Carlo and scenario analysis; returned 2–3% above its benchmark |

---

## Other Projects

- **[Dream League Soccer Playstyle Analysis](https://github.com/Arya85693/Dream-League-Soccer-Playstyle-Analysis)**: a Python pipeline that turns Dream League Soccer save data into per-game metrics, role-weighted and reliability-adjusted player rankings, and a similarity-based player prediction checked against later stats.
- **[Supplement Recommender](https://github.com/asrinivasan75/supplement-recommender)** *(team project)*: a full-stack web app that creates personalized supplement plans from a user's profile and goals using the OpenRouter API, with user accounts and saved plans. *(No longer deployed.)*

---

## Technical Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Data, ML & Research**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square&logoColor=white)
![Statistical Inference](https://img.shields.io/badge/Statistical%20Inference-1F2937?style=flat-square&logoColor=white)
![Backtesting](https://img.shields.io/badge/Backtesting-1F2937?style=flat-square&logoColor=white)

**Web & Infrastructure**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## GitHub Activity

<p align="center">
  <img height="165px" src="https://github-readme-stats.vercel.app/api?username=Arya85693&show_icons=true&hide_border=true&bg_color=0D1117&title_color=F5A524&icon_color=F5A524&text_color=C9D1D9&count_private=true&rank_icon=github" alt="GitHub stats" />
  &nbsp;&nbsp;
  <img height="165px" src="https://quickchart.io/chart?w=420&h=165&bkg=%230D1117&c=%7B%27type%27%3A%27horizontalBar%27%2C%27data%27%3A%7B%27labels%27%3A%5B%27%27%5D%2C%27datasets%27%3A%5B%7B%27label%27%3A%27Python%2063.18%25%27%2C%27data%27%3A%5B63.18%5D%2C%27backgroundColor%27%3A%27%233987e5%27%2C%27borderColor%27%3A%27%230D1117%27%2C%27borderWidth%27%3A1%7D%2C%7B%27label%27%3A%27TypeScript%2033.15%25%27%2C%27data%27%3A%5B33.15%5D%2C%27backgroundColor%27%3A%27%23d95926%27%2C%27borderColor%27%3A%27%230D1117%27%2C%27borderWidth%27%3A1%7D%2C%7B%27label%27%3A%27JavaScript%201.28%25%27%2C%27data%27%3A%5B1.28%5D%2C%27backgroundColor%27%3A%27%23199e70%27%2C%27borderColor%27%3A%27%230D1117%27%2C%27borderWidth%27%3A1%7D%2C%7B%27label%27%3A%27CSS%201.17%25%27%2C%27data%27%3A%5B1.17%5D%2C%27backgroundColor%27%3A%27%23c98500%27%2C%27borderColor%27%3A%27%230D1117%27%2C%27borderWidth%27%3A1%7D%2C%7B%27label%27%3A%27PLpgSQL%200.78%25%27%2C%27data%27%3A%5B0.78%5D%2C%27backgroundColor%27%3A%27%23d55181%27%2C%27borderColor%27%3A%27%230D1117%27%2C%27borderWidth%27%3A1%7D%2C%7B%27label%27%3A%27PowerShell%200.43%25%27%2C%27data%27%3A%5B0.43%5D%2C%27backgroundColor%27%3A%27%230ca30c%27%2C%27borderColor%27%3A%27%230D1117%27%2C%27borderWidth%27%3A1%7D%5D%7D%2C%27options%27%3A%7B%27title%27%3A%7B%27display%27%3Atrue%2C%27text%27%3A%27Most%20Used%20Languages%27%2C%27fontColor%27%3A%27%23F5A524%27%2C%27fontSize%27%3A18%2C%27fontStyle%27%3A%27bold%27%2C%27padding%27%3A14%7D%2C%27legend%27%3A%7B%27position%27%3A%27bottom%27%2C%27labels%27%3A%7B%27fontColor%27%3A%27%23C9D1D9%27%2C%27fontSize%27%3A13%2C%27boxWidth%27%3A12%2C%27usePointStyle%27%3Atrue%2C%27padding%27%3A14%7D%7D%2C%27scales%27%3A%7B%27xAxes%27%3A%5B%7B%27stacked%27%3Atrue%2C%27display%27%3Afalse%2C%27ticks%27%3A%7B%27min%27%3A0%2C%27max%27%3A100%7D%7D%5D%2C%27yAxes%27%3A%5B%7B%27stacked%27%3Atrue%2C%27display%27%3Afalse%2C%27barThickness%27%3A12%7D%5D%7D%2C%27plugins%27%3A%7B%27datalabels%27%3A%7B%27display%27%3Afalse%7D%7D%2C%27layout%27%3A%7B%27padding%27%3A%7B%27left%27%3A20%2C%27right%27%3A20%2C%27top%27%3A6%2C%27bottom%27%3A6%7D%7D%7D%7D" alt="Most used languages: Python 63.18%, TypeScript 33.15%, JavaScript 1.28%, CSS 1.17%, PLpgSQL 0.78%, PowerShell 0.43%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Arya85693&hide_border=true&background=0D1117&ring=F5A524&fire=F5A524&currStreakLabel=F5A524&sideLabels=F5A524&dates=C9D1D9&stroke=0D1117" alt="GitHub streak" />
</p>

---

<p align="center">
  <sub>Northeastern University &nbsp;|&nbsp; Boston, MA &nbsp;|&nbsp; Expected Graduation May 2028</sub>
</p>
