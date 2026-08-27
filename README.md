<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0221,40:2d0057,100:6B21A8&height=260&section=header&text=%20Woony&fontSize=48&fontColor=E9D5FF&fontAlignY=38&desc=math%20%E2%86%92%20cryptography%20%E2%86%92%20AI%20%E2%80%94%20same%20proof,%20different%20language&descFontSize=16&descFontColor=C4B5FD&descAlignY=58&animation=fadeIn" />
<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=C084FC&center=true&vCenter=true&multiline=true&width=720&height=90&lines=proving+things+since+2021+%F0%9F%94%90;shipping+things+since+2024+%F0%9F%9A%80;still+debugging+both" alt="Typing SVG" />

<br/><br/>

<a href="https://www.linkedin.com/in/woony/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/Leegwangwoon"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="https://velog.io/@woony/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white"/></a>
<a href="mailto:leegwangwoon@naver.com"><img src="https://img.shields.io/badge/Email-03C75A?style=flat-square&logo=naver&logoColor=white"/></a>
<a href="mailto:woony@artygenspace.com"><img src="https://img.shields.io/badge/Work-6B21A8?style=flat-square&logo=protonmail&logoColor=white"/></a>

</div>

<br/>


```
$ cat about_me.yaml
```

```yaml
name:        Woony
currently:   AI Lab Lead @ ArtygenSpace
stack:       [LLM, RAG, TTS/STT, ZKP, on-prem infra]
credo:       "수학적 이론 기반의 견고한 AI 시스템 설계"
education:
  - M.S. Mathematics (Cryptography)
published:   [IEEE TIFS '23, IEEE Blockchain '22, KMS Spring Conf '22]
patents:     2 registered software copyrights (KR)
```

<br/>

<h2>🗺️ career.map()</h2>

<table width="100%">
<tr>
<th align="left" width="20%">when</th>
<th align="left" width="24%">where</th>
<th align="left">what</th>
</tr>
<tr valign="top">
<td><code>2025.08 →</code><br/><sub>now</sub></td>
<td>🟣 <b>ArtygenSpace</b><br/><sub>AI Lab Lead</sub></td>
<td>

Selected for **KOITA**'s SME Emerging Researcher Recruitment Support Program <sub>(2026.06 → present)</sub>
Delivered on the **2025 AI Content Production Support Program**, sponsored by KOCCA <sub>(2025.08 – 2025.11)</sub>

</td>
</tr>
<tr valign="top">
<td><code>2024.12 – 25.06</code><br/><sub>SK Networks</sub></td>
<td>🟢 <b>Family AI Camp</b><br/><sub>LLM Service Developer</sub></td>
<td>

Full-cycle build of an in-house LLM automation suite — 4 services (meeting-minutes, doc QA, complaint response, call analysis) on a fully on-prem RAG stack
Built a multilingual museum docent chatbot: fine-tuned Qwen2.5-7B, RAG w/ FAISS, shipped with live TTS in 3 languages

</td>
</tr>
<tr valign="top">
<td><code>2023.03 – 11</code><br/><sub>9 mo · Seoul</sub></td>
<td>🔷 <b>Lightscale</b><br/><sub>Blockchain Researcher (Intern)</sub></td>
<td>

Built a pairing-based digital signature scheme on top of `herumi/mcl` + `PBC`, prototyped in raw C++
Surveyed state-of-the-art ZKP techniques and proposed protocol-level improvements

</td>
</tr>
<tr valign="top">
<td><code>2021.09 – 22.02</code><br/><sub>6 mo · USA</sub></td>
<td>🔶 <b>Notre Dame</b><br/><sub>Visiting Researcher</sub></td>
<td>

Dispatched under **IITP**'s Global Core Talent Development Program (2021 cohort) — a national program sending Korean grad students to top overseas labs
Shipped a blockchain data-provenance monitoring system → later published

</td>
</tr>
</table>

<br/>

<h2>⚡ what_i_actually_build</h2>

<table width="100%">
<tr>
<td width="25%" valign="top">

**🔊 voice**
> making machines sound less like machines

- Korean TTS on VITS / SoVITS, 500+ multilingual voice-actor datasets
- Zero-shot voice cloning w/ speaker preservation
- WhisperX-based STT for real-time transcription
- OCR+LLM+TTS audiobook pipeline → 🇯🇵 🇺🇸 app stores

</td>
<td width="25%" valign="top">

**🤖 agents**
> giving machines something to reason about

- On-prem infra for Qwen / LLaMA, GPU-tuned
- RAG pipelines: LangChain, LangGraph, Qdrant, FAISS
- Fine-tuned Qwen2.5-7B → published to 🤗 Hugging Face
- 4-in-1 enterprise LLM suite, load-tested (Locust)

</td>
<td width="25%" valign="top">

**🔐 proofs**
> the part where math pays rent

- Bulletproofs-based **Leopard** protocol → IEEE TIFS 2023
- Pairing-based signature schemes (`mcl`, `PBC`)
- Sublinear verifiers under the DL assumption
- OSS contributor: `tachyon`, `arkworks-rs`

