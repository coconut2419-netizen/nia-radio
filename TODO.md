# TODO（仮置き・未完成の箇所）

- **声は確定済み**：ニアの声は Irodori-TTS で作成し、参照潜在として固定済み（Muse側で管理）。試験放送（2026-11-06）の音声は生成済みで `audio/2026-11-06-ja.mp3`（46.96秒）があり、台本には `lines_timed`／`segments`／実測 `seconds` を記入済み。
- **url / repo はプレースホルダ**：`station.json` の `url`（https://coconut2419-netizen.github.io/nia-radio/）と `repo`（https://github.com/coconut2419-netizen/nia-radio）は、リポジトリ作成後に実在のものへ合わせる。README 冒頭の ON AIR バッジのリンク先も同じプレースホルダ。公開手順はCodex向け手順書（Muse側 `~/workspace/nia-radio/SETUP_FOR_CODEX.md`）参照。
- **コメント欄（giscus）は未設定**：テンプレートの `station.json` に入っていたお手本局の `comments` は削除済み。自局のリポジトリで Discussions を有効化し、giscus の ID を取得してから `station.json` に `comments` を書き、`giscus.json` の origins を公開先に合わせる（手順は `AGENTS.md` の「コメント欄」）。後回し可。
- **ロゴは仮**：`logo.svg` は簡易な自作マークに差し替え済み（お手本のロゴは残していない）。`station.json` の `logo` は null で、プレーヤーには局名の頭文字が出ます。正式ロゴができたら差し替える。
- **毎朝の自動生成は未構築**：台本生成→音声生成→push の自動化は今後の作業（Muse側で台本と音声を作り、公開側へ渡す形を想定）。
