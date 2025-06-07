## インストール
### Support raw 802.11 traffic (and monitor mode) for wireless adapters
- 無線LANで使う802.11のパケットを解析できるようになる
## 設定
### 列
- [設定]-[外観]-[列]
## Https
1. tlskeys.txtを作成
2. 環境変数"SSLKEYLOGFILE"でtlskeys.txtを設定
3. PC再起動
4. [設定]-[Protocols]-[TLS]-[(Pre)-Master-Secret log filename]にtlskeys.txtを設定

## フィルタリング
- http
- tls
- ip.addr == 192.168.1.10
## TLSバージョン
- Client Hello
- Alert Level: Fatal protocol_version
