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
    title 蔬菜辨識系統專題 甘特圖 (2025/10/6 - 2025/12/21)
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%d

    section 規劃階段
    研擬計畫               :a1, 2025-10-06, 5d
    文獻探討               :a2, after a1, 5d
    系統需求分析           :a3, after a2, 5d

    section 設計階段
    UI/UX介面設計          :b1, after a3, 7d
    資料集準備             :b2, 2025-10-16, 10d

    section 開發階段
    模型建立與測試         :c1, after b2, 14d
    API開發與資料串接      :c2, after c1, 10d
    後端架構建置           :c3, after c1, 8d
    系統功能資料庫設計     :c4, after c2, 8d

    section 測試與整合階段
    系統整合與測試         :d1, after c4, 10d
    系統優化及更改         :d2, after d1, 7d

    section 文件與驗收階段
    撰寫使用手冊           :e1, after d1, 5d
    最終驗收與簡報         :e2, after d2, 7d

```
