<h1 align="center"> AKASHI-bicho-BOT </h1> 

<a><img src='https://i.imgur.com/gY5LVek.gif'/></a>

<p>Evitez de faire des bêtises les gars merci</p>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=50&pause=1000&color=1BAFBAFF&center=true&width=910&height=100&lines=THANKS FOR CHOOSING+AKASHI-bicho-BOT;MULTI+DEVICE+WHATSAPP+BOT;CREATED+BY+ARTHUR&AKASHI" alt="Typing SVG" /></a>

  
<p align="center">
<a href="https://github.com/AKASHI-SASAKI"><img title="Author" src="https://img.shields.io/badge/SASAKI Bot-black?style=for-the-badge&logo=whatsApp"></a>
<p/>
<p align="center">
<a href="https://github.com/AKASHI-SASAKI?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/AKASHI-SASAKI?label=Followers&style=social"></a>
<a href="https://github.com/AKASHI-SASAKI/AKASHI-bicho-BOT/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/AKASHI-SASAKI/AKASHI-bicho-BOT?&style=social"></a>
<a href="https://github.com/AKASHI-SASAKI/AKASHI-bicho-BOT/network/members"><img title="Fork" src="https://img.shields.io/github/forks/AKASHI-SASAKI/AKASHI-bicho-BOT?style=social"></a>
<a href="https://github.com/AKASHI-SASAKI/AKASHI-bicho-BOT/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/AKASHI-SASAKI/AKASHI-bicho-BOT ?label=Watching&style=social"></a>
</p>

<h3 align="center">AKASHI-BICHO-BOT</h3>
<p align="center">
<a href="#"><img title="Creator" src="https://img.shields.io/badge/Creator-AKASHI&ARTHUR_SASAKI-red.svg?style=for-the-badge&logo=github"></a>
</a>
</p>
<p align="center">
<a href="https://github.com/AKASHI-SASAKI"><img title="Author" src="https://img.shields.io/badge/AKASHI-bicho-BOT-black?style=for-the-badge&logo=Github"></a> <a href="https://chat.whatsapp.com/IdB2EfQiNlKBekQrigN9m9"><img title="Author" src="https://img.shields.io/badge/CHANNEL-black?style=for-the-badge&logo=whatsapp"></a> <a href="https://wa.me/242067274660"><img title="Author" src="https://img.shields.io/badge/CHAT US-black?style=for-the-badge&logo=whatsapp">
<p/>
  
### 1. FORK THIS REPO

<a href='https://github.com/AKASHI-SASAKI/AKASHI-bicho-BOT/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork This Repo-blue?style=for-the-badge&logo=git&logoColor=white'/></a>
<p align="center">

### 2. GET SESSION_ID BY TEAMS SASAKI

### QR CODE.
<a href='https://web-qr-64jj.onrender.com/' target="_blank"><img alt='QR-CODE' src='https://img.shields.io/badge/QR-CODE-Purple?style=for-the-badge&logo=git&logoColor=purple'/></a>
<p align="center">

### PAIRING CODE.
<a href='https://sasaki-md-v2-paire-87pj.onrender.com/' target="_blank"><img alt='PAIR CODE' src='https://img.shields.io/badge/PAIRING-CODE-Red?style=for-the-badge&logo=git&logoColor=white'/></a>
<p align="center">



---

## ⚠️ AVERTISSEMENT ⚠️

. Utilisez ce bot à vos propres risques et périls. et svp éviter les spams je veux dire par là que éviter de signaler notre gît.

---

## DEPLOYEMENT SUR GITHUB 

```yaml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */6 * * *'  # Relance toutes les 6 heures

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Install FFmpeg
      run: sudo apt-get install -y ffmpeg

    - name: Start application with timeout
      run: |
        timeout 21590s npm start  # Limite l'exécution à 5h 59m 50s

    - name: Save state (Optional)
      run: |
        ./save_state.sh


## Contributeurs 🤝

<a href="https://github.com/AKASHI-SASAKI">
  <img src="https://github.com/AKASHI-SASAKI.png" width="200" height="200" alt="AKASHI-SASAKI"/>
</a>
