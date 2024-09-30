```mermaid
gantt
    title A Gantt Diagram Example

    section Planning
    研擬計畫     :a1, 2024-01-01, 1d
    任務分配     :after a1  , 4d
    取得硬體     :a2, after a1, 17d

    section Development
    程式開發      :a3, 2024-02-01, 70d
    安裝軟體      :a4, after a3, 10d

    section Testing
    程式測試     :a5, after a4, 30d
    撰寫使用手冊    :a6, after a5, 25d
    轉換檔案     :a7, after a6, 20d
    系統測試     :a8, after a7, 25d
    使用者訓練    :a9, after a7, 20d
    使用者測試    :a10, after a9, 25d
