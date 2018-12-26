### Ex01

開啟IntelliJ 建立New Project

![Imgur](https://i.imgur.com/GO5UJaF.png)

目前在galaxy nexus(android442)上面測式，因此設定API15(Android 4.0.3)

![Imgur](https://i.imgur.com/rWnBmSj.png)

----------

### 1-0 新增加menu

- 來源：[實作Activity上方選單Menu與下拉項目功能][1]  
在Activity出現在畫面之前，會自動呼叫Activitiy的「onCreateOptionsMenu」方法  
方法的參數帶來一個menu物件  
當按下選單中的任一個項目時，會自動呼叫Activity的onOptionsItemSelected方法  


使用IDEA建立Menu方式如下

- menu item相關設定  
id設定(action_settings,action_help)是給程式判斷用的  
title設定(設定及Help)則會顯示在畫面  
ifRoom: 若Action區域有空間，就會顯示  

- 自動產生程式  
點選java程式之後  
ctrl+o  

1-0-1

點選app目錄右鍵，New/ Android Resource File

![Imgur](https://i.imgur.com/UkLMmJn.png)

加入MenuItem如下

![Imgur](https://i.imgur.com/R0SHKom.png)

設定Item內容如下

![Imgur](https://i.imgur.com/GyXze6F.png)

測試結果如下

![Imgur](https://i.imgur.com/F2PMaAW.png)

[1]:https://litotom.com/2017/07/31/ch7-4-menu/
