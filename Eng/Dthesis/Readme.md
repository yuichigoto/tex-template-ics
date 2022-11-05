## How to use

At first, copy sample.tex

```
% cp sample.tex Goto_D.tex
```

Our graduate school demands Japanese title. If your manuscript includes Japanese characters, you should use `platex`. if not, `latex`.
```
% latex Goto_D
```

After that, generate PDF file.
```
% dvipdfmx Goto_D
```

You can get `Goto_D.pdf` according to this example.