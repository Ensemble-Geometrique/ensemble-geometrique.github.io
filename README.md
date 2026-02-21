# Ensemble Géométrique

関東を拠点に活動するアマチュア室内楽プロジェクト。

Jekyll で構築し、GitHub Pages でホスティング。

## 前提

- [rv](https://github.com/spinel-coop/rv)

シェル統合を設定しておくと、ディレクトリ移動時に Ruby バージョンが自動で切り替わる:

    # ~/.zshrc に追加
    eval "$(rv shell init zsh)"

## セットアップ

    rv ruby install
    bundle install

## ローカルビルド

    bundle exec jekyll serve

http://localhost:4000 で確認できる。

## デプロイ

`master` ブランチに push する。
