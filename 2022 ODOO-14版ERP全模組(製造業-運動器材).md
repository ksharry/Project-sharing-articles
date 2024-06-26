<table>
    <tr>
        <td>ODOO-14版ERP全模組(製造業-運動器材)</td>
    </tr>
</table>

## 客戶環境說明
  >  客戶由Odoo8升版到Odoo12，於2021年6月-9月啟動odoo12升版odoo14社群版，於2021年10月啟動odoo14的輔導，目的為導入成本模組的上線使用，此次與社群大神Jason合作，顧問進行輔導程序與流程梳理，Jason處理程式邏輯與版本差異，公司規模人數約在200-250人左右。

## 專案時程與目的
1. 專案時程:2021/10-2022/03
2. 專案上線:2022/01
3. 專案目的:
   + 導入成本模組上線
   + 重新梳理財務流程
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.1.1.png?raw=true)

## 上線模組與參數設定
1. 模組:銷售、採購、製造、庫存、MES、品質、專案、會計
2. 成本計價:移動平均成本(anglo saxon)
3. 庫存計價:自動
4. 多倉庫
5. 出貨:兩步
6. 製造:兩步
7. 機器手臂透過PLM與ODOO的MES整合，在與ODOO ERP整合

![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.10.png?raw=true)
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.1.png?raw=true)
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.2.png?raw=true)

8. 製造請求、生管下達計畫派工、採購轉料、採購請求
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.3.png?raw=true)
9. 品質檢驗
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.9.png?raw=true)
10. 一般事務性申請
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.4.png?raw=true)
11. 研發專案管理
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.11.png?raw=true)
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.12.png?raw=true)
12. 人工/製費由製造工單預估產生。
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.5.png?raw=true)
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.6.png?raw=true)
13. 固定資產模組使用
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.7.png?raw=true)
14. 部門與廠別損益表
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.8.png?raw=true)
15. 庫齡分析表
![Alt text](https://github.com/ksharry/Project-sharing-articles.md/blob/main/png/5.2.13.png?raw=true)

## 流程導入
1. 已製作SOP說明:
   + 銷售：10份流程文件
   + 採購：8份流程文件
   + 生產：13份流程文件
   + 庫存：7份流程文件
   + 財務：17份流程文件
2. 第三方模組安裝:
   + 原odoo12版本升版
   + 元植進銷存模組
   + 上線前26項A級需求
   + 上線後20項A級需求
   + 第二階段3項B級需求
4. 基本資料檢核與設定:
   + 顧問協助規劃產品類別與財務設定
   + Jason檢查整體參數與非財務模組與基本資料版本移轉

## 專案文件與導入成果
1. 專案文件:
   + 專案規畫書(甘特圖)
   + 細部行程表(日歷)
   + 個案需求清單
   + 基本資料檢核表
   + 標準作業流程表
   + 開帳流程文件
   + 結帳流程文件
   + 日常問題追蹤表
2. 導入成果:
   + 盤存制度調整為永續盤存制
   + 可單獨檢討調整庫存科目
   + 協助確認倉庫流程與使用情境
   + 由系統自動結算成本
   + 成本分析報表的檢討
   + 標準化結帳程序
   + 產出部門與廠別損益表

## 專案導入後心得
1. 客戶使用8年ODOO經驗，參觀客戶四間工廠在不同地點，機械手臂透過PLM與ODOO MES整合，在與ODOO ERP整合，顯示ODOO在整合的架構的便利性。
2. 因客戶有不同路線與倉庫，製造段增加了生管計料與採購單拋轉路線處理、增加了製造/採購請求工作、品質檢驗、一般事務性流程，增加了許多功能需求。
3. 此次有版本升級的經驗，過程中調整了許多項目，在短促的時間，增加了上線的風險。
4. 在百人以上公司，分工更加細緻，欄位紀錄與流程更加重要，此次調整了讓跨單位間的流程梳理與溝通方式。
5. 此次盤存制度改變，期望透過系統自動產生帳務資料，增加會計審查的時間，進而提升系統價值。
6. 客戶持續的優化，如何把ODOO調整更符合台灣中小企業使用，例如報表的呈現、單據的勾稽、媒體申報的使用、資金調撥
7. 上線駐廠資源的安排，Jason與Ching與大河能快速排除問題與A級客製需求，達到成功上線並完成財務結帳

