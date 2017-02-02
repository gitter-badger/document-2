# Anontown

## Anontownとは
2chの様々な問題点を改善した**登録制匿名掲示板**です。  

## 特徴
### 10秒で終わる簡単なユーザー登録
登録制と聞くと面倒なイメージがありますが、ID・パスワードとスパム対策の画像認証を入力するだけで登録をすることが出来ます。  
メールアドレスなどの個人情報は一切不要です。
登録制にすることによって、アカウント制度がない2chでは実現不可能だった便利な機能を実装しました。  
また、閲覧のみの場合は登録は不要です。
### 登録制だけど匿名
レスをしたりやトピックを建てたユーザーは公開されません。  
その為登録制ですが2chのように匿名なので気軽に書き込めます。
これはredditとの大きな違いです
### トピックを使い続ける事が出来る
dat落ちや、書き込み制限がなく、タイトルやカテゴリ、本文を編集出来るのでトピックを使い続ける事が出来ます。  
また、トピックの編集履歴はwikiのように残る為、荒らしに書き換えられても安心です。
※ただし、トピックが永遠に残ると気軽に建てる事が出来ないので、トピックを建てる時に「単発」を選択すれば、一定期間で落ちるようになります
### マークダウンを使用可能
redditのようにレス、トピックなどにマークダウン記法を使う事が出来ます。
### 投票による自治機能
荒らしや不愉快なレスには低評価、良いレスには高評価をするだけで自治が出来ます。  
これは、運営の介入が難しいローカルルール違反などにも対応できます。  
高評価が多いユーザーはシステムが「信頼出来るユーザー」であると判断する為、
* 連続投稿制限が緩くなる
* 投票の効力が大きくなる
* 多少の低評価ではレスが削除されなくなる

のような事が起こります。  
荒らし対策の為に積極的に投票機能を使いましょう。
### 高機能なWEBアプリ
高機能なWEBアプリを使う事が出来ます。  
WEBアプリの為、お気に入りトピックなどを複数端末間で共有することが可能です。
### 一括管理出来るプロフィール機能
1つのアカウントで複数の**プロフィール**を作ることができ、複数プロフィールが同一アカウントから作られていることは他の人からは分かりません。  
これは、2chのトリップ、BEの代わりに本人証明として使うことが出来ます。
### HASH機能
2chでいうIDのような機能に**HASH**があります。
IDは、日付・板・IPアドレスに依存した値でしたが、HASHは日付・トピック・ユーザーに依存した値です。  
### 板の代わりのタグ
板の場合は新しく作ろうとすると、運営に申請が必要な為面倒でした。  
しかし、タグは自由に設定出来るので面倒な申請は不要です。  
### APIを公開予定
現在は不安定な為、APIの使用は推奨していませんが、近日中にドキュメントを整備し使えるようになる予定です。  
APIを使うことで、クライアントアプリや便利ツールを誰でも作ることが出来ます。

## 向かないこと
2chとは仕様が違うので、向かない(出来ない)事もあります。
* 安価スレ
* 2ch専ブラの使用