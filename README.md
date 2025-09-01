# MyDiaryの概要
## 目的
MyDiaryは個人の日記を管理するサービスです。  
ぜひ、ご利用ください！

## 提供する機能
- 会員登録
- ログイン
    - IDとパスワードによるログイン
    - ログアウト
- 日記投稿
- コメント

## 登録手順
1. /registerにアクセス
1. メールアドレスを入力
1. メールが届いていることを確認
    1. メールに書かれているリンクを踏む
    1. 氏名、生年月日を入れる
1. /login でできることを確認

## ページ一覧
| URL| 内容 | HTMLファイル |
|:---:|:---:|:---:|
| /home | トップページ | index.html |
| /about| 自己紹介 | about.html |

## サンプルコード
変数か型、変数名で表す。例`String name` これで文字列型のnameとして表示
```java
public class Item {
    private String name;
    public String getName() {
        return name;
    }     
}
