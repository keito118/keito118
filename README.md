<p align="center">
  <img src="./assets/icon.jpg" width="200" alt="keito118 icon" />
</p>

<h1 align="center">Hi, I'm Kate 👋</h1>

<p align="center">
  IT consultant at a Japanese IT company. On GitHub I build conversational AI and XR projects for learning and fun.<br />
  Knowing both development and business, I aim to be a bridge between the two.<br />
  On this GitHub, I keep building up my development skills.
</p>

<p align="center">English | <a href="./README.ja.md">日本語</a></p>

---

## 🎧 Put your song on my playlist

<p align="center">
  <b>I run a Spotify playlist where anyone on GitHub can be the DJ.</b><br />
  Paste a song link into an issue, a bot turns it into a pull request, and once it's merged the song is live on Spotify.
</p>

<p align="center">
  <a href="https://github.com/keito118/open-source-mixtape/issues/new?template=add-song.yml"><img src="https://img.shields.io/badge/Add%20a%20song-open%20an%20issue-black?style=for-the-badge&logo=github" alt="Add a song" /></a>
  <a href="https://open.spotify.com/playlist/6RrEtS1qX6csamOV6ET74Q"><img src="https://img.shields.io/badge/Listen%20on-Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white" alt="Listen on Spotify" /></a>
</p>

<p align="center">Every song has a commit, an author, and a reason. 🎶</p>

---

## 🙋 About me

- 💼 Working as an IT consultant at a Japanese IT company; GitHub is where I study and build personal projects
- 💬 Building **Lilas**, a Japanese language model, from scratch in PyTorch: tokenizer, Transformer, training and evaluation
- 🎧 Built **Playlist as Code**, which runs Spotify playlists through GitHub pull requests, and **Open Source Mixtape**, a playlist anyone can add a song to
- 🥽 In university research, contributed to **AR Communicator**, a team project on Meta Quest 3 that uses avatars to bridge conversations between Deaf and hearing people
- 🌱 Currently learning: training and evaluating dialogue models / LLMs, data analysis

## 🚀 Projects

### 🎧 Playlist as Code: Spotify playlists run like a code repository (personal project)
[keito118/spotify-playlist-as-code](https://github.com/keito118/spotify-playlist-as-code) · v1.0.0 · GitHub template · MIT License

A template that turns any Spotify playlist into a GitHub repository. Each playlist is a text file with one song per line: a pull request proposes songs, a review is a listen, and merging updates the real playlist.

- **Merge = publish**: GitHub Actions validates every pull request (bad links, duplicates, track lookup on Spotify) and syncs the playlist on merge, in file order
- **No Git needed to join in**: paste a song link into an issue form, and a bot looks it up, edits the file, and opens the pull request
- **History for free**: `git log` shows who added each song, when, and why
- **Zero dependencies**: Python standard library only, no servers to run
- 🎶 Live demo: [**Open Source Mixtape**](https://github.com/keito118/open-source-mixtape), a playlist anyone in the world can add to ([listen on Spotify](https://open.spotify.com/playlist/6RrEtS1qX6csamOV6ET74Q))
- Tech: Python, GitHub Actions, Spotify Web API

### 💬 Lilas: a Japanese language model built from scratch (personal project)
[keito118/lilas-llm-from-scratch](https://github.com/keito118/lilas-llm-from-scratch) · MIT License

A small GPT-style Japanese conversational model (40M parameters) built from scratch in PyTorch, with no pretrained weights.

- Wrote my own **BPE tokenizer** (an incremental merge update made training **28× faster**) and a **decoder-only Transformer** with top-p sampling and a repetition penalty
- **Two-stage training**: pretraining on Aozora Bunko and Japanese Wikipedia, then fine-tuning on instruction data and hand-written persona conversations
- **Context extension** from 256 to 1024 tokens by reusing learned position embeddings instead of retraining
- **Tool use** (calculator, holidays, weather, Wikipedia lookup) with results passed to the model as reference text
- **Measured progress**: a frozen held-out conversation set evaluated after every round, with failures and diagnoses kept in a public training log
- 📝 Write-up on dev.to: [Why my from-scratch Japanese LLM says "That sounds tough" to good news](https://dev.to/keito118/why-my-from-scratch-japanese-llm-says-that-sounds-tough-to-good-news-3k15)
- Tech: Python, PyTorch, NumPy, Hugging Face Datasets

### 🥽 AR Communicator for Deaf and Hearing (university research, team project)
[social-robotics-lab/ar-communicator-for-deaf-and-hearing](https://github.com/social-robotics-lab/ar-communicator-for-deaf-and-hearing)

An AR system for Meta Quest 3 that overlays an avatar on your conversation partner and translates between spoken language and sign language through the avatar.

- **My role:** avatar voice playback (`SpokenLanguageScript.cs`, `AudioController.cs`) and loading scenario CSVs into dictionaries (`ScenarioToDict.cs`)
- Tuned sign-language motion parameters, built a scene with three avatars, and tested on a real Quest 3 headset
- Tech: Unity (C#), UniVRM, Firebase Realtime Database, Meta Quest 3

## 🛠 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,unity,cs,git,github,githubactions,firebase&perline=8" />
</p>

## 📊 GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=keito118&show_icons=true&hide_border=true" />
</p>
