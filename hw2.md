```mermaid
gantt
    title A Gantt Diagram Example

    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m-%d

    section Planning
    研擬計畫           :a1, 2024-01-01, 15d
    任務分配           :a2, after a1, 10d
    取得硬體           :a3, after a2, 20d

    section Development
    程式開發           :a4, after a3, 60d
    安裝軟體           :a5, after a4, 20d

    section Testing
    程式測試           :a6, after a5, 30d
    撰寫使用手冊        :a7, after a6, 15d
    轉換檔案           :a8, after a7, 10d
    系統測試           :a9, after a8, 15d
    使用者訓練         :a10, after a9, 15d
    使用者測試         :a11, after a10, 20d