</td>
<td width="25%" valign="top">

**🌐 full-stack**
> because a model with no UI helps no one

- React + Vite frontends, FastAPI 
- Docker, AWS EC2, RunPod deployment
- REST APIs wiring LLM ↔ vector DB ↔ frontend end-to-end

</td>
</tr>
</table>

<h2>📄 papers_and_patents</h2>

```
[2023.08]  Leopard: Sublinear Verifier Inner Product Argument
           under Discrete Logarithm Assumption
           → IEEE Transactions on Information Forensics and Security

[2022.09]  Monitoring Provenance of Delegated Personal Data
           with Blockchain
           → IEEE International Conference on Blockchain 2022

[2022.05]  대한수학회 춘계 학술대회 — conference talk

[C-2024-042161]  Pairing-based ZKP protocol for proving/verifying
                  computation results — registered software copyright

[C-2024-032025]  Range-proof protocol using pairing-based ZKP
                  — registered software copyright
```

<br/>

<h2>🏛️ funded_research (national R&D grants)</h2>

| project | sponsor | when |
|---|---|---|
| ZKP for privacy-preserving searchable blockchain provenance logs | IITP | 2021.05 – 2022.04 |
| SNARK — cryptographic foundation tech | IITP | 2021.04 – 2023.03 |
| Quantum-resistant one-way ZKP methods | NRF Korea | 2021.05 – 2023.03 |
| [Samsung Future Tech] Multi-party approximate computation crypto | SNU R&DB Foundation | 2022.07 – 2023.03 |
| Multi-layer blockchain log storage + ZKP | IITP | 2022.05 – 2023.03 |
| Cryptographic proof systems for Proof-Carrying Data | ETRI/NSR | 2022.05 – 2022.10 |
| Next-gen anti-piracy & secure content distribution (int'l joint research) | KOCCA | 2024.04 – 2024.12 |

<br/>

<h2>🧰 stack.json</h2>

<p align="center">
<img src="https://skillicons.dev/icons?i=python,cpp,rust,go,c,react,vite,js,html,css,django,fastapi,postgres,mysql,linux,docker,aws,git,pytorch,huggingface&theme=dark" />
</p>

**cryptography**
<p align="center">
<img src="https://img.shields.io/badge/mcl-herumi-0F172A?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PBC-Pairing--Based%20Crypto-0F172A?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ZKP-Bulletproofs-0F172A?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SNARK-Succinct%20Proofs-0F172A?style=for-the-badge"/>
</p>

**LLM / RAG / speech**
<p align="center">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Qwen2.5-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Llama_3.2-0467DF?style=for-the-badge&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/WhisperX-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/VITS%2FSoVITS-6B21A8?style=for-the-badge"/>
</p>

**data / infra**
<p align="center">
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS-4285F4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RunPod-6A00FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Locust-00B200?style=for-the-badge&logo=locust&logoColor=white"/>
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
</p>

<br/>

<h2>🎖️ achievements_unlocked</h2>

<p align="center">
<img src="https://img.shields.io/badge/📄_Papers-2_Published-6B21A8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/💡_Patents-2_Registered-6B21A8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/🏛️_Grants-7_National_Projects-6B21A8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/🌍_Dispatched-Notre_Dame_2021-6B21A8?style=for-the-badge"/>
</p>
<p align="center">
<img src="https://img.shields.io/badge/📱_Shipped-JP_%26_US_App_Stores-9333EA?style=for-the-badge"/>
<img src="https://img.shields.io/badge/🎓_Certified-Math_Teacher_Grade_2-9333EA?style=for-the-badge"/>
<img src="https://img.shields.io/badge/🤗_Fine--tuned-Qwen2.5--7B_(muse2)-9333EA?style=for-the-badge"/>
<img src="https://img.shields.io/badge/🧩_OSS-tachyon_%26_arkworks--rs-9333EA?style=for-the-badge"/>
</p>

<br/>

<h2>📡 live_status</h2>

<p align="center">
<img src="https://img.shields.io/github/followers/Leegwangwoon?label=followers&style=for-the-badge&color=A855F7&labelColor=0d0221"/>
<img src="https://img.shields.io/github/last-commit/Leegwangwoon/Leegwangwoon?label=last%20commit&style=for-the-badge&color=A855F7&labelColor=0d0221"/>
<img src="https://img.shields.io/badge/status-shipping-C084FC?style=for-the-badge&labelColor=0d0221"/>
</p>



<br/>

<div align="center">

```
$ echo "let's build something that proves itself"
```

<a href="https://www.linkedin.com/in/woony/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/Leegwangwoon"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://velog.io/@woony/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white"/></a>
<a href="mailto:leegwangwoon@naver.com"><img src="https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=naver&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Leegwangwoon&color=9333EA&style=for-the-badge&label=PROFILE+VIEWS" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6B21A8,50:2d0057,100:0d0221&height=150&section=footer&reversal=true" />
