# Powershell_DoS_Script (田代砲)
***PowerShell 7の使用を強く推奨***  
ただhttpリクエストをUA偽装して送りまくるだけです。  
Windows Powershelにコピペして実行できます。ps1ファイルで実行するとパフォーマンスが低下します。  
  
※TLSフィンガープリントをspoofする機能やproxyを刺す機能等はありません。  
**※実験用又は教育目的の物です。他人のサイトやサービスに対しては絶対に使用しないでください。これに関する一切の責任は負いかねます。**
***Only for Educational Purposes***

http_flood6: DoS攻撃検知回避機能とproxyに対応しました。使用する場合は  
XX.XX.XX.XX:port  
XX.XX.XX.XX:port  
XX.XX.XX.XX:port  
-------︙---------  　　　　
のように記述したproxy.txtを実行するディレクトリに設置してください。  
http_flood5:   
http_flood4: リクエストヘッダの内容を変更しました。  
http_flood3: ユーザエージェントの他にリファラ等も偽装します。  
http_flood2: ダミーユーザエージェントの数が非常に多いやつです。
