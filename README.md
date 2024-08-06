# サンプルページ

[https://a-ofuji-vista.github.io/\_template-html-coding/](https://a-ofuji-vista.github.io/_template-html-coding/)

# 使用技術

- Vite
- Sass (SCSS)
- Stylelint
- Prettier
- EditorConfig
- vite-plugin-handlebars
- GitHub Pages

# ディレクトリ構成

```sh
/
├── src/
│   ├── components/ # HTMLのコンポーネントパーツを格納
│   │   ├── header.html
│   │   └── xxx.html ...
│   ├── js/ # メインのモジュールJSファイルを格納（一応置いてる）
│   │   └── main.js
│   └── public/
│   │   └── assets/ # そのまま移動させたいファイルを必要に応じて格納
│   │       ├── images/
│   │       │   └── xxx.jpg ...
│   │       └── js/
│   │           └── xxx.js ...
│   ├── scss/ # 各記法に合わせたディレクトリ構成
│   │   └── style.scss
│   ├── index.html
│   └── xxx.html # 複数ページを追加する場合
└── package.json
```

# ローカル環境にクローンする準備

**1. VScodeのエクスプローラーから構築したいディレクトリを開く**

**2. VScodeのターミナルで構築したいディレクトリに移動**

「cd 」までタイプし、エクスプローラー（Finder）からターミナルに目的のディレクトリをドラッグ&ドロップ

```bash
cd ここにの該当のディレクトリをドラッグ＆ドロップ
```

# ローカル環境にクローンする方法

**1. クローンしたいアプリケーションのGithubからURLを取得する。**

Githubのリポジトリのトップページ > codeのボタン > HTTPS用のクローンURLをコピーする。

**2. クローンを実施する。**

1のステップでコピーしたURLを用いて、クローンを実施する。以下コマンドを実行。

```bash
git clone コピーしたGithubのURL
```

もしもクローンするアプリケーションの名前を変更したい場合は、以下のようにコマンドの末尾に設定したいアプリ名を追加する。

```bash
例）クローンしたアプリをtest_projectという名前に変更したい場合
git clone コピーしたGithubのURL test_project
```

**3. クローン元のリポジトリとの連動を解除する。（自身のリポジトリと紐付けをしたい場合）**

クローンした直後はクローン元のリポジトリと紐づいている状態なので、自身のリポジトリと紐付けをしたい場合は以下のコマンドで.gitディレクトリを削除する。

```bash
rm -rf .git
```

# ローカルで開発を開始する

**1. Viteをインストール。**

以下のコマンドを実行してViteをインストールする。

```bash
npm install create-vite
```

**2. 開発サーバを起動する。**

以下のコマンドを実行すると開発サーバが起動する。

```bash
npm run dev
```

# 関連・参考記事

## Githubリポジトリをローカル環境にクローンする方法

[Gitリポジトリをローカル環境にクローンする方法 - Qiita](https://qiita.com/sh10n/items/f5edb7293aaffebe35a7)

## Vite環境構築

[【詳細版】Viteでコーダーのコーディング環境（HTML（ejsライク：ハンドルバー化）・Sass・JS）を作る | Web production note](https://coding-memo.work/development/1274/)

## CSS / Sass (SCSS)のルール

[よりよいCSSを書くための、CSS / Sass (SCSS) 30のルールとその理由](https://zenn.dev/kagan/articles/1aa466bb6ef8eb)
