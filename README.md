# JavaScript Todo List

於六角學院舉辦的公益活動 - 2021 程式體驗營擔任助教

拿設計師製作的版型做的第五關主線任務 給學員當參考範例使用

## 部分代碼解析

全部都寫原生 JS

設置陣列 data 存放項目資料

通過 push 添加陣列中的物件

通過 `forEach` 方式處理資料

用 `querySelector` 獲取元素

用 `addEventListener` 監聽事件(都是 `click` 點擊事件)

用 `e.preventDefault();` 阻止預設行為

用 `trim()` 刪除字串中多餘的空格

在元素身上設置 `data-*` 並用 `getAttribute` 來獲取對應數據

刪除單個項目使用 `data.splice(i, 1);` 刪除對應的索引值項目

刪除已完成的項目使用新數組替換掉原本的數組內容

把資料渲染至畫面使用字符串拼接方式實現
