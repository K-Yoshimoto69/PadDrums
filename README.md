# PAD/8 — Web Drum Machine

> Web Audio API と 100% Vanilla JS で動作する、軽量・レスポンシブな 8 パッド型ドラムマシン。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-4DD9E0?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue.style=flat-square)

---

## 🌟 概要 (Overview)

**PAD/8** は、外部音源ファイル（WAV/MP3など）を一切使わず、**Web Audio API によるオシレーター合成とノイズ生成**のみでリアルタイムに音を鳴らすWebドラムマシンアプリです。

単一の `index.html` ファイルで構成されており、軽量かつ依存関係ゼロで動作します。ネオン調のハードウェア風UI、LEDアニメーション、直感的なボトムシートUIによるサウンドのカスタマイズ機能を備えています。

---

## ✨ 主な機能 (Features)

* 🎨 **オールインワン構造**: 外部ライブラリ・サンプル音源不要。`index.html` 1ファイルのみで動作。
* 🔊 **Web Audio API シンセシス**: 10種類のパーカッションサウンド（Kick, Snare, Hi-Hat, Tom, Clap, Rim, Cowbell, Clave, Cymbal）を完全合成。
* 🎛️ **4つのドラムキットプリセット**: 
  * `ACOUSTIC` / `808` / `TECHNO` / `LO-FI`
  * キットごとにチューニングパラメータ（Flavor）が変化し、異なる音響表現が可能。
* 🛠️ **カスタムパッドアサイン**: 
  * パッド右下の「●」ボタンをタップするとボトムシートが開く。
  * 好きな音色を選んで即座にプレビュー＆各パッドへ割り当て可能。
* 📱 **モバイル・タッチ最適化**: 
  * iPhone / Android 等のモバイル端末に最適化したレスポンシブデザイン。
  * PWA / フルスクリーン表示対応（Safe Area対応）。
  * 音声自動再生制限（AudioContext Suspended）に対応。

---

## 🚀 使い方 (Getting Started)

### インストール・実行

特別なビルドプロセスや `npm install` は不要です。

```bash
# 1. リポジトリをクローン
git clone [https://github.com/your-username/pad8-drum-machine.git](https://github.com/your-username/pad8-drum-machine.git)

# 2. ディレクトリに移動
cd pad8-drum-machine

# 3. index.html をブラウザで開く (macOSの例)
open index.html
