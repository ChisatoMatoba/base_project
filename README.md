新しいプロジェクト用のリモートリポジトリを作成してから以下を実行

```
# 元のリポジトリをベアクローン
% git clone --bare https://github.com/ChisatoMatoba/base_project.git

# 元のリポジトリ情報をミラープッシュ
% cd base_project.git
% git push --mirror git@github.com:ユーザー名/コピー先.git  

# 元のリポジトリ情報を削除
% cd ..
% rm -rf base_project.git
```
