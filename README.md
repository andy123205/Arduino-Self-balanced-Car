# Arduino-Self-balanced-Car
Introduction for PID

![pid](https://cloud.githubusercontent.com/assets/13445632/12025766/f3237312-adec-11e5-949a-95b9f43ffc0a.png)

積分實作

黎曼和:errorSum += error * timeChange
![pid1](https://cloud.githubusercontent.com/assets/13445632/12025802/3f752fa8-aded-11e5-8c81-0abdfaa9e82f.png)

微分實作

斜率: dError = error / timeChange
![pid2](https://cloud.githubusercontent.com/assets/13445632/12025808/492f4876-aded-11e5-9c1c-5bd14edd6d00.png)

時間軸的概念

millis() 函式簡介[1]

millis() 函式會回傳 Arduino 從開始執行程式一直到目前為止的千分之一秒數值(number of milliseconds)，這個數值在大約 50 天後會溢位(overflow)，屆時會從 0 開始計數。
![pid3](https://cloud.githubusercontent.com/assets/13445632/12025809/492f5eb0-aded-11e5-9d51-d490ae25fe26.png)

![pid4](https://cloud.githubusercontent.com/assets/13445632/12025807/492e3da0-aded-11e5-94c5-30a572d586ea.png)


參考資料

[1]時間軸
http://coopermaa2nd.blogspot.tw/2011/04/millis.html
