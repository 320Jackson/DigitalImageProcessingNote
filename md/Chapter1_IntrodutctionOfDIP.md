# Digital Image Processing Chapter1.
---
## Define
- 什麼是影像（Image）？
    - 圖片、照片......
    - 視覺化資料（Visual data）
    - 通常是 2 維或 3 維（two-dimensional or three-dimensional）
- 什麼是數位影像（Digital image）？
    - 影像是離散（Discretized）的，定義在離散的網格上。
    - 亮度（Light intensity value）或灰階值（Gray value）的二維集合
    - 矩陣、二維函數
- 什麼是數位影像處理（Digital image processing）？
    - 增強圖片，使其更清晰。（Human interpretation）
    - 機器學習、自動影像處理

## Important step in typical image processing system
- 影像採集
- 離散化 / 數位化 -> 量化 -> 壓縮
    - 將資料轉為離散形式。
    - 壓縮增加傳輸及儲存效率。
- 影像增強 -> 影像還原
    - 提高影像品質（低對比度、模糊、雜訊）
- 影像分割
- 選擇特徵
    - 選取物件特徵。
- 影像表示
    - 為選取的物件特徵加入標籤。
- 影像解釋
    - 賦予已辨識的物件意義。

<img src="https://i.imgur.com/duOqCEc.png" />


## 