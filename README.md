**使用 Obsidian 儲存庫範本做子彈筆記工作流程**

# 安裝
## 安裝 Obsidian 
[官方連結](https://obsidian.md/download) 

## 下載範本
透過 Git 指令
```
git clone https://github.com/robinli/ObsidianTemplateVault-BulletJournal.git
```

直接[下載](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/archive/refs/heads/main.zip)


## 開啟 Obsidian


## 開啟儲存庫
左側功能列下方 ==開啟其他儲存庫== 

![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230104630.png?raw=true)


選擇儲存庫的目錄
檔案總管開啟目錄，按下選取
![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230104746.png?raw=true)

![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230104733.png?raw=true)

---

# 簡易版子彈筆記法
## 工作流程
![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230114023%20%E7%B0%A1%E6%98%93%E7%89%88%E5%AD%90%E5%BD%88%E7%AD%86%E8%A8%98%E6%B3%95%E6%B5%81%E7%A8%8B%E5%9C%96.png?raw=true)

## 檔案架構與關聯
- Monthly Review 月計畫
	- 上月未完成 : 手動輸入
	- 本月計畫 : 手動輸入

- Weekly Review 週計畫
	- 本週計畫 : 手動輸入，從月計畫複製本週執行的項目

- 日誌
	- 月計畫 : 透過連結自動顯示本月計畫	
	- 週計畫 : 透過連結自動顯示本週計畫
	- 未完成事項: 透過連結自動顯示前一天的未完成事項
	- Daily Log 日誌 : 手動輸入
	- 未完成事項(YY-MM) : 手動輸入，今天未完成的工作要順延到明天


## 建立月計畫
在目錄 10✅子彈日誌\13 Monthly 下新增筆記，
命名格式為 : 西元年-M月份
舉例 2023 年 1 月份，筆記名稱為 2023-M01

左側功能列的 ==Templater== -> 選擇 Monthly Review Template

![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230104525.png?raw=true)


## 建立週計畫
從月曆點擊 ==週次==

![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230102842.png?raw=true)

## 填寫日誌
新增日誌
- 左側功能列 -> ==開啟今天的每日筆記==
- 從月曆點擊日期

在 __Daily Log__ 區段裡填寫當天的筆記 。

遺留到明天要執行的移轉至 __Daily Review__ 區段。


## Key 撰寫體例
-  : 一般筆記，生活記錄，帳目

💊 : 計畫的任務，在未來誌, 月計畫, 週計畫中的工作

- [ ] : 待辦工作，在日誌中的工作

📅 : 事件

⭐ : 重要性 

➡️ : 延後一天

⬅️ : 轉移到上一層清單


## 子彈筆記撰寫要領
- Future Log 未來誌(年度記事)
	- 當得知未來發生的任務或行程，可以先填寫在未來誌裡。
	- 日後進行每月、每週計畫時可參考與引用。
	- 儲存目錄 : __14 Yearly__
	- Key 僅包括 : 💊 📅

- Monthly Log 月計畫
	- 每月1~2日進行月計畫，參考 Future Log 並回顧上個月計畫，轉移預計執行的任務至此區段。
	- 儲存目錄 : __13 Monthly__
	- Key 僅包括 : 💊 📅

- Weekly Log 週計畫
	- 每週日進行本週計畫，從月計畫轉移預計執行的任務至此區段。
	- 儲存目錄 : __12 Weekly__
	- Key 僅包括 : 💊 📅

- Daily Log日誌
	- Daily Log 日誌 : 手動輸入
	- Routine : 每天例行事項，當天沒做完不轉移至明天
	- Daily Review : 將 Daily Log 未完成的工作標示 ➡️ 並轉移過來此區段
	- Reminder : 透過連結自動顯示前一天的 Daily Review、本週計畫、本月計畫、未來誌
	- 儲存目錄 : __11 Daily__

---
