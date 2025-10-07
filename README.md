# 專題簡介(第九組)

## 組員
林杉泰、顏玉靜、廖村浩、湯又蓁

## 方向
資源回收AI辨識

## 動機
看到學校回收桶有很多人分類都亂丟，造成清潔人員的困擾

## 受眾
- 前端網頁：不擅長分類的學生  
- 後端數據分析：管理者、決策人員  

## 技術
- YOLO  
- Python  
- OpenCV  

## 目標
期望改善回收亂分的問題，減少清潔人員的工作量

## 甘特圖
![甘特圖](https://github.com/shan-tai/teamwork/blob/main/%E7%94%98%E7%89%B9%E5%9C%96.png)


```mermaid
gantt
    title 專案甘特圖（2025/10/1～2025/12/21）
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%d
    section 計畫階段
    研擬計畫               :a1, 2025-10-01, 5d
    文獻探討               :a2, after a1, 7d
    系統需求分析           :a3, after a2, 7d

    section 設計階段
    UI/UX介面設計          :a4, after a3, 8d
    資料集準備             :a5, after a3, 10d
    後端架構建置           :a8, after a3, 10d
    系統功能與資料庫設計   :a9, after a8, 12d

    section 開發與測試
    模型建立與測試         :a6, after a5, 12d
    API開發與資料串接       :a7, after a6, 10d
    系統整合與測試         :a10, after a7 a9, 10d
    系統優化及更改         :a11, after a10, 10d

    section 文件與驗收
    撰寫使用手冊           :a12, after a10, 7d
    最終驗收與簡報         :a13, after a11 a12, 11d

```

```mermaid
graph TD
    A[1 研擬計畫] --> B[2 文獻探討]
    B --> C[3 系統需求分析]
    C --> D[4 UI/UX介面設計]
    C --> E[5 資料集準備]
    C --> H[8 後端架構建置]
    E --> F[6 模型建立與測試]
    F --> G[7 API開發與資料串接]
    H --> I[9 系統功能與資料庫設計]
    G --> J[10 系統整合與測試]
    I --> J
    J --> K[11 系統優化及更改]
    J --> L[12 撰寫使用手冊]
    K --> M[13 最終驗收與簡報]
    L --> M

```
