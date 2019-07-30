# space-apps-kushimoto.github.io

このリポジトリは Space Apps Kushimoto の公式サイトのリポジトリです。

https://space-apps-kushimoto.github.io/

## ブログの書き方
1. このリポジトリをフォーク。
2. フォークしたリポジトリ上で、`/_posts/`ディレクトリに移動。 例：`https://github.com/[your-name]/space-apps-kushimoto.github.io/tree/master/_posts`
3. Create New Fileをクリック。
4. 記事を書く。
5. プルリクエストを送る。

### 形式
- ファイル名を`YYYY-MM-DD-name-of-post.md`の形式で保存。
- 最初の行に下の形式でメタデータを追加。

```

---
layout: post
title: Your-Title
date: 2016-05-20 21:11:27
---

```

## 開発者向け

```
$ git clone git@github.com:space-apps-kushimoto/space-apps-kushimoto.github.io.git
$ cd space-apps-kushimoto.github.io
$ bundle install --path vendor
```

ローカル環境の起動

```
$ bundle exec jekyll serve --watch --baseurl=""
```

## 参考

https://github.com/ndrewtl/airspace-jekyll
