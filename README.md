# DemoWithFacebookSharing

A demo with facebook sharing function using Social Framework.

經測試後發現，這個Social框架的SLComposeViewController類別會有以下問題點：
* 若**有安裝**facebook app(在手機上)，SLComposeViewController的資訊無法正常帶出，如下左圖；  
* 若**沒有安裝**facebook app(在模擬器上)，SLComposeViewController的資訊可正常帶出(text, Album, Location, Audience)，如下右圖；  

<div align="center">
  <img src="https://github.com/jhsiao21/DemoWithFacebookSharing/blob/master/i5s.jpeg"> 
    <img src="https://github.com/jhsiao21/DemoWithFacebookSharing/blob/master/simulator.jpg"> 
</div>
