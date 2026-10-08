<h1 align="center">Hi, I'm keito118 🐈</h1>

<p align="center">
  <img src="https://http.cat/200" width="360" alt="HTTP 200 OK cat" />
</p>

<p align="center">
  Systems engineer at a Japanese IT company (SIer). On GitHub I build conversational AI and XR projects for learning and fun.
</p>

<p align="center">English | <a href="./README.ja.md">日本語</a></p>

---

```
   /\_/\
  ( o.o )  < nya~ welcome!
   > ^ <
```

## 🐱 About me

- 💼 Working as a systems engineer at a Japanese SIer; GitHub is where I study and build personal projects
- 💬 Building **Lilas**, a Japanese language model, from scratch in PyTorch: tokenizer, Transformer, training and evaluation
- 🥽 In university research, contributed to **AR Communicator**, a team project on Meta Quest 3 that uses avatars to bridge conversations between Deaf and hearing people
- 🌱 Currently learning: training and evaluating dialogue models / LLMs, data analysis

## 🐾 Projects

### 💬 Lilas: a Japanese language model built from scratch (personal project)
[keito118/lilas-llm-from-scratch](https://github.com/keito118/lilas-llm-from-scratch) · MIT License

A small GPT-style Japanese conversational model (40M parameters) built from scratch in PyTorch, with no pretrained weights.

- Wrote my own **BPE tokenizer** (an incremental merge update made training **28× faster**) and a **decoder-only Transformer** with top-p sampling and a repetition penalty
- **Two-stage training**: pretraining on Aozora Bunko and Japanese Wikipedia, then fine-tuning on instruction data and hand-written persona conversations
- **Context extension** from 256 to 1024 tokens by reusing learned position embeddings instead of retraining
- **Tool use** (calculator, holidays, weather, Wikipedia lookup) with results passed to the model as reference text
- **Measured progress**: a frozen held-out conversation set evaluated after every round, with failures and diagnoses kept in a public training log
- Tech: Python, PyTorch, NumPy, Hugging Face Datasets

### 🥽 AR Communicator for Deaf and Hearing (university research, team project)
[social-robotics-lab/ar-communicator-for-deaf-and-hearing](https://github.com/social-robotics-lab/ar-communicator-for-deaf-and-hearing)

An AR system for Meta Quest 3 that overlays an avatar on your conversation partner and translates between spoken language and sign language through the avatar.

- **My role:** avatar voice playback (`SpokenLanguageScript.cs`, `AudioController.cs`) and loading scenario CSVs into dictionaries (`ScenarioToDict.cs`)
- Tuned sign-language motion parameters, built a scene with three avatars, and tested on a real Quest 3 headset
- Tech: Unity (C#), UniVRM, Firebase Realtime Database, Meta Quest 3

## 🧶 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,unity,cs,git,github,firebase&perline=7" />
</p>

## 😺 GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=keito118&show_icons=true&hide_border=true" />
</p>

---

<p align="center">🐾 Thanks for dropping by! Have a purr-fect day 🐈</p>
