　gitは分散管理型のバージョン管理システムである。また、変更履歴が残る、
変更した箇所に戻ることができる、他人と共同編集できるなどの特徴を持つ。
　コミットとはファイル作成・変更・削除の記録である。
　レポジトリとは、gitが管理するプロジェクトのフォルダである。
ローカルレポジトリとリモートレポジトリがある
リモートレポジトリでは、ローカルリポジトリでcommitされた変更を反映させる。
リモートレポジトリにある内容をローカルレポジトリに反映させる。
　ブランチは、作業を枝分かれさせることができる。

リポジトリ、変更の作成のコマンド
 git init　指定した名前のローカルリポジトリを作成する
 git clone　プロジェクトとすべてのバージョン履歴をダウンロードする
 git status　コミット可能なすべての新規または変更のあるファイルを一覧で表示する
 git diff　まだステージされていないファイルの差分を表示する
 git commit コミットを実行する

変更、ファイルの整理のコマンド
 git branch　[]　新規ブランチを作成する
 git checkout　指定されたブランチに切り替える
 git merge　指定されたブランチの履歴を現在のブランチに統合する
 git rm 作業ディレクトリからファイルを削除する
 git mv　ファイル名を変更する

履歴の確認のコマンド
 git log　ログを表示する。
 git show 指定されたコミットのメタ情報と変更内容を表示する

コミットの修正のコマンド
 git reset　コミットをリセットする
