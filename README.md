# Lily58 Lite Rev.2 ZMK Config (Attempt)

このリポジトリは、Lily58 Lite Rev.2 に SparkFun Pro Micro RP2040 を搭載して ZMK Firmware で動かす挑戦をした記録です。

### 注意事項
Lily58 Lite Rev.2 に Pro Micro RP2040 互換ボードを搭載し、TRRSケーブル経由の有線分割（Full-Duplex Wired UART）を試みました。  
左ハーフは単独で動作するものの、TRRSで左右を接続すると左ハーフがフリーズし、右ハーフのキー入力が一切反応しない問題が発生しました。

結果としてZMKへの移行を断念し、QMKに戻しました。  
**この構成ではZMKは動作しません**。参考として残していますが、自己責任でご利用ください。