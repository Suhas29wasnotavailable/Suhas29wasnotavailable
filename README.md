<div align="center">

<img src="./assets/matrix-header.svg" width="100%" alt="Suhas — AI/ML Engineer" />

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3400&pause=1000&color=3FB950&center=true&vCenter=true&random=false&width=720&height=40&lines=Stylometry%3A+who+wrote+this+code%3F;Python+%C2%B7+scikit-learn+%C2%B7+FastAPI;And+fast%2C+motion-heavy+front-ends" alt="" />
</a>

<br/>

<a href="https://suhasy.vercel.app"><img src="https://img.shields.io/badge/Portfolio-3FB950?style=for-the-badge&logo=vercel&logoColor=0D1117&labelColor=3FB950" alt="Portfolio" /></a>
<a href="mailto:ys.suhas29@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=56D364&labelColor=0D1117&color=1F6F35" alt="Email" /></a>

<br/><br/>

<a href="https://suhasy.vercel.app">
  <img src="./assets/enter-portfolio.svg" alt="View the portfolio" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Suhas29wasnotavailable&label=Profile%20views&color=3FB950&style=flat-square" alt="" />

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## About

```console
$ whoami
Suhas — AI/ML engineer

$ cat focus.txt
classifiers · feature engineering · APIs · motion-heavy front-ends
```

I build ML tools, and the interfaces that make them usable.

Right now that means **CodePatternAnalyzer** — a classifier that works out who wrote a
Python file from style alone, by pairing AST structure (nesting depth, branching,
function density) with character n-grams. And front-ends that stay fast while doing a
lot of motion.

The parts I care about are the ones that are easy to skip: honest evaluation, structure
someone else can read, and being clear about what a model *can't* do.

<img src="./assets/divider.svg" width="100%" alt="" />

## Stack

<div align="center">

<img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/scikit--learn-0D1117?style=for-the-badge&logo=scikitlearn&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/NumPy-0D1117?style=for-the-badge&logo=numpy&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/Pandas-0D1117?style=for-the-badge&logo=pandas&logoColor=56D364&labelColor=0D1117&color=1F6F35" />

<img src="https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/Three.js-0D1117?style=for-the-badge&logo=threedotjs&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/GSAP-0D1117?style=for-the-badge&logo=greensock&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/Tailwind-0D1117?style=for-the-badge&logo=tailwindcss&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/Vite-0D1117?style=for-the-badge&logo=vite&logoColor=56D364&labelColor=0D1117&color=1F6F35" />

<img src="https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git&logoColor=56D364&labelColor=0D1117&color=1F6F35" />
<img src="https://img.shields.io/badge/Vercel-0D1117?style=for-the-badge&logo=vercel&logoColor=56D364&labelColor=0D1117&color=1F6F35" />

<br/><br/>

<img src="./assets/capability-matrix.svg" width="100%" alt="Skills breakdown" />

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## Projects

| Project | What it does | Built with |
|:--------|:-------------|:-----------|
| **[CodePatternAnalyzer](https://github.com/Suhas29wasnotavailable/CodePatternAnalyzer)** · [demo](https://code-pattern-analyzer.vercel.app) | Identifies who wrote a piece of Python from style alone — character n-grams plus AST structure (depth, branching, function density) through an MLP classifier. | `Python` `scikit-learn` `FastAPI` |
| **[portfolio](https://github.com/Suhas29wasnotavailable/portfolio)** · [live](https://suhasy.vercel.app) | My personal site — motion, smooth scroll and a WebGL scene, built to stay fast. | `React` `Three.js` `GSAP` `Tailwind` |
| **[gauri-khetan-portfolio](https://github.com/Suhas29wasnotavailable/gauri-khetan-portfolio)** | Portfolio site built for a product / visual / brand designer. | `JavaScript` `CSS` |

<br/>

<details>
<summary><b>&nbsp;🔴&nbsp; Red pill — the longer version</b></summary>

<br/>

| Layer | Weapon of choice |
|:------|:-----------------|
| **Editor** | Neovim, and a config I haven't read in three years |
| **Terminal** | Ghostty · tmux · zsh |
| **Machine** | macOS for the day job, Linux for anything that matters |
| **Notebooks** | Jupyter for thinking. Everything graduates to a `.py` file. |
| **Deploy** | Docker → GitHub Actions → whichever cloud is cheapest that quarter |

**Opinions I'll defend**

- Most ML problems are data problems wearing a trench coat.
- If your eval set was built after your model, it isn't an eval set.
- The best architecture is the one the next person can reason about at 3am.
- Notebooks are for thinking, not for shipping.

**Currently working through**

- Giving CodePatternAnalyzer an honest train/test split and a real accuracy number
- Widening the corpus past 5 authors without the classifier falling over
- Getting WebGL scenes to stay smooth on a mid-range phone

</details>

<details>
<summary><b>&nbsp;🔵&nbsp; Blue pill — the short version</b></summary>

<br/>

He writes Python. It works. Nobody knows why.

</details>

<img src="./assets/divider.svg" width="100%" alt="" />

## GitHub

<div align="center">

<img height="180" src="https://streak-stats.demolab.com?user=Suhas29wasnotavailable&hide_border=true&background=0D1117&stroke=1F6F35&ring=3FB950&fire=56D364&currStreakLabel=3FB950&sideLabels=8B949E&dates=8B949E&currStreakNum=E6EDF3&sideNums=E6EDF3" alt="Contribution streak" />
<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Suhas29wasnotavailable&theme=github_dark" alt="Repos per language" />

<br/>

<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Suhas29wasnotavailable&theme=github_dark&utcOffset=5.5" alt="Productive time" />

<br/><br/>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">

### Open to interesting problems

If you're building something that shouldn't work yet, I'd like to hear about it.

<a href="https://suhasy.vercel.app">
  <img src="./assets/enter-portfolio.svg" alt="View the portfolio" />
</a>

<br/><br/>

<sub>🐇 <i>Follow the white rabbit.</i></sub>

</div>
