Challenge 1.1 (平方函數): 定義一個函數 square(x)，回傳 x 的平方。呼叫 square(6) 並印出結果

<img width="306" height="143" alt="image" src="https://github.com/user-attachments/assets/b24f7ba1-7ef6-4676-9713-30ba838b32f2" />

Challenge 1.2 (偶數過濾器): 定義一個函數 is_even(n)，如果 n 是偶數回傳 True，否則 False。測試數字 7

<img width="352" height="201" alt="image" src="https://github.com/user-attachments/assets/7b47dced-6bfb-48da-9bc0-c713caef4ae4" />

Challenge 1.3 (上限函數): 寫一個函數 clamp_top(val, limit)。如果 val 大於 limit 就回傳 limit，否則回傳 val。測試 clamp_top(15, 10)

<img width="461" height="199" alt="image" src="https://github.com/user-attachments/assets/71337728-149d-4042-a90e-cb4a28947d80" />

Challenge 1.4 (點的位移): 寫一個函數 move_point(x, y, dx, dy)，回傳加上偏移量後的新座標 tuple。測試 move_point(5, 5, -1, 1)

<img width="346" height="135" alt="image" src="https://github.com/user-attachments/assets/5779e98e-9b69-46d3-a31e-3dc275ad9de0" />

Challenge 1.5 (絕對距離): 定義函數 distance(x1, x2)，回傳 abs(x1 - x2)。計算 2 與 9 的距離

<img width="318" height="155" alt="image" src="https://github.com/user-attachments/assets/993897e1-b7ed-4f20-b4df-63c63664c72e" />

Challenge 2.1 (單一邊界測試): 呼叫 is_valid_cell(0, 8) 與 is_valid_cell(9, 0) 並印出結果

<img width="450" height="174" alt="image" src="https://github.com/user-attachments/assets/c163619e-38cd-4bec-aa64-fccf5a879590" />

Challenge 2.2 (邊緣鄰居數): 呼叫 get_neighbors(0, 4) (位於最上方邊緣但不在角落)，印出它有幾個合法鄰居

<img width="551" height="375" alt="image" src="https://github.com/user-attachments/assets/48b53c0b-2132-4791-9454-9e8c6cbfa84e" />

 Challenge 2.3 (掃描結果格式化): 取得 get_neighbors(8, 8) 的結果，使用 for 迴圈將每個 Tuple 一行一行地印出來

<img width="308" height="237" alt="image" src="https://github.com/user-attachments/assets/0be8fab1-66a9-4f6a-a645-b68d6e0073ff" />

Challenge 2.4 (十字雷達修改): 複製 get_neighbors 的概念，但這次只檢查上下左右 (十字型)，不檢查斜角。測試 (4,4)

<img width="576" height="348" alt="image" src="https://github.com/user-attachments/assets/952ff0be-d3ad-4efb-8161-3c30f2f300b7" />

Challenge 2.5 (大範圍雷達): 複製 get_neighbors 的概念，將偏移量從 [-1, 0, 1] 擴大為 [-2, -1, 0, 1, 2] (5x5 範圍)。印出 (4,4) 會得到幾個合法鄰居

<img width="585" height="432" alt="image" src="https://github.com/user-attachments/assets/cb5f885d-a2e3-46f7-afc2-cad2ad4a17a0" />

## 自習心得

這次學習讓我更了解 Python 函數、Tuple、迴圈與座標的應用。透過尋找九宮格周圍的鄰居，學會判斷邊界範圍，也了解如何利用雙層迴圈檢查不同方向，讓我對程式邏輯更加熟悉。

## 角色轉換——思考如何教導初學者 (Think about how to teach young people): 試著思考：「如果我要把今天的實作講給弟弟妹妹聽，我該怎麼轉化這些概念？要用什麼生活化的例子或步驟來說明？」整理出你專屬的「教學思路」與「降維說明法」。

我的教學思路與降維說明法
一、我的教學思路
如果要教弟弟妹妹今天學習的 Python，我會用「九宮格踩地雷遊戲」當作生活例子，讓他們更容易理解。
1. 函數： 像一台機器，輸入座標後，就能幫我們計算鄰居的位置。
2. Tuple： 像地址一樣，用 (r, c) 表示每個格子的位置。
3. 迴圈： 像巡邏員，一格一格檢查周圍的位置。
4. 條件判斷： 像檢查門禁，確認座標有沒有超出地圖範圍。
5. 鄰居搜尋： 檢查上下左右及斜角，找出附近合法的格子。
二、我的降維說明法
我會用生活中的例子來解釋：
- get_neighbors：像找自己座位周圍的同學。
- for 迴圈：像一個一個點名。
- if 判斷：像檢查是否超出教室範圍。
- len()：像計算周圍總共有幾位同學。
- 5×5 範圍：就像把尋找範圍從附近一圈擴大成附近兩圈。
三、教學心得
我認為教初學者應該先從生活例子開始，再慢慢介紹程式語法。透過九宮格遊戲，可以讓抽象的座標、函數和迴圈變得簡單，也能訓練邏輯思考能力。
