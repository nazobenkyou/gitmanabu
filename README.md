# gitmanabu

gitコマンドを学ぶまで！

## 1. git clone

クローンするのはレポジトリのコードをダウンロードすることです。二つのやり方があります

```bash
git clone git@github.com:ervitis/gitmanabu.git
```

```bash
git clone https://github.com/ervitis/gitmanabu.git
```

一番目ssh使うのでセキュリティーに大してとてもいいです。[ssh keyは必要です](https://git-scm.com/book/ja/v2/Git%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC-SSH-%E5%85%AC%E9%96%8B%E9%8D%B5%E3%81%AE%E4%BD%9C%E6%88%90)


## 2. git status

ステータスはファイルをコミットしたとコミットしてなかったファイルを現れてる

```bash
git status
```

[![asciicast](https://asciinema.org/a/UHspzb14PMbaUAq2IQx03TB2K.svg)](https://asciinema.org/a/UHspzb14PMbaUAq2IQx03TB2K)


## 3. git add

ファイルやコードを書いてコミットしたいとき最初はgit addしないといけない

[![asciicast](https://asciinema.org/a/qp37wk2rAo9DvUa0YbAAwbEbe.svg)](https://asciinema.org/a/qp37wk2rAo9DvUa0YbAAwbEbe)

```bash
touch helloworld.txt

git add helloworld.txt
```

もしコミットファイルを変更して全部のファイルをコミットしたい

```bash
git add -u
```

もし全部コミットしたい

```bash
git add .
# このコマンド危ないかもしれない
```


## 4. git commit

コミット

```bash
git commit -m "add hello world file"
```



## 5. git checkout

いろいろできます

- ブランチを変わる
- ファイルの最後のコミットに戻すことになる

## 6. git push

## 7. git pull

## 8. git stash
