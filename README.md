<p align="center">  
  <a href="https://session-generator-bsji.onrender.com">
    <img alt="NEXA" height="300" src="https://files.catbox.moe/rk013i.jpg">
    <h1 align="center">HOPELESS XD</h1>
  </a>
</p>
<p align="center">
<a href="https://github.com/HENRYGOKUGT0"><img title="Author" src="https://img.shields.io/badge/HENRYGOKUGT0-black?style=for-the-badge&logo=Github"></a> <a href="https://chat.whatsapp.com/CkIGluck2EI6zToAmhw2Nw"><img title="Author" src="https://img.shields.io/badge/CHANNEL-black?style=for-the-badge&logo=whatsapp"></a> <a href="https://wa.me/256789810043"><img title="Author" src="https://img.shields.io/badge/CHAT US-black?style=for-the-badge&logo=whatsapp"></a>
<p/>
<p align="center">
<a href="https://github.com/HENRYGOKUGT0?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/HENRYGOKUGT0?label=Followers&style=social"></a>
<a href="https://github.com/HENRYGOKUGT0/HOPELESS-CLONE-XD/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/HENRYGOKUGT0/HOPELESS-CLONE-XD?&style=social"></a>
<a href="https://github.com/HENRYGOKUGT0/HOPELESS-CLONE-XD/network/members"><img title="Fork" src="https://img.shields.io/github/forks/HENRYGOKUGT0/HOPELESS-CLONE-XD?style=social"></a>
<a href="https://github.com/HENRYGOKUGT0/HOPELESS-CLONE-XD/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/HENRYGOKUGT0/HOPELESS-CLONE-XD?label=Watching&style=social"></a>
</p>

####  
# My Awesome Project

Welcome to my awesome project! Here you'll find...
## NOTE DON'T CLONE 🤭

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

Join our WhatsApp group for updates and discussions!

[![WhatsApp group](https://img.shields.io/badge/Join-WhatsApp%20group-25D366?style=for-the-badge&logo=whatsapp)](https://chat.whatsapp.com/CkIGluck2EI6zToAmhw2Nw)
## WhatsApp Support Group 👆

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

## 𝔽𝕠𝕣𝕜 𝕥𝕙𝕖 𝕣𝕖𝕡𝕠
<a href="https://github.com/HENRYGOKUGT0/HOPELESS-CLONE-XD/fork" target="_blank">
  <img src="https://img.shields.io/badge/FORK REPO-black?style=for-the-badge&logo=render" alt="Authenticate With WhatsApp" width="170" height="34">
</a>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

<h2>📌IF YOU WANT THE 𝕊𝕖𝕤𝕤𝕚𝕠𝕟 𝕀𝔻 FOR YOUR NUMBER kindly tap on the above IMAGE👆</h2>
<h1>PLEASE WAIT FOR ABOUT 6-7 MINUTES FOR THE SEVER TO START 😓</h1>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)
#### 𝕕𝕖𝕡𝕝𝕠𝕪𝕞𝕖𝕟𝕥 𝕤𝕖𝕔𝕥𝕚𝕠𝕟
# <a href="https://dashboard.heroku.com/new?template=https://github.com/wasixd/WASI-MD-V"><img title="heroku" src="https://img.shields.io/badge/DEPLOY ON HEROKU-h?color=green&style=for-the-badge&logo=msi"></a>
# <a href="https://railway.app/template/tM2McB?referralCode=v7Xehd"><img title="railway" src="https://img.shields.io/badge/DEPLOY ON RAILWAY-h?color=green&style=for-the-badge&logo=msi"></a>
# <a href="(https://replit.com/github/Itxxwasi/WASI-MD-V"><img title="raplir" src="https://img.shields.io/badge/RAPLIT-h?color=green&style=for-the-badge&logo=msi"></a>
# <a href="https://wasimd-9dedcea2edba.herokuapp.com/"><img title="koyeb" src="https://img.shields.io/badge/DEPLOY ON KYOEB-h?color=green&style=for-the-badge&logo=msi"></a>
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)
## DEPLOY ON PANNEL 
<a href='https://bot-hosting.net/?aff=1260744175356346430' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/DEPLOY -h?color=black&style=for-the-badge&logo=opera' width="96.35" height="28"/></a></p>
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

