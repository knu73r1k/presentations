---
marp: true
size: 16:9
theme: bouvet
footer: Fagkaffi 20th July 23 - CDE (Cloud Development Environment) / Ephemeral workspaces
paginate: true  
---
<!-- _class: lead -->
![bg right:42%](./resources/zabou-2290189_1280.jpg)
# Always ready to code!
###### `CDE - Cloud Development Environment`
>Treat your infrastructure<br>as cattle 🐮, not pets 🦮

---
<style scoped>
section blockquote {
  font-size: 1.5rem;
  text-align: center;
  vertical-align: center;
  margin-top: 1rem;
}
</style>
![bg opacity:.3](./resources/street-art-1183812_1280.jpg)
><br>I think the shift to the cloud will happen at such a rapid rate, that in a few years, I predict there will be no more source code on your computers.<br><br>

Thomas Dohmke (2022), CEO GitHub

---
![bg opacity:.3](./resources/peace-g3bf9dbf34_1280.jpg)
## Learning objectives 👩🏽‍🏫

* 👨🏼‍💻 Awaken curiousity for a better way of maintaining dev environments
* 😈 Provoke us to transform 🧙🏼‍♂️ our pets 🦮 to cattles 🐮
* 👩🏽‍💻 Demo CDE - _ready to code_ from zero to fully operative
* 🤩 Inspire to explore
  - `Developer eXperince` / `Cloud Development Environment`

---
![bg opacity:.2](./resources/graffiti-508272_1920.jpg)
# DevX - Developer eXperience
<br><br>

>Developer experience refers to how easy or difficult it is for a developer to perform essential tasks needed to implement a change. <br><br>A positive developer experience would mean these tasks are relatively easy for the team.

---
![bg opacity:.2](./resources/mural-4121994_1280.jpg)
# Cloud happened

* Virtual Machines - gained momentum late 90-ties
* Transformation to Cloud computing - (AWS 2006)
* Containerisation - Docker / Kubernetes - (2014)
* Ephemeral workspaces or CDEs - Now!

---
![bg opacity:.1](./resources/street-art-2044085_1280.jpg)
# What is CDE
<br><br>

>Cloud development environments are on-demand and pre-configured with all tools, libraries and dependencies required to be ready-to-code.

---
![bg opacity:.1](./resources/street-art-465304_1280.jpg)
# Cloud Development Enivronments - principles

* **Ephemeral** over _long lived_
  - A fresh disposable environment for every task
* **Reproducible** over _cobbled together_
  - Consistently replicable without manual intervention
* **Effortless** over _arduous_
  - With minimal friction and difficulty

---
![bg opacity:.2](./resources/face-2089059_1280.jpg)
# Vision
<br>
From :

Select project, check dependencies, checkout branch, view readme.txt, install tools, run build, run test, start coding.

---
![bg opacity:.2](./resources/face-2089059_1280.jpg)
# Vision
<br>
To :

Select project,
~~check dependencies, checkout branch, view readme.txt, install tools, run build, run test,~~
start coding.

---
<style scoped>
section h1 {
  font-size: 5.5rem;
}
</style>
![bg opacity:.2](./resources/graffiti-g33e6f651e_1280.jpg)
<!-- _class: lead -->
# DEMO

gitpod.io<br>CDE - Cloud Development Environment
<br>
"Pod's = containers" hosted on a Kubernetes environment