# 使い方
## pLaTeXを使う場合
LinuxやmacOSでは日本語の文字コードがUTF-8であるため、`sample.utf8.tex`を利用してください。
2025年6月1日現在、Ubuntu 24.04 LTSで動作確認をしています。
```
%  platex --version
e-upTeX 3.141592653-p4.1.0-u1.29-230214-2.6 (utf8.euc) (TeX Live 2023/Debian)
kpathsea version 6.3.5
ptexenc version 1.4.3
Copyright 2023 D.E. Knuth.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the e-upTeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the e-upTeX source.
Primary author of e-upTeX: Japanese TeX Development Community.

% platex sample.utf8.tex
% dvipdfmx sample.utf8
% evince sample.utf8.pdf &
```

## LuaLaTeXを使う場合
LuaLaTeXを使う場合は、`sample.lualatex.tex`を利用してください。
2025年6月1日現在、Ubuntu 24.04 LTSで動作確認をしています。
```
%  lualatex --version
This is LuaHBTeX, Version 1.17.0 (TeX Live 2023/Debian)
Development id: 7581

Execute  'luahbtex --credits'  for credits and version details.

There is NO warranty. Redistribution of this software is covered by
the terms of the GNU General Public License, version 2 or (at your option)
any later version. For more information about these matters, see the file
named COPYING and the LuaTeX source.

LuaTeX is Copyright 2022 Taco Hoekwater and the LuaTeX Team.

% lualatex sample.lualatex.tex
% evince sample.lualatex.pdf &
```