```
const { spawnSync } = require('child_process')
const { existsSync, writeFileSync } = require('fs')

const SESSION_ID = 'ADD YOUR SESSION ID' // Edit this line only, don't remove ' <- this symbol

if (!existsSync('HENRYGOKUGT0')) {
  console.log('Cloning the repository...')
  const cloneResult = spawnSync(
    'git',
    ['clone', 'https://github.com/HENRYGOKUGT0/HOPELESS-CLONE-XD.git', 'HENRYGOKUGT0'],
    {
      stdio: 'inherit',
    }
  )

  if (cloneResult.error) {
    throw new Error(`Failed to clone the repository: ${cloneResult.error.message}`)
  }

  const configPath = 'HENRYGOKUGT0/config.env'
  try {
    console.log('Writing to config.env...')
    writeFileSync(configPath, `VPS=true\nSESSION_ID=${SESSION_ID}`)
  } catch (err) {
    throw new Error(`Failed to write to config.env: ${err.message}`)
  }

  console.log('Installing dependencies...')
  const installResult = spawnSync('yarn', ['install', '--network-concurrency', '3'], {
    cwd: 'HENRYGOKUGT0',
    stdio: 'inherit',
  })

  if (installResult.error) {
    throw new Error(`Failed to install dependencies: ${installResult.error.message}`)
  }
}

spawnSync('yarn', ['start'], { cwd: 'HENRYGOKUGT0', stdio: 'inherit' })
```
### 𝕋ℍ𝔸ℕ𝕂𝕊 𝕋𝕆
 [`ASTROPED FOR PLUGINS `](https://github.com/astroped)
  [`ibrahim-tech-for-help`](https://github.com/ibrahimaitech)
  



   
## 𝕎𝔸ℝℕ𝕀ℕ𝔾
- 𝘛𝘩𝘪𝘴 𝘣𝘰𝘵 𝘪𝘴 𝘯𝘰𝘵 𝘮𝘢𝘥𝘦 𝘣𝘺 `𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘐𝘯𝘤.` 𝘚𝘰 𝘮𝘪𝘴𝘶𝘴𝘪𝘯𝘨 𝘵𝘩𝘦 𝘣𝘰𝘵 𝘮𝘪𝘨𝘩𝘵 `𝘣𝘢𝘯` 𝘺𝘰𝘶𝘳 `𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘢𝘤𝘤𝘰𝘶𝘯𝘵!`(𝘛𝘩𝘰𝘶𝘨𝘩 𝘺𝘰𝘶𝘳 𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘢𝘤𝘤𝘰𝘶𝘯𝘵 𝘤𝘢𝘯 𝘣𝘦 𝘶𝘯𝘣𝘢𝘯𝘯𝘦𝘥 𝘰𝘯𝘭𝘺 𝘰𝘯𝘤𝘦.)
- 𝘐 𝘢𝘮 𝘯𝘰𝘵 𝘳𝘦𝘴𝘱𝘰𝘯𝘴𝘪𝘣𝘭𝘦 𝘧𝘰𝘳 𝘣𝘢𝘯𝘯𝘪𝘯𝘨 𝘺𝘰𝘶𝘳 𝘢𝘤𝘤𝘰𝘶𝘯𝘵.
- 𝘜𝘴𝘦 𝘢𝘵 𝘺𝘰𝘶𝘳 𝘰𝘸𝘯 𝘳𝘪𝘴𝘬 𝘣𝘺 𝘬𝘦𝘦𝘱𝘪𝘯𝘨 𝘵𝘩𝘪𝘴 𝘸𝘢𝘳𝘯𝘪𝘯𝘨 𝘪𝘯 𝘮𝘪𝘯𝘥.

<h2 align="center">  NOTICE
</h2>
   

██╗░░██╗░█████╗░██████╗░███████╗
██║░░██║██╔══██╗██╔══██╗██╔════╝
███████║██║░░██║██████╔╝█████╗░░
██╔══██║██║░░██║██╔═══╝░██╔══╝░░
██║░░██║╚█████╔╝██║░░░░░███████╗
╚═╝░░╚═╝░╚════╝░╚═╝░░░░░╚══════╝

                                                      
