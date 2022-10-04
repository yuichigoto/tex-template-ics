# 使い方

LinuxやmacOSでは日本語の文字コードがUTF-8であるため、`sample.utf8.tex`を利用してください。
なお、2022年10月5日現在、コンパイル時にエラーが発生します。`r`キーを押して以下のエラーは無視してください。
```
% platex sample.utf8.tex
This is e-pTeX, Version 3.141592653-p4.0.0-220214-2.6 (utf8.euc) (TeX Live 2022) (preloaded format=platex)
 restricted \write18 enabled.
entering extended mode
(./sample.utf8.tex
pLaTeX2e <2021-11-15> (based on LaTeX2e <2021-11-15> patch level 1)
L3 programming layer <2022-02-24>
(/usr/local/texlive/2022/texmf-dist/tex/latex/plautopatch/plautopatch.sty)
〜中略〜
(/usr/local/texlive/2022/texmf-dist/tex/latex/base/latexsym.sty)
(/usr/local/texlive/2022/texmf-dist/tex/latex/base/latexsym.sty)
(/usr/local/texlive/2022/texmf-dist/tex/latex/l3backend/l3backend-dvipdfmx.def
(|extractbb --version)) (./sample.utf8.aux)

! LaTeX Error: There's no line here to end.

See the LaTeX manual or LaTeX Companion for explanation.
Type  H <return>  for immediate help.
 ...                                              
                                                  
l.55 \maketitle
               
?  （rキーを押す）
〜中略〜
OK, entering \nonstopmode...
[1] [1] [2] (./sample.utf8.toc
(/usr/local/texlive/2022/texmf-dist/tex/latex/base/ulasy.fd) [3]) [4]
(./sample.utf8.lof) [5] (./sample.utf8.lot) [6]
第 1 章
[1]
第 2 章
[2] [3] [4]
第 3 章
[5]
第 4 章
[6] [7] [8] [9]
付 録 A  
[10]
付 録 B  
***** List of packages loaded by `plautopatch': *****
 plarray.
*****************************************************
[11] (./sample.utf8.aux) )
(see the transcript file for additional information)
Output written on sample.utf8.dvi (18 pages, 16440 bytes).
Transcript written on sample.utf8.log.

% dvipdfmx sample.utf8
% evince sample.utf8.pdf &
```
