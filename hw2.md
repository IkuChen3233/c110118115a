# 甘特圖
### Mermaid
mermaid
gantt
    title 甘特圖

    section 1
    研擬計畫           :a1, 2023-01-01, 1d
    section 2
    任務分配      :a2, after a1  , 4d
    section 3
    取得硬體      :a3, after a1  , 17d
    section 4
    程式開發      :a4, after a2  , 70d
    section 5
    安裝硬體      :a5, after a3  , 10d
    section 6
    程式測試      :a6, after a4  , 30d
    section 7
    撰寫使用手冊      :a7, after a5  , 25d
    section 8
    轉換檔案      :a8, after a5  , 20d
    section 9
    系統測試      :a9, after a6  , 25d
    section 10
    使用者訓練      :a10, after a7 and a8  , 20d
    section 11
    使用者測試      :a11, after a9 and a10  , 25d
