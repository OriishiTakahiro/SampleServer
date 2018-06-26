# SampleServer
知能情報工学セミナーの演習用プログラムです．  
Wiresharkを使って，lo (local loopback)インターフェイスをキャプチャしてください．

### 実行方法
```sh
dep ensure -update
# HTTPでの起動
go run server.go
# HTTPSでの起動
go run server.go -tls
```

### リクエスト送信
```sh
# HTTPでの通信
sendReq.sh
# HTTPSでの通信
sendReq.sh -tls
```
