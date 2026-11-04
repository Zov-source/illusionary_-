# ILLUSIONARY — Character 041–050 Add-on

既存サイトへキャラクター041〜050を追加する差分ファイルです。既存001〜040のHTMLやCSSは含めていません。

## 収録内容
- `character-041.html` 〜 `character-050.html`：詳細ページ10枚
- `characters-041-050.json`：一覧データへの追加分10件のみ
- `README.md`：導入手順

## GitHubへの追加手順
1. ZIPを展開します。
2. 10枚の `character-041.html` 〜 `character-050.html` を既存リポジトリのルートへ追加します。
3. `characters-041-050.json` を開き、配列内の10件を既存の `characters.json` の配列末尾へ追加します。**既存の `characters.json` 全体は置き換えないでください。** 既存の最後の要素と追加データの最初の要素の間にカンマを入れてください。
4. 画像は同梱していません。画像を使う場合は `images/character-041.jpg` 〜 `images/character-050.jpg` を追加してください。
5. コミットしてGitHub Pagesへ反映します。

詳細ページは既存の `style.css` を参照します。CSSやトップページの `index.html` は変更不要です。
