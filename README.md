# Textbox

文章まわりの細かい作業を、ブラウザだけでまとめて行える Web ツール集です。インストール不要、入力した文章は端末の外に送信されません。

**公開ページ:** https://daigorou-addon.github.io/textbox/

## 機能

| タブ | できること |
|---|---|
| 文字数カウント | 文字数、空白を除く文字数、バイト数（UTF-8）、行数、原稿用紙（400字詰め）の枚数。X（140字）・YouTube のタイトル（100字）・概要欄（5000字）の上限メーター付き |
| 文字変換 | 英数記号の全角⇄半角、半角カナ⇄全角カナ、大文字／小文字、ひらがな⇄カタカナ、改行の削除、空白の削除 |
| 文字装飾 | 太字・斜体・太字斜体・筆記体・二重線・等幅・丸文字・黒丸・四角・取り消し線・下線の 11 種類。押すとコピー（英数字のみ変換。取り消し線・下線は全文字） |
| 縦書き画像 | 文章を縦書きの画像にして PNG で保存。文字サイズ・書体（明朝／ゴシック）・文字色・背景色を指定可能 |
| ふりがな | 漢字にふりがなを付けて表示。「漢字（かんじ）」の括弧付き形式でコピーも可能 |

## 特長

- 日本語 / English / 한국어 / 简体中文 / 繁體中文 / Español の 6 言語に対応
- ダーク表示の切り替えに対応
- スマホ（縦・横画面）に対応

## プライバシー

すべての処理はこの端末内で行われます。入力した文章はどこにも送信されません。

ふりがなタブは、初回の利用時に辞書（約 18 MB）を読み込みます。公開ページに同梱の辞書を読み込めなかった場合に限り、辞書ファイルのみを CDN（jsDelivr）から取得します。入力した文章が送信されることはありません。

## 使用ライブラリ

- [kuromoji.js](https://github.com/takuyaa/kuromoji.js)（Apache License 2.0）— ふりがなタブの形態素解析。ライセンス表記は `licenses` フォルダに同梱しています。

## 作者・サポート

制作: daigorou-tools（[daigorou-addon](https://github.com/daigorou-addon)）

開発を応援していただける方は [Buy Me a Coffee](https://buymeacoffee.com/daigorou) からどうぞ。

Copyright (C) 2026 daigorou-tools. All rights reserved.

---

# Textbox (English)

A set of small text tools that run entirely in your browser. No installation, and your text is never sent anywhere.

**Live page:** https://daigorou-addon.github.io/textbox/

## Features

- **Counter** — characters, characters without spaces, UTF-8 bytes, lines, and manuscript pages (400 characters each), with limit meters for X, YouTube titles and YouTube descriptions
- **Convert** — full-width ⇄ half-width alphanumerics and symbols, half-width ⇄ full-width kana, upper / lower case, hiragana ⇄ katakana, remove line breaks, remove spaces
- **Fancy text** — 11 Unicode styles (bold, italic, script, double-struck, monospace, circled, squared, strikethrough, underline and more), click to copy
- **Vertical text image** — render Japanese text vertically and save it as a PNG
- **Furigana** — add readings above kanji, or copy them in parentheses

Available in Japanese, English, Korean, Simplified Chinese, Traditional Chinese and Spanish, with dark mode and mobile support.

## Privacy

All processing happens on your device. The furigana tab downloads a dictionary (about 18 MB) on first use; only if the bundled dictionary cannot be loaded does it fetch the dictionary files from jsDelivr. Your text is never sent.

## Third-party software

- [kuromoji.js](https://github.com/takuyaa/kuromoji.js) (Apache License 2.0) — morphological analysis for furigana. License notices are included in the `licenses` folder.

Copyright (C) 2026 daigorou-tools. All rights reserved.
