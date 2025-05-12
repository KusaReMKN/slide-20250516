# オレオレ IP 電話網を大きくしたら Tailscale の~~不具合~~ワナを踏み抜いて発狂した話

2025-05-16 のエンジニア作業飲み集会で発表した際のスライド資料のソースです。

## コンパイル方法

[matze/mtheme](https://github.com/matze/mtheme) で公開されている Metropolis を使っているため、予めインストールしておく必要があります。

```console
$ latexmk -lualatex
```

## 最適化

出力される PDF がかなり大きいため、必要であれば最適化します。

```console
$ ./optimize.sh
```
