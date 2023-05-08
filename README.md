# TReK GT40 GRINIUM ビルドガイド補足

## GRINIUM_firmware
- TReK GT40Plus GRINIUM firmware

- Pro Micro Web Updaterなどを使って書き込むファームウェアです。  
https://sekigon-gonnoc.github.io/promicro-web-updater/index.html

## ファームウェアの種類
- gl516_grinium_via.hex Remap対応ファームウェア
- gl516_grinium_via_rgbmatrix.hex Remap対応RGBマトリクスファームウェア

## Remap用JSONファイル
- grinium.json

## MXソケットとロータリーエンコーダーの排他利用
- ロータリーエンコーダーをはんだ付けする場合  
<img src="image/rotary_encoder.jpg" width="25%" />

----

- MXソケットをハンダ付けし、MX互換キースイッチを使う場合  
<img src="image/mx_socket.jpg" width="25%" />
