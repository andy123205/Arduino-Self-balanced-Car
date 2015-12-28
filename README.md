# Arduino-Self-balanced-Car
Introduction for PID

![pid](https://cloud.githubusercontent.com/assets/13445632/12025766/f3237312-adec-11e5-949a-95b9f43ffc0a.png)

積分實作

黎曼和:errorSum += error * timeChange
![pid1](https://cloud.githubusercontent.com/assets/13445632/12025971/199cd16c-adef-11e5-9fe0-b610b202cd03.png)

微分實作

斜率: dError = error / timeChange
![pid2](https://cloud.githubusercontent.com/assets/13445632/12025973/1d369e8e-adef-11e5-972e-6e51ef14cdac.png)

時間軸的概念

millis() 函式簡介[1]

millis() 函式會回傳 Arduino 從開始執行程式一直到目前為止的千分之一秒數值(number of milliseconds)，這個數值在大約 50 天後會溢位(overflow)，屆時會從 0 開始計數。
![pid3](https://cloud.githubusercontent.com/assets/13445632/12025809/492f5eb0-aded-11e5-9d51-d490ae25fe26.png)

![pid4](https://cloud.githubusercontent.com/assets/13445632/12025942/b206e0ba-adee-11e5-83f5-12d814e22fc0.png)


參考資料

[1]時間軸
http://coopermaa2nd.blogspot.tw/2011/04/millis.html
