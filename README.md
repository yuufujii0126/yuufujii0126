# こんにちは、藤井 優羽です 👋

武蔵野大学 データサイエンス学部 データサイエンス学科 / 2028年3月卒業予定  
**データサイエンティスト・データアナリスト** を目指して就職活動中です。

> データから「人の行動や気持ち」を読み解き、意思決定に役立つ形で届けることに関心があります。

---

## 🧑‍💻 About Me

- 🎓 **研究**：VR教室上での学生の行動データ分析による、授業の納得度推定システム
- 💼 **インターン**：株式会社Finatext にて、Snowflake × Python / SQL を用いたPOSデータ分析
- 🎯 **興味のある分野**：行動データ分析、マルチモーダルデータ、教育 × データサイエンス

---

## 🛠 Skills

| 分野 | 技術 |
| --- | --- |
| 言語 | Python, Java, SQL |
| データ分析 | NumPy, librosa（音声特徴量） |
| 研究で扱った技術 | MediaPipe（表情・頭部姿勢）, LLM API, Three.js / WebXR |
| データ基盤 | Snowflake |
| ツール | Git / GitHub |

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)

---

## 🔬 Research

### [VRClassroom](https://github.com/yuufujii0126/VRClassroom) — VR教室における学習者の納得度推定

**背景：** 授業で学生がどれだけ「納得」しているかは、これまで授業後のアンケートに頼るしかなく、リアルタイムで客観的に測る手段がありませんでした。

**取り組み：** WebXRで構築したVR教室で学習者の行動データを収集し、複数のモーダルから納得度を推定する基盤を開発しています。

- **頭部運動**：うなずき・首振りを頭部姿勢の時系列から検出
- **表情**：MediaPipeの表情特徴を Action Unit に対応づけ、笑顔・困惑などを指標化
- **音声・言語**：発話の音響特徴の抽出と、LLMによる同意／聞き返し等の発話ラベリング
- **主観指標との照合**：理解・同意・受容・コミットメントの4次元尺度と客観指標を対応づけ、相関分析・回帰モデルで予測可能性を検証

**技術：** Python / MediaPipe / Three.js・WebXR / LLM API / SQLite  
**発表：** DICOMO2026（共著）

---

## 💼 Experience

### 株式会社Finatext（インターン）— POSデータ分析

**内容：** Snowflake上のPOSデータを Python・SQL で分析し、「何が、いつ、なぜ売れるのか」を探りました。

**仮説検証で苦労したこと：**  
当初は「まとめ買いは土日、惣菜など日常的に消費する即食系の食品は平日に買われる」という仮説を立てましたが、データでは明確に支持されず、仮説検証の難しさを実感しました。

**学んだこと：**
- 数字だけでは見えない **購買の背景**（生活者の事情や店舗の状況など）に目を向けることの重要さ
- 仮説は、自分の知見・経験に基づく **主観的仮説** と、データに基づく **客観的仮説** の両方を行き来しながら立てることが大切だということ

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yuufujii0126&show_icons=true&hide_border=true)
