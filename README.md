
```python
import snk
import badges

def about_me():
    greeting = "Olá Mundo!"
    name = "Francisco Pereira"
    alias = "ffarps"
    role = "Software Developer"
    focus = "Driving Innovation with AI & Machine Learning"
    debug = "Debugging one line at a time until I find the damn error"

def tech_stack():
    os = ["Debian", "Arch Linux"] #🐧
    interests = ["💻 FOSS Advocate", "🤖 AI/ML", "🔐 Cybersecurity"]
    
def portfolio():
    url = "https://ffarps.github.io/"
    description = "Visit My Portfolio"
    portfolio=f"🔗 {description}: {url}"
    return badges(portfolio)

def current_projects():
    projects = "https://ffarps.github.io/#Projects"
    
def snake():
    config="snake.yml"
    return snk(config)

def acknowledgments():
    snake="https://github.com/Platane/snk"
    badges="https://github.com/Envoy-VC/awesome-badges#contents"
    avatar="Avatar by Midjourney AI - cyberpunk choom with vr headset"
    return badges(snake,badges,avatar)

portfolio()
snake()
acknowledgments()
```
<br>
<div>
  <div align="center">
    <a href="https://ffarps.github.io/" target="_blank">
      <img src="https://img.shields.io/badge/Visit_My-Portfolio-1abc9c?style=for-the-badge&logo=hyper&logoColor=white" alt="Portfolio Badge"/>
    </a>
  </div>
  
  <br>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ffarps/ffarps/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ffarps/ffarps/output/github-contribution-grid-snake.svg">
    <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/ffarps/ffarps/output/github-contribution-grid-snake.svg">
  </picture>
  
  <br/>
  <a href="https://github.com/Platane/snk" target="_blank">
      <img src="https://img.shields.io/badge/Snake-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Snake Game"/>
  </a>
  <br/>
  <a href="https://github.com/Envoy-VC/awesome-badges#contents" target="_blank">
      <img src="https://img.shields.io/badge/Awesome_Badges-100000?style=for-the-badge&logo=github&logoColor=white" alt="Awesome Badges"/>
  </a>
  <br/>
  <img src="https://img.shields.io/badge/Avatar by Midjourney AI cyberpunk choom with vr headset-100000?style=for-the-badge&logo=hyper&logoColor=white" alt="Avatar"/>
  <!--<em>Avatar by Midjourney AI cyberpunk choom with vr headset</em>-->
</div>
