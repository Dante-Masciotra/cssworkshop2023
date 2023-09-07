---
theme: ./theme
background: >-
  https://images.unsplash.com/photo-1616941482131-489295011919?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjkzNjEwMTU1&ixlib=rb-4.0.3&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## VS Code and WSL Workshop​
drawings:
  persist: false
transition: slide-left
title: VS Code and WSL Workshop​
hideInToc: true
layout: intro
---

<div class="abs-tr m-6 flex gap-2">
  <img src="https://css.uwindsor.ca/images/css-logo-shield.png" width="100"/>
</div>

# VS Code and WSL Workshop​

By: Dante Masciotra and Borhan Saflo

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
hideInToc: true
---

# Meet the Presenters

<div>

  ## Dante Masciotra
  <img src="https://media.licdn.com/dms/image/D5603AQFRwMqQu9pwpA/profile-displayphoto-shrink_200_200/0/1687574028651?e=1698883200&v=beta&t=nsK2U505EGCWTTjxslJmi4jBwOHikRvdNSBeeiJBkQo" style=" border-radius: 50%; float:left; margin: 10px 50px 0px 0px;" />
  <br>
  <br>
  <div class="text-left">

  - 📝 4th Year Student
  - 🎨 Runs a Cooking Instagram Page [@dante.al.dente](https://www.instagram.com/dante.al.dente/) 
  - 🧑‍💻 Winner of Hack The North 2022

  </div>
</div>

<div class="text-right">

  ## Borhan Salfo
  <img src="https://media.licdn.com/dms/image/C5603AQHs9AIshA0psQ/profile-displayphoto-shrink_200_200/0/1658601814664?e=1698883200&v=beta&t=qMjsbI1n3U1PMsMshUPNiMQMalMS51e-igg5XZsxtYM" style=" border-radius: 50%; float:right;  margin: 10px 0px 0px 50px;" />
  <br>
  <br>
 <div dir="rtl">

  - 📝 FACTS ABOUT ME
  - 🎨 FACTS ABOUT ME
  - 🧑‍💻 FACTS ABOUT ME

</div>
</div>

---
layout: default
hideInToc: true
---

# Table of contents

<Toc maxDepth="2"></Toc>

---
transition: slide-up
class: text-center
---

# Visual Studio Code

 ## Visual Studio Code is a code editor made by Microsoft for Windows, Linux and macOS. It offers support for tons of programming languages and highly customizable.​

 <br>
 <img class="rounded mx-auto d-block" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png"  width="200"/>
 <br>

  ## Lets take a look at what we can do
---
transition: slide-left
layout: default
level: 2
---

# File Explorer
  <img class="rounded mx-auto d-block"  x1="0" y1="0" src="/images/FileExplorerVSC.png" />
  <arrow v-click="[1, 2]" x1="200" y1="125" x2="80" y2="125" color="#ff0000" width="5" arrowSize="4" />


---
transition: slide-up
level: 2
---

# Extensions
  <img  class="rounded mx-auto d-block" src="/images/baseVSC.png" />

  <arrow v-click="[1, 2]" x1="200" y1="210" x2="80" y2="210" color="#ff0000" width="5" arrowSize="4" />

---
level: 3
---

# Our Favorite Extensions

VSC has large library of extensions check them out in extensions tab or at **https://marketplace.visualstudio.com/vscode**.

Here are some of our favorites

<div class="text-center" grid="~ cols-2 gap-2" m="-t-2">

<h2>Borhan</h2>

<h2>Dante</h2>

1

Code Runner

2

Git Graph

3

GitLens

</div>


---
class: px-20
transition: slide-up
level: 2
---

# Themes

  <img  class="rounded mx-auto d-block" src="/images/themeVSC1.png" />

  <arrow v-click="[1, 2]" x1="90" y1="350" x2="90" y2="460" color="#ff0000" width="5" arrowSize="4" />
  <arrow v-click="[2, 3]" x1="270" y1="463" x2="140" y2="463" color="#ff0000" width="5" arrowSize="4" />
  <arrow v-click="[3, 4]" x1="430" y1="462" x2="333" y2="462" color="#ff0000" width="5" arrowSize="4" />

---
transition: fade-out
level: 3
---

# Themes

VSC comes with many themes but even more can be found at **https://vscodethemes.com/**.

Here are some of our favorites

<div grid="~ cols-2 gap-2" m="-t-2">

Borhan - Your Favorite

Dante - [Noctics Obescuro](https://vscodethemes.com/e/liviuschera.noctis/noctis-obscuro?language=javascript)

<img border="rounded" src="/images/synthWave.png">

<img border="rounded" src="/images/Noctis.png">

</div>

Look at themes available and pick your favorite but . . . 
<h2 v-click="[1, 2]">FLASH WARNING!!!</h2>

---
level: 3
---

# If You Like This One Then . . . 

<img border="rounded mx-auto d-block" src="/images/lightMode.png">


---
transition: slide-up
level: 2
---

# Remote Explorer
  <img  class="rounded mx-auto d-block" src="/images/sshVSC.png" />

  <arrow v-click="[1, 2]" x1="200" y1="217" x2="80" y2="217" color="#ff0000" width="5" arrowSize="4" />
  <arrow v-click="[2, 3]" x1="270" y1="155" x2="155" y2="155" color="#ff0000" width="5" arrowSize="4" />
  <arrow v-click="[3, 4]" x1="600" y1="117" x2="460" y2="117" color="#ff0000" width="5" arrowSize="4" />

---
level: 3
---

# Remote Explorer Path

<div class="text-center">

```bash
ssh [Username]@cs.uwindsor.ca
```
</div>


---
transition: slide-up
class: text-center
---

# Windows Subsystem for Linux (WSL)

 ## WSL is a feature of Windows that allows you to run a Linux environment without the need for a separate virtual machine or dual booting

 <br>
 <img class="rounded mx-auto d-block" src="/images/WSL.png"  width="200"/>
 <br>

  ## Lets take a look at what we can do
---
layout: default
level: 2
class: text-center 
---
# Install
#### To install WSL run the below command in PowerShell. This will install the default Distro which is the latest version of Ubuntu
<br>

  ```bash
  wsl --intsall
  ```
<br>

#### To look for available Distros 
<br>

  ```bash
  wsl --list --online
  ```
<br>

#### Then to install a desired distro
<br>

 ```bash
 wsl --install -d DISTRO-NAME
  ```

---
layout: default
level: 2
transition: slide-up
class: text-center 
---

# Config

#### If you want to run mutiple Distros than here are some helpful commands to config WSL to your prefences

<br>
To set default Distro
<br>
<br>

  ```bash
  wsl --set-default Distribution-Name
  ```

<br>

#### If forget your password you'll need to run the following commands
<br>

  ```bash
  wsl -u root
  passwd username
  ```
---
layout: default
level: 2
class: text-center 
---

# Run

<br>
To run a WSL in a desired folder open your desired path in CMD or Powershell
<br>
<br>

  ```bash
  C:\your\path> wsl
  ```
<br>
To run a Distro that is not default
<br>
<br>


  ```bash
  C:\your\path> wsl --distribution Distribution Name 
  ```
<br>

---
layout: default
level: 3
transition: slide-up
class: text-center 
---

# What you can while in WSL

<br>

## Now that your in a linux envoriment you have access to all the best linux tools
<div grid="~ cols-2 gap-2" m="-t-2">

  ls
  
  ps
  
  cat

  
  env
  
  killall
  
  ssh

  tail
  
  iptables
  
  cp
  

  sudo
</div>

---
layout: center
class: text-center
level: 3
---

# Thank You for Listening

### Check out the slideshow here
<br>
<img class="rounded mx-auto d-block" src="/images/QR.png"  width="200"/>

<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
/>
<br>
<div class="">
  <a class="fab text-decoration-none m-2 fa-instagram" target="_black" href="https://instagram.com/uwindsorcss"></a>
  <a class="fab text-decoration-none m-2 fa-twitter" target="_black" href="https://x.com/UWindsorCSS"></a>
  <a class="fab text-decoration-none m-2 fa-facebook" target="_black" href="https://facebook.com/uwindsorcss"></a>
  <a class="fab text-decoration-none m-2 fa-github" target="_black" href="https://github.com/uwindsorcss"></a>
</div>
