# インターフェース誌 AmazonRanking
　Interface誌の販売ランキング（Amazon調べ）を表示します．<br>
 Java + Swingを使用しています(JDK15)．<br>
 ウェブ・スクレイピングにはjsoupを使っています．<Br>
 
## How to use
AmazonScrape-1.4.jarをダウンロードしてください．<br>
Please download AmazonScrape-1.0.jar file<br>
<br>
いわゆるFat Jarになっており，ライブラリを含んでいます．<br>
The file is fat jar, libraries are included.<br>
<br>
次の様に実行します．<br>
The application is executed by following command.<br>
<br>
`$ java -jar AmazonScrape-1.0`<br>
<br>
Raspbian OS, Windows10で動作確認しています．<br>
We can use the application on Raspbian, Windows 10.<br>

 ## App can throw Ranking data to IBM Cloud(cloudant)
If you use this function, you need to get EndPoint and IAM key to connect IBM cloud.
App GUI has TextFields to input those values.
