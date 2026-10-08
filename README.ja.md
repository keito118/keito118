<h1 align="center">Hi, I'm keito118 🐈</h1>

<p align="center">
  <img src="https://http.cat/200" width="360" alt="HTTP 200 OK cat" />
</p>

<p align="center">
  IT企業でSIerとして働くシステムエンジニアです。GitHubでは勉強と趣味で、会話AIやXRのプロジェクトをつくっています。
</p>

<p align="center"><a href="./README.md">English</a> | 日本語</p>

---

```
   /\_/\
  ( o.o )  < にゃ〜 ようこそ！
   > ^ <
```

## 🐱 About me

- 💼 IT企業でSIerとして勤務。GitHubは勉強と個人開発の場として使っています
- 💬 日本語の言語モデル「**Lilas**」をPyTorchでゼロから個人開発。トークナイザ、Transformer、学習、評価まですべて自作
- 🥽 大学の研究で、ろう者と聴者の会話をアバターでつなぐMeta Quest 3向けシステム **AR Communicator** のチーム開発に参加しました
- 🌱 いま学んでいること: 対話モデル / LLMの学習と評価、データ分析

## 🐾 Projects

### 💬 Lilas: ゼロから作った日本語言語モデル(個人開発)
[keito118/lilas-llm-from-scratch](https://github.com/keito118/lilas-llm-from-scratch) · MIT License

事前学習済みの重みを使わず、PyTorchでゼロから作ったGPT型の小さな日本語会話モデル(パラメータ数4,000万)。

- **BPEトークナイザ**を自作(マージの差分更新で学習を**28倍高速化**)し、top-pサンプリングと繰り返しペナルティを備えた**デコーダ型Transformer**を実装
- **2段階学習**: 青空文庫と日本語Wikipediaで事前学習し、指示データと手書きのペルソナ会話でファインチューニング
- 学習済みの位置埋め込みを流用し、再学習なしで**コンテキスト長を256から1024に拡張**
- **ツール利用**(計算、祝日、天気、Wikipedia検索)の結果を参考情報としてモデルに渡し、回答はモデル自身が生成
- **改善を数値で追跡**: 固定した評価用会話セットで毎ラウンド評価し、失敗と原因分析も学習ログとして公開
- Tech: Python, PyTorch, NumPy, Hugging Face Datasets

### 🥽 AR Communicator for Deaf and Hearing(大学の研究・チーム開発)
[social-robotics-lab/ar-communicator-for-deaf-and-hearing](https://github.com/social-robotics-lab/ar-communicator-for-deaf-and-hearing)

会話相手にアバターを重ねて表示し、音声と手話をアバターが相互に変換して伝えるMeta Quest 3向けARシステム。

- **担当:** アバターの音声再生(`SpokenLanguageScript.cs` / `AudioController.cs`)、シナリオCSVの読み込みと辞書化(`ScenarioToDict.cs`)
- 手話モーションのパラメータ調整、アバター3体を配置したシーンの構築、Quest 3実機での動作確認
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

<p align="center">🐾 見に来てくれてありがとうございます！よい一日を 🐈</p>
