<!-- Banner Cyber -->

<p align="center">
  <img src="https://i.ibb.co/NsYnyF0/matrix-green.gif" width="740" alt="Matrix Hacker">
</p>

<h1 align="center">💀 rlzy | Python Apprentice 🐍 — Cyber Green Edition</h1>

<p align="center">
  <i>“A Matrix é código. Eu estou aprendendo Python para reescrever as regras.”</i>
</p>

<p align="center">
  <a href="#jogo-cripta-da-gnose">🎮 Jogo</a> •
  <a href="#graficos">📊 Gráficos</a> •
  <a href="#sobre">🧠 Sobre</a> •
  <a href="#setup">⚙️ Setup</a>
</p>

---

## 🔥 Badges & Status

<p align="center">
  <img src="https://img.shields.io/badge/Python-00ff00?style=for-the-badge&logo=python&logoColor=111" />
  <img src="https://img.shields.io/badge/Linux-00ff00?style=for-the-badge&logo=linux&logoColor=111" />
  <img src="https://img.shields.io/badge/Git-00ff00?style=for-the-badge&logo=git&logoColor=111" />
  <img src="https://komarev.com/ghpvc/?username=rlzy&label=visitas&color=00ff00&style=flat" />
</p>

---

## 📊 Gráficos

<p id="graficos"></p>

> Substitua **`rlzy`** nas URLs pelo seu usuário do GitHub se precisar.

<div align="center">

<!-- GitHub Stats -->

<img src="https://github-readme-stats.vercel.app/api?username=rlzy&show_icons=true&hide_title=true&theme=chartreuse-dark" height="150"/>

<!-- Most Used Languages -->

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rlzy&layout=compact&theme=chartreuse-dark" height="150"/>

<!-- Streak -->

<img src="https://streak-stats.demolab.com?user=rlzy&theme=chartreuse-dark&hide_border=false" height="150"/>

<!-- Activity Graph -->

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rlzy&theme=react-dark&area=true&hide_border=true&color=00ff00&line=00ff00&point=00ff00&custom_title=Atividade%20de%20Commits"/>

</div>

---

## 🎮 Jogo: **Cripta da Gnose** (CYOA)

<p id="jogo-cripta-da-gnose"></p>

> Mini‑game **C**hoose **Y**our **O**wn **A**dventure totalmente em Markdown (sem scripts, 100% seguro para README). Clique nas escolhas para avançar.

### 🟢 Início

Você acorda numa sala verde neon. Um terminal pisca: `acessar pleroma?`

* 👉 [Acessar o terminal](#fase-1-terminal)
* 🚪 [Explorar a sala](#fase-1-sala)

### Fase 1 — Terminal

<p id="fase-1-terminal"></p>
O prompt pede uma chave.  
- 🔑 [Digitar `gnosis` e pressionar ENTER](#fase-2-criptografia)  
- ❌ [Errar a chave de propósito](#fim-glitch)

### Fase 1 — Sala

<p id="fase-1-sala"></p>
Você encontra dois itens: um **Manual Python** e uma **Máscara Social**.  
- 📘 [Levar o Manual Python](#fase-2-python)  
- 🎭 [Vestir a Máscara Social](#fim-loop)

### Fase 2 — Criptografia

<p id="fase-2-criptografia"></p>
O terminal pede para decifrar `6861636b2074686520706c65726f6d61`.  
- 🧮 [Converter de HEX para texto](#fase-3-desbloqueio)  
- 🤷 [Ignorar e tentar brute force](#fim-alarme)

### Fase 2 — Python

<p id="fase-2-python"></p>
O manual abre em `input()`, `print()` e `for`.  
- 🐍 [Rodar script de teste](#fase-3-desbloqueio)  
- 💤 [Fechar o livro](#fim-loop)

### Fase 3 — Desbloqueio

<p id="fase-3-desbloqueio"></p>
Você desbloqueia a **Porta Verde**.  
- 🚀 [Entrar no Pleroma](#vitoria)

---

## ✅ Vitória

<p id="vitoria"></p>
> **Você venceu!**

```
   _____ _                    _                 
  / ____| |                  | |                
 | (___ | | ___  _   _  __ _ | |_ ___  ___ _ __
  \___ \| |/ _ \| | | |/ _` || __/ _ \/ _ \ '__|
  ____) | | (_) | |_| | (_| || ||  __/  __/ |   
 |_____/|_|\___/ \__,_|\__,_| \__\___|\___|_|   
```

* 🎯 **Lição**: conhecimento + prática → desbloqueio.
* 💾 **Loot**: snippet Python abaixo para decodificar HEX.

```python
# decode_hex.py — converte hex -> texto
s = "6861636b2074686520706c65726f6d61"
print(bytes.fromhex(s).decode())  # hack the pleroma
```

---

## 🧠 Sobre

<p id="sobre"></p>

```python
class NeoAprendiz:
    stack = ["Python", "Git", "Linux"]
    goals = ["automatizar", "raspar dados", "hacking ético"]

    def level_up(self):
        return "aprender todos os dias"
```

* 🌱 Atualmente: **aprendendo Python**.
* 🔭 Foco: lógica, scripts CLI, requests, automação.
* 🧩 Interesse: ciberestética verde, terminal e minimalismo.

---

## 🐍 Projetos (em progresso)

* `matrix-cli`: utilitários de terminal com verde neon.
* `hex-decoder`: script para converter HEX/BASE64 rapidamente.
* `crawler-lite`: raspador simples com `requests` + `selectolax`.

---

## 🐍🐍 “Snake” das Contribuições (gráfico animado)

> Mostra uma cobrinha comendo seus commits. Ative via GitHub Actions.

**1) Adicione ao README:**

```md
![snake gif](https://github.com/rlzy/rlzy/blob/output/github-contribution-grid-snake.svg)
```

**2) Crie o workflow `.github/workflows/snake.yml`:**

```yml
name: Generate Snake
on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: rlzy
          outputs: |
            dist/github-contribution-grid-snake.svg
      - name: Push snake
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

> Troque **`rlzy`** pelo seu usuário.

---

## ⚙️ Setup rápido (tema verde hacker no perfil)

<p id="setup"></p>

* Use o tema `chartreuse-dark` nas cartas de estatísticas.
* Prefira imagens `.svg` para manter a nitidez no verde.
* Deixe seções curtas e com ícones/ASCII para estética “terminal”.

---

## 🧩 Roadmap de Aprendizado

* [ ] Fundamentos Python (tipos, loops, funções)
* [ ] CLI com `argparse`
* [ ] Requests + scraping
* [ ] Automação de tarefas no Linux
* [ ] Testes com `pytest`

---

<p align="center">
  <img src="https://i.ibb.co/1zpssGb/matrix-skull.gif" width="420" alt="matrix skull"/>
</p>

<p align="center">Feito com 🐍 + 🟢</p>
<!-- Banner Cyber -->
<p align="center">
  <img src="https://i.ibb.co/NsYnyF0/matrix-green.gif" width="600" alt="Matrix Hacker">
</p>

<h1 align="center">💀 rlzy | Neo Coder in Python 🐍</h1>

<p align="center">
  <i>"A Matrix é o código... e eu estou aprendendo a quebrá-lo linha por linha."</i>
</p>

---

## 🧑‍💻 Sobre mim
```python
class Hacker:
    def __init__(self):
        self.name = "rlzy"
        self.learning = "Python"
        self.mission = "Despertar e decodificar a Matrix"

    def __str__(self):
        return f"{self.name} | Estudando {self.learning} | Missão: {self.mission}"

me = Hacker()
print(me)
