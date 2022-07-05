
# anti-pattern-wiki

アンチパターンや誤謬を取りまとめたWiki。

以下のURLよりアクセス可能。（GitHub Pagesにて公開）

- https://tanakanata7190.github.io/anti-pattern-wiki/


## 【メモ：MDWikiの使い方】

### 1. ローカル編

1-1. 以下のページから、`mdwiki-0.6.2.zip`を、ローカルにダウンロード

- https://github.com/Dynalon/mdwiki/releases

1-2. ZIPファイルを解凍し、以下の構成である事を確認。

```
./mdwiki-0.6.2
  ├ GPLv3.txt
  ├ index.md
  ├ LICENSE.txt
  ├ mdwiki.html
  ├ mdwiki-debug.html
  ├ mdwiki-slim.html
  └ README.md
```

1-3. `mdwiki.html`をブラウザで開く

- IE：サポートしてない
- Firefox：サポートしている
- Chrome：起動オプション（ `--allow-file-access-from-files` ）の設定が必要
    - 参考：https://www.cg-method.com/md-wiki/#index_id5
    - 参考：https://stakiran.hatenablog.com/entry/2018/03/24/103208

1-4. `index.md`を適当に修正し、上書き保存し、再度`mdwiki.html`を開く

- 修正内容が反映されている事を確認する


### 2. GitHub Pages編

2-1. 公式サイトにて、GitHubアカウントを作成

- https://github.com/signup

2-2. 公式サイトを元に、GitHub Pagesを作成

- https://pages.github.com/
- ちなみに、
    - リポジトリ名は、`{username}.github.io`でもいいし、`{適当なプロジェクト名}`でもいい
    - 前者だと、`https://{username}.github.io`でアクセスできて、
    - 後者だと、`https://{username}.github.io/{適当なプロジェクト名}`でアクセスできる

2-3. 「1. ローカル編」のファイル群を、2-2で作成したプロジェクトにpush

2-4. しばらく待つ

- 反映に１時間くらいかかる時もあるらしいので、気長に待つ

2-5. 2-2で示したURLにアクセスする

- これでGitHubのホスティングサービスを用いて、無料でWikiの公開ができる。おめでとう。
