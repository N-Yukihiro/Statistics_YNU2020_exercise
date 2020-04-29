# 2020年度春学期開講「社会分析のための統計基礎」演習用ページ
2020年度春学期開講「社会分析のための統計基礎」演習用ページです．

授業の回数に応じたRmarkdownを公開します．
各自こちらのコードを参考に演習を進めてください．

なお，次のコードをRのコンソール上で実行することでこのレポジトリを各自のフォルダにコピーできます．

初回は次のようにコードを実行します．
```
install.packages("git2r")  # 初回のみ
library(git2r) # 利用時は毎回
clone(url = "https://github.com/N-Yukihiro/Statistics_YNU2020_exercise.git",
      local_path = "exercise") # 初回のみ
```

このgithubのレポジトリが更新された場合は，次のようにコードを実行してフォルダの内容を更新します．

```
library(git2r) # 利用時は毎回
config(user.name="Unkown", user.email="test@example.com") # 初回のみ．各自の名前やメールアドレスに変更．
setwd("exercise")
git2r::pull()
```
