# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリは、ネット上にあり、複数人と共有できる。
- ローカルリポジトリは、自分のPC内にあり、個人で使用する。



## プッシュとマージの違いは何でしょうか？
- プッシュは、ローカルリポジトリの変更履歴をリモートリポジトリに反映すること。
- 一方マージは、他のブランチの内容を別のブランチに反映することなので、ローカルリポジトリ内でもリモートリポジトリ内でも実行出来るという違いがある。


## コミットとプッシュの違い
- コミットがローカルリポジトリ内における変更作業なのに対し、プッシュは、ローカルリポジトリからリモートリポジトリへの変更作業という違いがある。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 変更内容が分かりやすいように詳細に書く。プロジェクトごとのルールがある場合はそれに従う。
- コミットメッセージに使用する代表的なプレフィックスは以下です。
  - feat: 新しい機能
  - fix: バグの修正
  - docs: ドキュメントのみの変更
  - style: 空白、フォーマット、セミコロン追加など
  - refactor: 仕様に影響がないコード改善(リファクタ)
  - perf: パフォーマンス向上関連
  - test: テスト関連
  - chore: ビルド、補助ツール、ライブラリ関連


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージする場合は、他の人に確認してもらうことが出来ないが、プルリクエストでのマージは他の人が確認後にマージするので、ミスに気づきやすい。



## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 処理を書いた人とまず相談し、下記３通りの対応を行う。
  - 先にマージされた変更内容を取り込む
  - 後にマージしようとしている変更内容を取り込む
  - どちらの変更内容も取り込む
