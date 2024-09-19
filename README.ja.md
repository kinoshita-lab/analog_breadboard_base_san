# アナログブレッドボードベースさん

アナログ回路を作りたい。正負電源を作るのが大変だ。こちらにございます。

![alt text](usage.jpg)

## 特徴

- 15V USB PD対応しています。アダプター等が対応していれば、その電源を使用します。
- そうでない場合、内蔵のDCDCコンバータで15Vを生成します。この場合、使用可能電力は限られます。
  - ノートPCなどを接続して使用可能な可能性が高いです。M2のMacbook Airと、CHUWI Freebookで動作を確認しています。
- (わかっている人へ)USB PDの15Vと、unregulatedな-15Vをそのまま引き出せるテストポイントもあります。