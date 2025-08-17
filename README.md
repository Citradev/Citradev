# 📄 README.md (Copy this into your profile repo)

<!-- Replace EVERY `yourusername` and links with your real ones -->

<h1 align="center">Hi, I'm Shubham 👋</h1>
<p align="center">
  CSE @ MMCOE • Web Dev • Cybersecurity • DSA • Anime enthusiast
</p>

<p align="center">
  <a href="https://komarev.com/ghpvc/?username=yourusername">
    <img src="https://komarev.com/ghpvc/?username=yourusername&style=flat&color=blue" alt="Profile views" />
  </a>
  <a href="https://github.com/yourusername?tab=followers">
    <img src="https://img.shields.io/github/followers/yourusername?style=social" alt="Followers" />
  </a>
  <a href="https://github.com/yourusername?tab=stars">
    <img src="https://img.shields.io/github/stars/yourusername?style=social" alt="Stars" />
  </a>
</p>

---

### 🚀 About Me

* 🧑‍💻 CSE student at **MMCOE, Pune**
* ☕ Coffee-powered (2 cups/day)
* 🛡️ Learning **TryHackMe**, Linux basics & Web Security
* 📚 **GATE prep + Engineering Mathematics**
* 🧪 Building small web apps for fun (Tailwind, JS, React)

### 🧰 Tech I Use

<p>
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
  <img height="32" width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
</p>

### 🔭 Current Focus

* 🎧 Spotify-like dashboard UI (frontend)
* 📅 Anime airing schedule app (HTML + Tailwind + JS)
* 🔍 DSA + Python daily

### 📊 Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername\&show_icons=true\&theme=radical)

![Streak](https://streak-stats.demolab.com?user=yourusername\&theme=radical)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername\&layout=compact\&theme=radical)

### 📌 Featured Projects

<a href="https://github.com/yourusername/repo1">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=yourusername&repo=repo1&theme=radical" />
</a>
<a href="https://github.com/yourusername/repo2">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=yourusername&repo=repo2&theme=radical" />
</a>

### 🐍 Contribution Graph

> After enabling the workflow below, this image will start rendering automatically.

![Snake animation](https://github.com/yourusername/yourusername/blob/output/github-contribution-grid-snake.svg)

### 📫 Connect

* ✉️ Email: [your.email@example.com](mailto:your.email@example.com)
* 🔗 LinkedIn: [https://www.linkedin.com/in/your-link/](https://www.linkedin.com/in/your-link/)
* 🌐 Portfolio: [https://your-portfolio.com](https://your-portfolio.com)

---

## ⚙️ Optional: GitHub Action for the Snake Animation

Create a file at `.github/workflows/snake.yml` in your profile repo with **this exact content** (replace `yourusername`):

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"   # runs every day at 00:00 UTC
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: yourusername
          outputs: |
            dist/github-contribution-grid-snake.svg

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

> Commit the workflow; it will create/update an `output` branch with the SVG. The image URL used above will then show the animated grid.

---

## 🔗 Quick Badge Snippets (Optional)

```md
![Profile Views](https://komarev.com/ghpvc/?username=yourusername&color=blue)
![Followers](https://img.shields.io/github/followers/yourusername?style=social)
![Stars](https://img.shields.io/github/stars/yourusername?style=social)
```

```md
<!-- Pinned repo card (change repo name) -->
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=yourusername&repo=repo-name&theme=radical)](https://github.com/yourusername/repo-name)
```

---

### ✅ Replace Checklist

* [ ] Replace all `yourusername`
* [ ] Put real links for email/LinkedIn/portfolio
* [ ] Change `repo1`/`repo2` to actual projects
* [ ] Commit the Action file if you want the snake
* [ ] Preview the README on GitHub profile
