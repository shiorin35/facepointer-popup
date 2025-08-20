# facepointer-popup
Canva埋め込みページ

## ローカル環境

ターミナルでプロジェクトルートに移動して、以下のコマンドを実行します。


1. Pythonを使用する場合

PythonのHTTPサーバーを起動します。

```bash
python3 -m http.server 8000
```

ブラウザで `http://localhost:8000` にアクセスします。

停止する場合は `Ctrl + C` を押します。

2. Node/npmを使用する場合

Node/npm ベースの静的サーバーを起動します。

```bash
npm install -g serve
npx http-server -p 8000
or
serve -s . -l 8000
```

ブラウザで `http://localhost:8000` にアクセスします。

停止する場合は `Ctrl + C` を押します。

## 便利なコマンド

1. ピクセルサイズを取得するコマンド

```bash
sips -g pixelWidth -g pixelHeight path/to/image.png
```

2. 画像のメタデータを取得するコマンド

```bash
mdls path/to/image.png
```

3. ファイルサイズ(バイト)を取得するコマンド

```bash
stat -f "%z bytes %N" path/to/image.png
```
