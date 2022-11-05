## How to use

At first, copy sample.utf8.tex

```
% cp sample.tex Goto_M.tex
```

The file includes Japanese characters as Japanese title and lab name.
So, you should use `platex`.
```
% platex Goto_M
```

After that, generate PDF file.
```
% dvipdfmx Goto_M
```

You can get `Goto_M.pdf` according to this example.