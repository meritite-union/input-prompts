<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github_assets/cover_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="github_assets/cover_light.png">
  <img alt="The Meritite Union's Input Prompts" src="github_assets/cover.png">
</picture>

## すべてのゲーム開発のニーズのために1000以外個ベクターでラスターなプロンプト。
PlayStationとXboxとパソコンのはできあがります！
Nintendo Switchのプロンプトは開発中です。Wii・Wii UやSteam Deckや汎用やもっとこうご期待！

このアッセトパックが@hergergyのMeritite Unionに作られました。

Input PromptsはCC0 1.0 Universalで許可を与えさせられます。MODIFY SHARE DISTRIBUTE 権限が付与されています。作者表示は必須じゃないですが、歓迎します。

このプロジェクトのインスピレーションとなったのは、[KennyのInput Prompts](https://www.kenney.nl/assets/input-prompts)でした。[Xeluの](https://thoseawesomeguys.com/prompts/)も。プロジェクトをチェックしてください！

# ガイド
## 疑似インストール
全部が`.zip`ファイルに一個含まれます。必要に応じて、[最新バージョン](https://github.com/meritite-union/input-prompts/releases/latest)をダウンロードしてください。
## ストラクチャー
ファイルストラクチャーは `フォーマット / プラットフォーム / テーマ / カテゴリー / サブカテゴリ / シェード / バリアント.フォーマット`で:
- `フォーマット`: `256-png` for 256x256px png images (2x upscale from Figma) or `svg` for vector graphics (at standard 128x128 1x scale).
- `プラットフォーム`: `xbox`、`ps`（プレイステーション）、`pc`（パソコン）になれます。
- `テーマ`: `light`（ライト）、 `dark`（ダーク）になれます。
- `カテゴリー`: プラットフォームに違います。
- `サブカテゴリ`も。
- `シェード`: 単一のコントロールプロンプトには、`_` （ノーマル）と`fill`（フィル）があります。Dパッドなどのマルチコントロールプロンプトにはありません。
- `バリアント`: 特定のプロンプトに基づいて名前が付けられます。

したがって、影響があります。
- ファイル名自体は必ずしも一意である必要はありません。意味をもらうために、親フォルダーには必要な情報が含まれています。
- つまり、画像自体が重複している可能性があります. このパックは、プラットフォームのすべてのアセットがそれぞれのプラットフォーム フォルダー内に自己完結するように設計されています。例えば、PlayStation 専用のゲームを開発している場合は、Xbox の左スティック プロンプトが同じであっても、「ps」フォルダで左スティック プロンプトを見つけることができます。
## ファイルフォーマット
これは`.svg`形式に固有です。
すべてのプロンプトは 128x128ピクセルのボックスにあります。画厚さは一般に6ピクセルです。Standard colors used include ![#191923 HEX color representation](github_assets/191923.svg) `#191923`, ![#2E2836 HEX color representation](github_assets/2e2836.svg) `#2E2836`, ![#C8CED0 HEX color representation](github_assets/c8ced0.svg) `#C8CED0`, and ![#FBFEF9 HEX color representation](github_assets/fbfef9.svg) `#FBFEF9`です。この色はMeritite Unionのいろですけど、あなたのではないかもしれません。[Figma file](https://www.figma.com/community/file/1354930683181049242/input-prompts)を見ってください。

To try to help with import to whatever system you're using, I've formatted the file names to try to avoid your tools from throwing a fit. File and folder names consist of only lowercase a-z, underscore, and digits 0-9, although no file name begins with a digit. I'm not particularly experienced in these things, and I've only used a handful of tools. If there's a better format, please [let me know](https://github.com/meritite-union/input-prompts/issues/new)! Similarly, please leave an issue for any kind of feedback.
\
\
\
<img src="https://github.com/meritite-union/brand/blob/c0399ebfb77d66757c189edf77639b8a349f1d62/250x250.svg" width="35" height="35" alt="Meritite Union plain purple squid mascot" style="float:right;">
