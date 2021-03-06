# CycleGan
Use cyclegan to transfer the relationship between volume and price

過往研究指出，量價關係是一種特別的關係，擁有著聯合作用，單看一項終究導致失敗或不完整的結果。而近幾年來神經網路發展迅速，許多深度學習(Deep Learning)的方法與獨特的網路架構被提出，在各大領域上有卓越的表現。目前有許多神經網路應用在預測股價方面上，較常見的是使用長短期記憶(LSTM)架構，不過通常都將量與價視為一種資料而非兩個具有獨特關係的資料。因此本研究想要嘗試使用深度學習來學習量價間的關係，再應用此結果預測股價，進而達到技術分析的目的。 

主要來說我們的貢獻有兩種: 

1.使用循環生成對抗網路來觀察量價關係，並且證明量價關係可以被此神經網路所學習。 

2.透過假設循環生成對抗網路的結果來預測股價。

![image](https://user-images.githubusercontent.com/63281304/112474419-8fb6a300-8daa-11eb-8925-c1c11e6f1c32.png)

![image](https://user-images.githubusercontent.com/63281304/112474496-ab21ae00-8daa-11eb-8fd6-39fca9508f81.png)

