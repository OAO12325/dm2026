Challenge 1.1 (全 1 矩陣): 使用二維的 List Comprehension，產生一個 3x3 且全部填滿數字 1 的矩陣並印出

<img width="531" height="110" alt="image" src="https://github.com/user-attachments/assets/567bee41-9f4c-431c-bcdf-a07ab9d5ce38" />

Challenge 1.2 (狙擊右上角): 宣告一個 3x3 全為 0 的矩陣，將「右上角」的值修改為 99，並逐列印出

<img width="266" height="273" alt="image" src="https://github.com/user-attachments/assets/a4475391-9549-4a22-bf0e-7532ec5dd14a" />

Challenge 1.3 (面積總和): 給定矩陣 grid = [[1, 2], [3, 4]]，使用巢狀迴圈計算所有數字的總和 (1+2+3+4)

<img width="370" height="233" alt="image" src="https://github.com/user-attachments/assets/027d4abc-50e0-464c-9f58-ee243f56838b" />

Challenge 1.4 (尋找座標): 給定矩陣 grid = [[0, 0], [0, 5]]，寫程式用迴圈找出數字 5 的絕對座標 (r, c)

<img width="589" height="188" alt="image" src="https://github.com/user-attachments/assets/41aef309-7e24-4889-bf12-0080d9108774" />

 Challenge 1.5 (對角線繪圖): 建立一個 3x3 全為 0 的矩陣，利用迴圈與 if row == col:，將對角線上的 0 換成 8，並逐列印出

<img width="492" height="347" alt="image" src="https://github.com/user-attachments/assets/4da7ab28-e2b5-4155-bf90-4f6bd79677be" />

Challenge 2.1 (客製化 5x5 地圖): 初始化一個 5x5 的 visible 矩陣，全塞滿 🟦。將四個角落修改為 🏝️，然後用 join() 印出

<img width="601" height="340" alt="image" src="https://github.com/user-attachments/assets/6aeb70a3-4163-475e-a3ad-3b3d6d02f15a" />

Challenge 2.2 (十字瞄準線): 建立一個 5x5 的矩陣，預設全為 🔲。使用迴圈將第 2 列與第 2 行 (也就是正中間的十字) 替換為 🔴，並印出

<img width="545" height="298" alt="image" src="https://github.com/user-attachments/assets/e25b1287-f366-4fd8-b22d-92aa7377d25b" />

Challenge 2.3 (真實與虛幻): 宣告 logic = [[0, "X"], ["X", 0]] 與 visible = [["🔲", "🔲"], ["🔲", "🔲"]]。寫一段程式，自動根據 logic 的值，如果發現是 "X" 就把 visible 對應座標改成 🚩，最後印出 visible

<img width="506" height="340" alt="image" src="https://github.com/user-attachments/assets/13ce30ff-47de-4076-a151-578e46225dec" />

Challenge 2.4 (邊界巡邏): 建立一個 4x4 的全 0 矩陣。使用迴圈將矩陣的「最外圍邊界」(第 0 列、最後一列、第 0 行、最後一行) 全部改成 1，並逐列印出

<img width="638" height="266" alt="image" src="https://github.com/user-attachments/assets/36a26925-ee11-43e5-9ffc-6ea9d4368b24" />

Challenge 2.5 (九宮格印鈔機): 定義中心座標 cx, cy = 1, 1。建立一個 3x3 的 🔲 矩陣。利用兩個迴圈 (dx 從 -1 到 1，dy 從 -1 到 1)，將 (cx+dx, cy+dy) 的位置全部塞入 💲，最後印出 (會是一個全滿的錢幣矩陣)

<img width="635" height="278" alt="image" src="https://github.com/user-attachments/assets/f33de8b7-d928-4f32-8078-9dc2b7221e13" />

## 自習心得:

透過這次 Python 練習，我學會了使用變數、if-else 判斷式、for 迴圈及雙層迴圈來操作矩陣，也了解如何利用座標修改指定位置。從簡單的圖形排列到地雷盤面，讓我更熟悉程式邏輯，也提升了解決問題的能力。

## 角色轉換——思考如何教導初學者 (Think about how to teach young people): 試著思考：「如果我要把今天的實作講給弟弟妹妹聽，我該怎麼轉化這些概念？要用什麼生活化的例子或步驟來說明？」整理出你專屬的「教學思路」與「降維說明法」。
一、教學思路
如果我要教弟弟妹妹學習 Python，我會先用生活中的例子來解釋，不會一開始就講太多程式專有名詞。例如，可以把矩陣想像成教室座位表，每個位置都有自己的座標，再利用程式決定每個位置要放什麼圖案。讓他們先理解概念，再慢慢學習程式寫法。
二、降維說明法
1. 變數： 把變數想成一個盒子，可以放入數字或文字。
2. if-else： 就像紅綠燈，紅燈停、綠燈走，依照條件做不同動作。
3. for 迴圈： 就像每天刷牙，重複做相同的事情。
4. 雙層迴圈： 就像教室座位表，先決定第幾排，再決定第幾個座位。
5. 矩陣： 就像井字遊戲的格子，每個格子都有自己的位置。
6. 座標： 就像地圖上的地址，可以找到指定的位置並修改內容。
三、我的教學步驟
- 第一步：先用生活例子介紹概念。
- 第二步：畫出簡單的格子，讓初學者觀察。
- 第三步：寫出簡單的 Python 程式。
- 第四步：實際執行程式，觀察結果。
- 第五步：讓初學者自己修改數字或圖案，練習思考。
四、我的心得
透過這次練習，我發現程式設計不一定要用複雜的方式解釋，也可以利用生活中的例子讓初學者理解。像是把矩陣想成座位表，把迴圈想成重複動作，能讓學習變得更簡單。我也學會換個角度思考，讓自己不只會寫程式，也能把學到的知識教給別人。








