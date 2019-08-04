<!--
Filename:       README.md
Author:         Shiro Takeda
e-mail          <shiro.takeda@gmail.com>
First-written:  <2006/12/04>
Time-stamp:     <2019-01-22 14:07:33 st>
-->

jecon.bst
==============================

jecon.bst (経済学用のBibTeX style file) の私家修正版です。
本家の ver. 5.6 に準拠しています.

本家: <http://shirotakeda.org/ja/tex-ja/jecon-ja.html>

本家との違い:
* DOI の表記から, `http:/dx.doi.org/` を省略しました.
  + リンクをフルで表記するのは冗長なためです. また, `dx.doi.org` を `doi.org` に変更しています.
=======
"jecon.bst"は（主に）経済学用の BibTeX スタイルファイルです。以下のような特徴があります。

* 「著者（年）」形式（author-year format) で引用できます。
*  経済学でよく利用されるような参考文献（reference）の形式を実現できます（ただし、
  特定の雑誌向けというわけではないです）。
* 英語の文献だけでなく、日本語の文献も適切に処理できます。
* 他の BibTeX 用のスタイルファイルよりも表示形式のカスタマイズが簡単にできます。

## ファイル

| ファイル                                    | 説明                                                         |
|:--------------------------------------------|:-------------------------------------------------------------|
| `jecon.bst`                                 | これが bst ファイルです。                                    |
| `jecon-example.tex`                         | 使い方等の説明をしたファイルです。                           |
| [`jecon-example.pdf`](jecon-example.pdf) | `jecon-example.tex` をPDFにしたものです。                    |
| `jecon-example.bib`                         | 文献のファイルです。                                         |
| `jecon-example-old.bib`                     | 文献のファイルです。                                         |
| `unicode`                                   | ユニコード文字の利用について説明したファイルがあるフォルダ。 |
| `customization`                             | カスタマイズの例を置いてあるフォルダ。                       |
| [`CHANGES.md`](CHANGES.md)                | 変更点を説明したファイルです。                               |
| `README.md`                                 | このファイルです。                                           |

<!--
--------------------
Local Variables:
mode: markdown
fill-column: 80
coding: utf-8-dos
End:
-->

