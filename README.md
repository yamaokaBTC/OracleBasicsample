# OracleBasicsample

## セットアップ・起動  
npm install  
node index.js  

## 解説  
オラクルの書き込みと読み込みのみを実装したシンプルなサンプルコードです。  
DAGへデータの書き込みを行うため、実行するウォレット内にある程度bytesが入っている必要があります。  

index.js  
メインのプログラム。オラクルの読み書きはこちらのコードで実行しています。  
ウォレットのパスコード入力後に自動で行われます。  
  
wallet.js  
headless-byteballのstart.jsと全く同じです。  
index.jsにはアドレスを表示したりチャットに接続させるコードが入っていないため、  

ペアリングした後チャット経由でbytesをウォレットに送るために配置しています。オラクルの読み書き自体には一切関係ありません。  

詳細はこちらから  
http://byteball.memo.wiki/d/%A5%AA%A5%E9%A5%AF%A5%EB%A4%CE%C6%C9%A4%DF%BD%F1%A4%AD%A5%B5%A5%F3%A5%D7%A5%EB%A5%B3%A1%BC%A5%C9
