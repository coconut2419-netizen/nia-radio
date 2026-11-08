<h1 align="center">ニアの朝ラジオ</h1>

<p align="center"><b>毎朝、天気と相場、AI・テックニュースを、<br>秘書AIのニアがまとめてお届けします。</b></p>

<p align="center">秘書AIニアの、朝のまとめ聞き。毎朝 7:00 更新（予定）。</p>

<p align="center">
  <a href="https://coconut2419-netizen.github.io/nia-radio/"><img src="https://img.shields.io/badge/%E2%96%B6%20ON%20AIR-%E3%83%8B%E3%82%A2%E3%81%AE%E6%9C%9D%E3%83%A9%E3%82%B8%E3%82%AA-b18cff?style=for-the-badge&labelColor=161a26" alt="ニアの朝ラジオを聞く"></a>
</p>

- **放送は HTML の番組**です。台本（JSON）と音声（mp3）を置いて公開するだけで、字幕・見出し・キャラクター・出典リンクが再生に合わせて動きます
- **チャンネル切り替え**：回の一覧は「総合／相場／テック」のタブで絞り込めます（`station.json` の `channels` と、各回の `ch` で指定）
- **ニュースの画像**は、記事のサイトが共有用に公開している画像（OGP）の URL を表示するだけで、保存はしません
- 公開は直近 30 日分の音声だけ。台本は残るので、過去の回も文字で読めます

## 仕組み

この局は [myradio](https://github.com/monoradio102/myradio)（monoradio102）のテンプレートで作られています。局の情報は `station.json`、台本は `episodes/`、回の一覧は `episodes.json`、キャラクターは `character/` にあります。形式の詳細は [docs/formats.md](docs/formats.md)、運用の決まりは [AGENTS.md](AGENTS.md) を見てください。

未完成・仮置きの箇所は [TODO.md](TODO.md) にまとめています。

## ライセンス

- プログラム（`index.html`、`tools/`）：MIT License（myradio by monoradio102）。詳細は [LICENSE](LICENSE)
- 台本（`episodes/`、`episodes.json`）：この局のもの
- キャラクター（`character/`）：ニア・リリスの13状態透過PNGパック（AI生成）。旧パックも復元用に同梱（詳細は `station.json` と `character/character.json` の note を参照）
- 天気：Open-Meteo（CC BY 4.0）

## クレジット

- 声：Irodori-TTS（予定）
- 仕組み：myradio by monoradio102（MIT）
