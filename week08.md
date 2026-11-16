Challenge 1.1 (階乘計算): 使用 math.factorial 計算 6 的階乘並印出

<img width="317" height="157" alt="image" src="https://github.com/user-attachments/assets/028be840-e600-485c-9f3f-9f451f047cbb" />

Challenge 1.2 (挑選炸彈): 盤面有 10 顆地雷，如果你要隨機選出 3 顆來解除，有多少種組合？用 math.comb 算出 
C (10,3)

<img width="363" height="152" alt="image" src="https://github.com/user-attachments/assets/145ca3fa-b65a-4573-aa79-ac72f5864243" />

Challenge 1.3 (死亡機率): 盤面有 81 格，地雷 10 顆。印出「隨機點擊一格的死亡機率」，請用百分比表示並取小數點後一位

<img width="531" height="189" alt="image" src="https://github.com/user-attachments/assets/52dd6aab-4463-49af-9712-325bc50ca9d0" />

Challenge 1.4 (二維計數): 給定矩陣 matrix = [[1, 0, 1], [0, 0, 0]]。寫一個迴圈，計算矩陣內總共有幾個 1

<img width="382" height="250" alt="image" src="https://github.com/user-attachments/assets/867bb775-a6c6-40ea-8ef5-96c2ac5dab22" />

Challenge 1.5 (期望值算力): 某寶箱有 20% 機率獲得 100 元，80% 機率失去 10 元。算出並印出這個寶箱的期望值

<img width="682" height="229" alt="image" src="https://github.com/user-attachments/assets/554719b1-2d92-4cd7-8a75-bb56537d5a21" />

Challenge 2.1 (九宮格計數): 定義 logic = [["X", 0, "X"], [0, 0, 0], ["X", 0, "X"]]。直接透過索引查看 4 個角落，將所有 "X" 累加起來並印出總數

<img width="543" height="263" alt="image" src="https://github.com/user-attachments/assets/44946903-914c-422b-baa8-d0babe0e3b42" />

Challenge 2.2 (剩餘安全區機率): 盤面有 81 格，10 顆雷。你已經點開了 11 個安全的格子。請算出並印出「現在盲點一格的死亡機率 (百分比)」

<img width="500" height="253" alt="image" src="https://github.com/user-attachments/assets/3a52959f-fd0f-47f8-a7a6-4521fb512e66" />

Challenge 2.3 (鄰居檢查器): 假設某格子的 neighbors = [0, "X", "X", 0, 0] (為了簡化，直接給狀態串列)。寫迴圈算出裡面有幾個 "X"

<img width="411" height="226" alt="image" src="https://github.com/user-attachments/assets/cb3c3f63-f145-48be-aea4-2fdcf2286c71" />

Challenge 2.4 (更新盤面): 宣告 board = [[0, 0], [0, "X"]]。使用巢狀迴圈走訪，如果發現 board[r][c] 是 0，就直接把它改成數字 1 (我們假裝已經算好了)，最後印出 board

<img width="410" height="207" alt="image" src="https://github.com/user-attachments/assets/758c0072-32b6-4fa4-a867-602c4efa19db" />

Challenge 2.5 (地雷密度評估): 撰寫一段程式，比較兩個格子的威脅度。A格周圍 8 個格子有 3 顆雷，B格周圍 5 個格子 (在邊緣) 有 2 顆雷。算出兩者的地雷密度 (百分比)，並印出哪一個比較危險

<img width="438" height="456" alt="image" src="https://github.com/user-attachments/assets/58faeee2-4f81-4b3b-a18e-cb2f3318e1ec" />

## 自習心得:

這次實作讓我學會使用 Python 巢狀迴圈、條件判斷及數學計算，了解如何計算地雷密度並比較不同格子的危險程度。透過踩地雷遊戲的例子，讓我更熟悉程式邏輯，也提升了解決問題的能力。

## 角色轉換——思考如何教導初學者 (Think about how to teach young people): 試著思考：「如果我要把今天的實作講給弟弟妹妹聽，我該怎麼轉化這些概念？要用什麼生活化的例子或步驟來說明？」整理出你專屬的「教學思路」與「降維說明法」。

我的教學思路與降維說明法
一、我的教學思路
如果我要教弟弟妹妹今天學習的 Python，我會用「踩地雷遊戲」當作生活例子，讓他們更容易理解。
1. 矩陣： 像教室座位表，每個位置都有自己的座標。
2. 巢狀迴圈： 像巡邏員，一排一排檢查每個格子。
3. 條件判斷： 像紅綠燈，判斷格子是否有地雷。
4. 數學計算： 利用機率計算踩到地雷的風險。
5. 地雷密度： 比較不同格子的危險程度，找出哪個位置比較安全。
二、我的降維說明法
我會用簡單的生活例子解釋：
- for 迴圈：像點名，一個一個檢查。
- if-else：像選擇題，根據條件決定答案。
- count += 1：像計算人數，每找到一個就加一。
- math.factorial()：像計算數字連續相乘。
- math.comb()：像從一群人中挑選幾個人，不需要考慮順序。
- 期望值：像抽獎，計算長期平均可以賺多少錢。
- 地雷密度：像比較兩個袋子的危險程度，看哪個袋子的地雷比例比較高。
三、教學心得
我認為教初學者要先用生活例子幫助理解，再慢慢帶入程式語法。透過踩地雷遊戲，可以把抽象的數學、迴圈和條件判斷變得簡單有趣，也能培養邏輯思考與解決問題的能力。
