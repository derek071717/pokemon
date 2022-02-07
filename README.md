# BOLT
## 簡介
Bolt是一款免費將程式碼「可視化」的套件，適合用於「教學」及「初學者」。

## 2D遊戲試做
### 套件下載
- Bolt
- Bolt Kit: Platformer Tutorial Assets
- 
### 放置內容物
- Player
- Enemy
- Objective
- PlatformLarge
- Canvas
- GameObject Left 
- GameObject Right
### 程式碼製作
- Player：移動
  - 角色套件
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E8%A7%92%E8%89%B2%E5%A5%97%E4%BB%B6.png)
  - 呼叫Horizontal內建移動套件
  - 設定Player之Variables → Speed為5 型態Float
  - 使用 按鍵移動x速度值 → 移動距離值 
  - Bolt允許動態創建變量並存取值 → 把值轉為座標即可移動 
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E8%A7%92%E8%89%B2%E5%BA%A7%E6%A8%99%E7%A7%BB%E5%8B%95.png)
- Player：跳躍
  - 透過按鍵賦予角色跳躍力度
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E8%B7%B3%E8%BA%8D%E5%8A%9B%E5%BA%A6.png)
  - 以角色為圓心，向下發射偵測射線 → 偵測圖層是否正確
  - ![圖](https://github.com/derek071717/pokemon/blob/main/Image/%E8%B7%B3%E8%BA%8D%E5%A4%A7%E7%B6%B1.png)
- Enemy：碰撞與加分
  - 球體套件
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E7%90%83%E9%AB%94%E5%A5%97%E4%BB%B6.png)
  - 球體碰撞偵測
  - 球體落地次數=1 則為得分分數
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E7%90%83%E9%AB%94%E7%A2%B0%E6%92%9E%E5%81%B5%E6%B8%AC%E8%88%87%E5%8A%A0%E5%88%86.png)
- GameObject：碰撞框製作
  - 碰撞套件
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E7%A2%B0%E6%92%9E%E6%A1%86%E5%A5%97%E4%BB%B6.png)
  - 指定變數傳輸對象
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E8%AE%8A%E6%95%B8%E5%82%B3%E8%BC%B8%E5%B0%8D%E8%B1%A1.png)
  - ![](https://github.com/derek071717/pokemon/blob/main/Image/%E5%88%A4%E6%96%B7%E6%8E%89%E8%90%BD%E7%89%A9.png)
