Challenge 1.1 (過濾器): 宣告 data = [9, 9, 1, 2, 2, 2, 5]，利用集合將它去重複後，再次轉換回 list 並印出

<img width="467" height="216" alt="image" src="https://github.com/user-attachments/assets/690d651e-4b8e-485f-a360-9eaf193a7788" />

Challenge 1.2 (雙修學生): 宣告 math_class = {"Alice", "Bob", "Charlie"} 與 cs_class = {"Bob", "David", "Alice"}。找出同時修兩門課的學生並印出

<img width="464" height="198" alt="image" src="https://github.com/user-attachments/assets/6e54b276-4664-4ae0-be58-5843c35e7a18" />

Challenge 1.3 (獨家菜單): 餐廳A有 {"Pizza", "Burger", "Pasta"}，餐廳B有 {"Pasta", "Steak", "Salad"}。用對稱差集 (Symmetric Difference) 找出不是兩家都有的獨家菜色。

<img width="471" height="185" alt="image" src="https://github.com/user-attachments/assets/89b003ba-821a-4864-b792-306aaacef48a" />

Challenge 1.4 (十面骰子): 使用 while 迴圈與 random.randint(1, 10)，持續丟骰子直到收集滿 5 個不重複的數字為止，印出結果。

<img width="481" height="237" alt="image" src="https://github.com/user-attachments/assets/d771a8b7-c0d2-4b35-94ca-713c4cb4e131" />

Challenge 1.5 (找出奇數): 建立集合 nums = {1, 2, 3, 4, 5, 6}。寫一個 for 迴圈，如果數字是奇數 (用 % 2 判斷)，就把它加入到新的集合 odds 中，最後印出

<img width="365" height="234" alt="image" src="https://github.com/user-attachments/assets/f18de2ff-0ab7-4d78-be97-c5aea8b7a7e1" />

Challenge 2.1 (隨機五連星): 使用 while 迴圈與 set，產生 5 個不重複的隨機座標 (範圍 0 到 4)，並印出這個集合。

<img width="498" height="267" alt="image" src="https://github.com/user-attachments/assets/08220ce1-627c-472b-969a-a21f3cee1d3c" />

Challenge 2.2 (檢查腳下): 宣告 mines = {(1,1), (3,3)}。寫一個 if-else，判斷玩家踩下的座標 (2,2) 是否在 mines 集合中。如果在，印出「踩到地雷！」；不在，印出「安全！」

<img width="312" height="217" alt="image" src="https://github.com/user-attachments/assets/06e10a1a-7ed4-4ec5-b544-1cb767c10406" />

Challenge 2.3 (小型佈雷器): 建立一個 3x3 的 logic 矩陣(全填 0)。建立一個集合 mines = {(0,0), (2,2)}。用迴圈將集合內的座標，在 logic 矩陣中對應的位置改成 "X"，並逐列印出。

<img width="337" height="341" alt="image" src="https://github.com/user-attachments/assets/2ff9c4ee-a7b7-47d8-88f7-9dac2ae587ea" />

 Challenge 2.4 (計算安全區): 一個 3x3 的盤面總共有 9 個格子(Universal Set)。如果你的 mines 集合裡有 4 顆地雷，寫程式算出並印出「安全格的數量」 (提示：利用減法 9 - len(mines))。

<img width="497" height="223" alt="image" src="https://github.com/user-attachments/assets/ed391416-b1dd-4f25-84e1-08103219459d" />

Challenge 2.5 (視覺化防護網): 延續 2.3 題的 mines 集合，建立一個 3x3 的迴圈，如果當下座標 (r, c) 在 mines 裡，就印出 💣，否則印出 🔲。印出一個 3x3 的美麗九宮格。

<img width="491" height="278" alt="image" src="https://github.com/user-attachments/assets/0a349967-6c0b-4473-b9c7-2ef2f2acdd0a" />

## 自習心得
這次學習讓我了解如何使用 Python 的雙層迴圈建立 3x3 九宮格，並利用集合判斷座標是否有地雷。透過 if-else 條件判斷，將地雷顯示為 💣，安全格顯示為 🔲，讓我更熟悉迴圈、集合與座標的應用。


## 角色轉換——思考如何教導初學者 (Think about how to teach young people): 試著思考：「如果我要把今天的實作講給弟弟妹妹聽，我該怎麼轉化這些概念？要用什麼生活化的例子或步驟來說明？」整理出你專屬的「教學思路」與「降維說明法」。

我的教學思路與降維說明法
如果我要教弟弟妹妹今天學習的 Python，我會用「踩地雷遊戲」當作生活例子，讓他們更容易理解。
一、我的教學思路
1. 先用生活例子： 把 3x3 九宮格想成一個遊戲地圖，每個格子都有自己的位置。
2. 介紹座標： 用 (r, c) 表示格子的位置，就像教室的第幾排、第幾個座位。
3. 認識集合： 把 mines 想成地雷位置清單，記錄哪些格子有地雷。
4. 學習迴圈： 使用雙層 for 迴圈，一格一格檢查九宮格。
5. 條件判斷： 如果格子在地雷清單裡，就顯示 💣，否則顯示 🔲。
二、我的降維說明法
我會把程式想成一個尋寶遊戲：
- for 迴圈：像巡邏員，一格一格巡視。
- mines 集合：像地雷位置名單。
- if-else：像紅綠燈，判斷要顯示哪個圖案。
- (r, c)：像地圖座標，找到正確的位置。
三、教學心得
我認為教初學者不能一開始就講太多程式專有名詞，而是要先用生活中的例子幫助理解，再一步一步帶入程式碼。透過踩地雷遊戲，可以讓抽象的迴圈、集合和條件判斷變得簡單又有趣。










