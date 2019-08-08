## まゆですよぉ
借金を管理しますよぉ

## 必要なもの
* Python >= 3.6.2
* pip >= 19.2.1


## install
リポジトリを clone
`git clone https://github.com/e-jima/otaku_shakkin_chan.git`

ライブラリをインストール
`pip install -r requirements.txt`

## 注意
`secret/secret.yml` に、[Twitter Developer]([https://developer.twitter.com/]) から取得したキーを、以下のように記述する

```secret.yml
twitter:
  mayu:
    consumer_key: YOUR_CONSUMER_KEY
    consumer_secret: YOUR_CONSUMER_SECRET
    access_token: YOUR_ACCESS_TOKEN
    access_secret: YOUR_ACCESS_SECRET
```