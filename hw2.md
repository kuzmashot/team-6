第6組:
| 任務 | 說明 | 需時(天) | 前置任務 |
|:-------------|:---------------:|-----:|:---------------:|
| 1 | 研擬計畫 | 2023-10-01 | 1d |
| 2 | 任務分配 | 4 | 4d |
| 3 | 取得硬體 | 17 | 17d |
| 4 | 程式開發 | 70 | 70d |
| 5 | 安裝軟體 | 10 | 25d |
| 6 | APP開發 | 30 | 20 |
| 7 | 撰寫使用者手冊 | 25 | 30 |
| 8 | 程式測試 | 20 | 10 |
| 9 | 撰寫使用者手冊 | 25 | 10 |
| 10 | 使用者訓練 | 20 | 15 |
| 11 | 使用者測試 | 25 | 10 |

```mermaid
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
    section 12
    成果發表      :a12, after a11  , 25d

```
