# 楽天お買い物Bot

## 概要

### QRcode
<img src="https://user-images.githubusercontent.com/38125792/115953781-65324400-a528-11eb-9d21-e1b5b4fda547.png" width=20% >

### 目的
- LINEbotの開発
- 楽天APIの利用
- HEROKUでデプロイ

### 内容
- LINEからテキストメッセージを取得
- 入力値で楽天APIを用いて商品検索を行い、先頭の商品のジャンルを取得
- 再び楽天APIを使い、取得したジャンル内で、入力値で検索
- 取得した「商品概要」・「画像URL」・「価格」・「商品のリンク」を、表示

### 環境
- MacOS BigSur 11.2.3
- Ruby 2.5.7
- Ruby on Rails 5.2.4
