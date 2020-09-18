## lualatexのコンパイルについて

### lualatexのコンパイル

lualatexのコンパイルは、

> lualatex sample.tex

をコマンドライン上で実行。

### bibtexの使用

bibtexを使用する場合には、

> lualatex sample.tex

> pbibtex deep_hedge

> lualatex sample.tex（複数回）

をコマンドラインで実行することでコンパイルが可能。
