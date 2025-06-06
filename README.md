埼玉大学工学部情報システム工学科LaTeX用学位論文テンプレート（非公式）
==========

## 本テンプレートについて

以下のLaTeX用スタイルファイルと雛形ファイルです。
- 埼玉大学工学部情報工学科の卒業論文
- 埼玉大学大学院理工学研究科 情報システム工学コース・情報工学プログラムの修士論文
- 同コース・プログラムの修論審査会、M2中間発表会、M1発表会の予稿
- 埼玉大学大学院理工学研究科の博士論文

卒業論文および修士論文のスタイルファイルは、情報工学科・情報工学プログラム・情報工学プログラムのWebサイトで配布しているものをベースにしています。博士論文のスタイルファイルは研究室内で利用しているものです。

## 注意点

このスタイルファイルは非公式なものです。このスタイルファイルを用いることで得た不利益について補償しかねます。ご注意ください。

卒業論文および修士論文のスタイルファイルは、情報工学科のWebサイトで配布しているものが最新版です。必ず見比べてください。

章の構成や参考文献の書式は私の習慣に依っています。どうするべきかは、各指導教員の指示にしたがってください。

## 本ファイルの構成

以下のディレクトリ構成になっています。
    
    .
    ├── Eng （英語表記用）
    │   ├── Dthesis （博士論文）
    │   ├── Mabstract （修論審査会／発表会の予稿用）
    │   └── Mthesis （卒業論文・修士論文）
    └── Jpn （日本語表記用）
        ├── BMthesis （卒業論文・修士論文）
        └── Mabstract（修論審査会／発表会の予稿用）
    
それぞれのディレクトリの構成は以下のようになっています。
- *.sty：スタイルファイル
- sample.tex：雛形ファイル。これをコピーして論文を作成する
- sample.pdf：雛形ファイルをコンパイルしたもの

ファイル名に「utf8」が含まれているファイルの文字コードはUTF-8であり、pLaTeX用です。
ファイル名に「lualatex」が含まれているファイルの文字コードはUTF-8であり、LuaLaTeX用です。
その他のファイルの文字コードはJISコード（ISO-2022-JP）であり、pLaTeX用です。

動作確認はTeX Live 2023/Debin で行っています。日本語表記用はpLaTeX(日本語用LaTeX）かLuaLaTeXの使用を前提としています。スタイルファイルの設定が古いためupLaTeXでは動きません。英語表記用についても、DthesisとMthesisは日本語を含むためpLaTeXかLuaLaTeXを使ってください。Mabstractについては日本語が含まれていないのでLaTeXを使うことをお勧めします。


## ファイル取得方法

### Webページからのダウンロード

https://github.com/yuichigoto/tex-template-ics を開き、右側にある「Download ZIP」というボタンをクリックしてダウンロードしてください。

## 関連情報

正式版の卒業論文および修士論文のスタイルファイルは、学科内ネットワークからダウンロードできます。どこにあるかは指導教員に尋ねてください。

博士論文および修士論文提出に関連する情報および各種書類の様式については、入学時に配布された履修案内を確認するとともに、[埼玉大学大学院理工学研究科のページ](https://www.saitama-u.ac.jp/rikogaku/)の「在学生のみなさんへ」→「事務室からのお知らせ」を確認してください。

Linux環境の構築については[WSL2を用いたUbuntu環境の構築](https://www.aise.ics.saitama-u.ac.jp/~gotoh/Ubuntu2404OnWSL2In2025.html)にまとめてあります。

指導教員や先輩に論文指導をしてもらう前に[卒業論文・修士論文および英語論文のための自己チェックリスト](https://github.com/yuichigoto/checklists)を使って、基本的な点について直しておきましょう。


### 問い合わせ先

このスタイルファイルは、[後藤 祐一](http://www.aise.ics.saitama-u.ac.jp/~gotoh/FrontPage.html)が公開しています。
