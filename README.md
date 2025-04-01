# フリーペーパー：ゆめみ25周年新歓祭

このペーパーは、[mitsuharu/iosdc-pamphlet-template](https://github.com/mitsuharu/iosdc-pamphlet-template) を元に作成しました。

## 執筆手順（ローカル）

### 電子版のPDF作成

PDFを作成する。`output/output.pdf` に出力されます。

```shell
yarn pdf
```

PDFを開く。

```shell
yarn open
```

PDFの作成と開くを同時に行う。

```shell
yarn start
```

### 入稿データの作成

Docker で実行する（推奨）。`output/press.pdf` に出力されます。

```shell
yarn press
```

ローカル環境で実行する  （Docker Desktop が無い場合は make press の方が推奨です）

```shell
yarn press-local
```
