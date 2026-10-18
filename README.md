<h1 align="center">Hi, I'm Neerav Mishra 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=640&lines=I+build+ML+systems+that+check+their+own+work;Full-stack+products+with+real+tests;Student+at+ABV-IIITM+Gwalior" alt="I build ML systems that check their own work · Full-stack products with real tests · Student at ABV-IIITM Gwalior">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/neerav-mishra-39a779323"><img src="https://img.shields.io/badge/LinkedIn-Neerav%20Mishra-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:itsnjstyle27@gmail.com"><img src="https://img.shields.io/badge/Email-itsnjstyle27%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/ABV--IIITM-Gwalior-1F6FEB?style=for-the-badge" alt="ABV-IIITM Gwalior">
</p>

---

### About me

- 🎓 Student at **ABV-IIITM Gwalior**
- 🧠 I build **machine-learning systems**: AI agents that verify their answers, recommender evaluation on 26M real logs, satellite mapping of Himalayan glacial lakes
- 🛠️ I ship **full-stack products** with Next.js, React, Node.js, FastAPI and PostgreSQL
- 📏 Every project comes with tests and reproducible results, not just a demo
- 📫 Reach me at **itsnjstyle27@gmail.com**

---

## 🤖 AI and machine learning

<table>
<tr>
<td width="45%" valign="top"><a href="https://github.com/itsnjstyle27/darkrai"><img src="https://raw.githubusercontent.com/itsnjstyle27/darkrai/main/docs/assets/screenshots/run-answer.png" alt="Darkrai"></a></td>
<td valign="top">

### [Darkrai](https://github.com/itsnjstyle27/darkrai)
**An AI agent that verifies every answer.** It breaks a goal into a task graph, picks a tool for each
step with a contextual-bandit policy that learns from experience, and has an independent evaluator
check every result. Runs fully offline on its own fine-tuned 22M-parameter language model.

- Tool-choice accuracy on held-out tasks: **89.7% → 100%** after training
- False "verified" answers on blind prompts: **24.4% → 2.4%**

`Python` `PyTorch` `Transformers` `FastAPI` `React` `TypeScript`

</td>
</tr>
<tr>
<td width="45%" valign="top"><a href="https://github.com/itsnjstyle27/counterfact"><img src="https://raw.githubusercontent.com/itsnjstyle27/counterfact/main/results/figures/obd_relative_error.svg" alt="counterfact"></a></td>
<td valign="top">

### [counterfact](https://github.com/itsnjstyle27/counterfact)
**Off-policy evaluation, built from scratch and tested on 26.9M real recommendation logs.**
Seven estimators (IPW, DR, Switch-DR and more), a PyTorch reward model with cross-fitting, and the
full Open Bandit benchmark. The 11.7 GB dataset streams into a 753 MB in-memory format (15× smaller).

- Giving the reward model item identity cuts the direct-method error from **15.0% → 6.7%**

`Python` `PyTorch` `NumPy` `pytest`

</td>
</tr>
<tr>
<td width="45%" valign="top"><a href="https://github.com/itsnjstyle27/moraine"><img src="https://raw.githubusercontent.com/itsnjstyle27/moraine/main/docs/screenshots/explore.png" alt="Moraine"></a></td>
<td valign="top">

### [Moraine](https://github.com/itsnjstyle27/moraine)
**Satellite screening of Himalayan glacial lakes.** Maps every lake each autumn since 1988 from
Landsat and Sentinel-2, scores outburst hazard and simulates the flood downstream. A replay of the
2023 South Lhonak disaster uses only data from before the event.

- **599 lakes** mapped; South Lhonak ranked **3rd of 570** before it burst
- Water classifier: **0.86 F1** on an independent inventory it never trained on

`Python` `LightGBM` `Remote sensing` `React` `MapLibre`

</td>
</tr>
</table>

## 🌐 Full-stack products

<table>
<tr>
<td width="45%" valign="top"><a href="https://github.com/itsnjstyle27/loomcart"><img src="https://raw.githubusercontent.com/itsnjstyle27/loomcart/main/docs/screenshots/recommendations.png" alt="LoomCart"></a></td>
<td valign="top">

### [LoomCart](https://github.com/itsnjstyle27/loomcart)
**A production-style fashion store that learns each shopper's taste.** Catalogue, Razorpay checkout,
back office, and a recommender that explains every pick. A/B analytics with significance tests measure
whether personalisation beats plain popularity.

- **132 automated tests**: 79 unit, 31 integration, 22 end-to-end

`Next.js 16` `TypeScript` `PostgreSQL` `Prisma` `Redis` `Docker`

</td>
</tr>
<tr>
<td width="45%" valign="top"><a href="https://github.com/itsnjstyle27/HealthSync"><img src="https://raw.githubusercontent.com/itsnjstyle27/HealthSync/main/docs/screenshots/timeline.png" alt="HealthSync"></a></td>
<td valign="top">

### [HealthSync](https://github.com/itsnjstyle27/HealthSync)
**One place for a patient's medical records, under the patient's control.** Brings records from
different hospitals together, gives doctors and insurers temporary, scoped access via QR code or OTP,
and reads scanned reports offline with OCR to track follow-ups nobody should miss.

- **182 backend tests**; consent-aware AI assistant over the patient's own records

`React` `Node.js` `Express` `MongoDB` `Socket.IO` `Tesseract.js`

</td>
</tr>
</table>

## 🛠️ Developer tools

<table>
<tr>
<td width="45%" valign="top"><a href="https://github.com/itsnjstyle27/patchwright"><img src="https://raw.githubusercontent.com/itsnjstyle27/patchwright/main/docs/cli.svg" alt="patchwright"></a></td>
<td valign="top">

### [patchwright](https://github.com/itsnjstyle27/patchwright)
**Finds open-source issues worth fixing, including cash bounties, and fixes them.** Works in a
sandboxed agent loop, proves each fix with tests, and writes a clean pull request. Nothing is pushed
until you approve it.

`Python` `Typer` `Anthropic SDK` `Gemini`

</td>
</tr>
</table>

## 🤝 Collaborations

<table>
<tr>
<td width="45%" valign="top"><a href="https://digi-sustain-2026.vercel.app"><img src="assets/digi-sustain.png" alt="DIGI-SUSTAIN 2026"></a></td>
<td valign="top">

### [DIGI-SUSTAIN 2026](https://github.com/SK8-infi/digi-sustain-2026)
**Official website for ABV-IIITM's international conference** on digital transformation for a
sustainable future. Nine pages covering the call for papers, dates, registration and leadership, with
all conference content kept in data files so organisers can update it without touching the layout.

Built with [@aayuxsh326](https://github.com/aayuxsh326) and [@SK8-infi](https://github.com/SK8-infi) · [Live site](https://digi-sustain-2026.vercel.app)

`React` `Vite` `Tailwind CSS` `Vercel`

</td>
</tr>
</table>

---

## 🧰 Tech stack

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Machine learning**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend and data**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Tooling**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

<p align="center">
  <a href="https://www.linkedin.com/in/neerav-mishra-39a779323">LinkedIn</a> ·
  <a href="mailto:itsnjstyle27@gmail.com">Email</a> ·
  <a href="https://github.com/itsnjstyle27?tab=repositories">All repositories</a>
</p>
