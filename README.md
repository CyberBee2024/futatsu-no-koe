# デジタル・ペルソナ — 二つの声 / Digital Persona: Two Voices

藤嶋咲子《デジタル・ペルソナ — 二つの声》(art-bit 6, 2026) の対話ログ可視化サイト。

## 公開方法（GitHub Pages）

1. GitHub で新しいリポジトリを作成（例: `futatsu-no-koe`、Public）。
2. この `index.html` をアップロード（リポジトリ画面の「Add file → Upload files」にドラッグ）。
3. Settings → Pages → Build and deployment → Source: **Deploy from a branch**、
   Branch: **main** / **/(root)** を選んで Save。
4. 1〜2分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

## データについて

対話ログ・画像はすべて `index.html` 一つに埋め込まれています（外部ファイル不要・単一ファイルで完結）。
ログを差し替えたいときは、`index.html` 内の `const DATA = { ... }` を編集してください。
