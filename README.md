<!-- ORBION — GitHub Profile README -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:6366f1,100:020617&height=200&section=header&text=ORBION&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=Self-Hosted%20Multi-Agent%20AI%20Office&descAlignY=58&descSize=20&animation=fadeIn" width="100%"/>

<a href="https://github.com/erdenyagici-cmd/orbion">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=820&lines=A+personal+AI+office+that+runs+on+your+own+server;Multi-agent+orchestration+with+real+evidence;Gemini+%E2%86%92+Groq+%E2%86%92+Cloudflare+%E2%86%92+local+Ollama+failover;Your+data+never+leaves+your+box;Zero+cloud+lock-in.+Zero+per-token+panic." alt="typing"/>
</a>

<br/>

[![ORBION repo](https://img.shields.io/badge/⬡_ORBION-View_the_project-0ea5e9?style=for-the-badge&logo=github)](https://github.com/erdenyagici-cmd/orbion)
[![MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](https://github.com/erdenyagici-cmd/orbion/blob/main/LICENSE)

<br/>

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![Self-Hosted](https://img.shields.io/badge/Self--Hosted-✓-22c55e?style=flat-square)
![Wear OS](https://img.shields.io/badge/Wear%20OS-companion-4285F4?style=flat-square&logo=wearos&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-interface-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-evidence%20model-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-Tunnel%20%2F%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

</div>

---

### 👋 What is this?

I build **ORBION** — a self-hosted *AI office*. One small server becomes a team of
specialized agents: a coordinator that delegates, a coder, a mail archivist, a
researcher — talking to you through **Telegram**, a **live web console**, and a
**Wear OS watch face** that shows your agents working in real time.

> Built on a free-tier ARM VM. No GPU. No vendor lock-in. No per-token anxiety.

<div align="center">

<table>
<tr>
<td align="center" width="33%">🧠<br/><b>Multi-agent</b><br/><sub>Coordinator + specialists,<br/>every call logged with <code>call_id</code></sub></td>
<td align="center" width="33%">🔀<br/><b>LLM pool</b><br/><sub>Gemini → Groq → Cloudflare →<br/>local Ollama, automatic failover</sub></td>
<td align="center" width="33%">🔒<br/><b>Yours</b><br/><sub>Data stays on your box;<br/>no cloud leakage</sub></td>
</tr>
<tr>
<td align="center">⌚<br/><b>Watch-native</b><br/><sub>Wear OS face +<br/>live office companion app</sub></td>
<td align="center">🧾<br/><b>Evidence, not claims</b><br/><sub>"It's done" backed by<br/>a recorded call + status</sub></td>
<td align="center">🩺<br/><b>Trust boundary</b><br/><sub>Battle-tested on a<br/>privacy-first health use case</sub></td>
</tr>
</table>

</div>

### 🩺 A note on the health companion

ORBION's architecture was forged on a **health-critical** use case we deliberately
**do not publish** — personal health data belongs behind a reviewed trust boundary,
not in a public clone. The design (isolated health agent, source-tagged medical
record, evidence-based research with no fabricated citations, wearable ingestion
via short-lived device tokens, hard safety rails, zero cloud leakage) is documented
inside the project. It's the reason ORBION is paranoid about data by default.

### 🚀 Start here

<div align="center">

<a href="https://github.com/erdenyagici-cmd/orbion">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=erdenyagici-cmd&repo=orbion&theme=tokyonight&hide_border=true" />
</a>

</div>

```bash
git clone https://github.com/erdenyagici-cmd/orbion.git
cd orbion && cp .env.example .env   # add your keys
python3 -m venv .venv && . .venv/bin/activate
pip install -r requirements.txt && python3 scripts/agent.py
```

<div align="center">

### 📊 GitHub

<img src="https://github-readme-stats.vercel.app/api?username=erdenyagici-cmd&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=erdenyagici-cmd&theme=tokyonight&hide_border=true" height="150"/>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:6366f1,100:0ea5e9&height=110&section=footer"/>

<sub><i>Your AI should be yours.</i> ⬡</sub>

</div>
