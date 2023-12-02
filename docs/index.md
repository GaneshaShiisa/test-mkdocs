# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## 自動公開の設定
mainブランチにプッシュしたらGitHub Actionsでページを公開されるように設定する。
リンク先（[Publishing your site](https://squidfunk.github.io/mkdocs-material/publishing-your-site/)）のサンプルをそのまま、`.github/workflows/ci.yml`に作成し、GitHubにプッシュする。

## GitHub側の設定
1. GitHubのプロジェクトページを開き、右上の「Settings」をクリックする。
1. 左側のメニューの中から「Pages」をクリックする。
1. 「Branch」を「gh-pages」に変更して、「Save」をクリックする。

参考：[自分で作ったWebページをインターネット上に公開しよう！ 5. ページの公開](https://prog-8.com/docs/github-pages)