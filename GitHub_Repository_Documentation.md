<!-- STREAMING_CHUNK:Writing title and header badges... -->
# 🎵 Vinyl Player Pro

iOS / Android のバックグラウンド再生・ロック画面操作に対応した、レトロ＆スタイリッシュなWebレコーダー・オーディオプレイヤーです。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)

---

<!-- STREAMING_CHUNK:Writing features section... -->
## ✨ 特徴・機能

- 📱 **バックグラウンド＆ロック画面再生完全対応**:
  - Web Media Session API を採用し、画面オフ時や他アプリ使用時でも高音質で連続再生可能。
  - ロック画面やコントロールセンターから再生・一時停止・曲送り・シーク操作が可能。
- 針（トーンアーム）が動くリアルなアナログレコード演出。
- 🔊 **レコード特有のクラックルノイズ（プチプチ音）合成**:
  - Web Audio API を活用したリアルタイム環境音エフェクト（ON/OFF切替可能）。
- 🎛 **回転数（RPM）変更 & ピッチコントロール**:
  - 33 / 45 / 78 RPM に対応し、再生速度をリアルタイム変更。
- 📊 **円状オーディオビジュアライザー**:
  - レコード外周で音に反応して波形が動くビジュアルエフェクト。
- 📜 **プレイリスト＆リピート・シャッフル管理**:
  - 複数ファイルの一括選択、ドラッグ＆ドロップ再生、1曲/全曲リピート設定。
- 🚀 **サーバー不要（完全ローカル処理）**:
  - 選択した音声/動画ファイルはサーバーに送信されず、端末内で安全・高速に処理されます。

---

<!-- STREAMING_CHUNK:Writing usage guide... -->
## 🚀 使い方

### 1. Webブラウザで開く
GitHub Pages の公開URLにアクセスします。

### 2. 音楽ファイルを選択
「**曲を選択**」ボタンをクリック（またはドラッグ＆ドロップ）し、端末内の音楽・動画ファイルを選択します。
> **対応フォーマット**: `.mp3`, `.m4a`, `.mp4`, `.wav`, `.aac`, `.flac` など

### 3. レコードプレイヤーを楽しむ
- **再生 / 一時停止**: 中央のプレイボタンを押すか、ロック画面・イヤホンリモコンから操作できます。
- **プチプチ音（CRACKLE）**: 右上の「CRACKLE」ボタンでノイズ音をON/OFF設定。
- **プレイリスト確認**: 右上のリストアイコンでプレイリスト一覧を表示。

---

<!-- STREAMING_CHUNK:Writing deployment instructions... -->
## 🛠 GitHub Pages での自前公開手順

1. 本リポジトリを Fork またはダウンロードします。
2. 自身の GitHub に新規リポジトリを作成し、`index.html` と `README.md` をアップロードします。
3. リポジトリの **Settings** > **Pages** を開きます。
4. **Source** を `Deploy from a branch` にし、`main` ブランチの `/ (root)` を選択して **Save** を押します。
5. 数分後に発行されるURLから利用可能です。

---

<!-- STREAMING_CHUNK:Writing technology stack and license... -->
## 🧰 技術スタック

- **HTML5 / CSS3 / JavaScript (ES6+)**
- **Tailwind CSS** (デザイン・UI)
- **Font Awesome 6** (アイコン)
- **Web Media Session API** (バックグラウンド再生・ロック画面連動)
- **Web Audio API** (アナログノイズ合成)

---

## 📄 ライセンス

[MIT License](LICENSE)