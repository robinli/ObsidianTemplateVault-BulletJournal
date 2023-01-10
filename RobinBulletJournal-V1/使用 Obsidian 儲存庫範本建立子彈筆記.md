# 前言
子彈筆記法最初設計以手帳方式記錄，我想保留幾項適用的原則，移植到數位筆記軟體上，選擇 Obsidian 來協助個人子彈筆記流程，目前採用四種筆記類型：未來誌、月計畫、周計畫、日誌。

透過 Obsidian 雙向連結的性，讓這四種筆記緊密連結，當填寫日誌時速查前一天轉移的工作，並檢視當週計畫、當月計畫與未來誌的內容。

Obsidian 另一項很不錯的體驗，每天第一次使用 Obsidian 會直接開啟當天的子彈筆記，不經過瀏覽或查找，即可開始輸入當天的 Daily Log。

# 安裝 Obsidian 與子彈筆記範本
## Step 1
進入 [Obsidian 官方網站](https://obsidian.md/download)  下載軟體後，直接安裝即可 。

## Step 2
下載 [子彈筆記範本](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/archive/refs/heads/main.zip) ，並解壓縮。
也可以透過 Git 指令取得範本檔案：

```
git clone https://github.com/robinli/ObsidianTemplateVault-BulletJournal.git
```


## Step 3 
第一次開啟 Obsidian 時，選擇 __開啟資料夾為儲存庫__，按下 ==開啟==。

![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230104630.png?raw=true)

檔案總管展開範本主目錄，按下 ==選取==。

![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230104746.png?raw=true)


由於這範本有使用第三方外掛，請按下 ==信任作者並啟用外掛程式== 。

![](https://github.com/robinli/ObsidianTemplateVault-BulletJournal/blob/main/RobinBulletJournal-V1/90%F0%9F%92%8E%E7%B3%BB%E7%B5%B1%E5%8C%A3/99%20Attachment/Pasted%20image%2020221230104733.png?raw=true)


# 子彈筆記操作說明

## 子彈筆記流程

從時間的範圍由大至小為 未來誌 (Futrue Log) -> 月計畫 -> 週計畫 -> 日誌。
這四類筆記有不同的格式，透過 Obsidian 範本的功能，可以自動帶入範本內容。

![upgit_20230110_1673343117.png](https://raw.githubusercontent.com/robinli/RobinObsidianAssets/main/2023/01/upgit_20230110_1673343117.png)



## 建立月計畫
在目錄 __10✅子彈日誌/13 Monthly__ 按 右鍵 新增筆記，
命名格式為 : 西元年-M月份
舉例 2023 年 1 月份，筆記名稱為 2023-M01

左側功能列的 ==Templater== -> 選擇 __Journal Monthly__


## 建立週計畫

從 Obsidian 右上方的月曆，點擊 週次 的數字，會自動開啟該週的週計畫，若檔案尚未建立，則會自動新增週計畫的筆記。

![upgit_20230110_1673343179.png](https://raw.githubusercontent.com/robinli/RobinObsidianAssets/main/2023/01/upgit_20230110_1673343179.png)


## 填寫日誌
以下兩種新增日誌的方式：
- 左側功能列 -> ==開啟今天的每日筆記==

![upgit_20230110_1673343308.png](https://raw.githubusercontent.com/robinli/RobinObsidianAssets/main/2023/01/upgit_20230110_1673343308.png)


- 從月曆點擊日期


## Key 撰寫體例
-  : 一般筆記，生活記錄，帳目

💊 : 計畫的任務，在未來誌, 月計畫, 週計畫中的工作

- [ ] : 待辦工作，在日誌中的工作

📅 : 事件

⭐ : 重要性 

➡️ : 延後一天

⬅️ : 轉移到上一層清單


## 子彈筆記撰寫原則
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
	- Daily Log 日誌 : 手動輸入。
	- Routine : 每天例行事項，當天沒做完 __不用__ 轉移至明天。
	- Daily Review : 將 Daily Log 未完成的工作標示 ➡️ 並轉移過來此區段。
	- Reminder : 透過連結自動顯示前一天的 Daily Review、本週計畫、本月計畫、未來誌。
	- 儲存目錄 : __11 Daily__


# 小結

以上是個人以 Obsidian 組合為子彈筆記的作法，初期希望 Obsidian 以核心功能出發，僅安裝四個外掛程式，包括 Calendar, DataView, Tasks, Templater，盡可能保留 Obsidian 原始風格與簡約設計，提供 Obsidian 初學者自行修改調整的空間，參考範本可減少學習摸索期。

有各式各樣筆記軟體可以搭建數位化的子彈筆記，沒有最好只有適合的，凡是能做到方便、無壓力、有效時間管理就是適合的解決方案，透過每天填寫日誌，工作轉移、回顧等操作，在不同時間、場景記錄筆記，漸進式調整為個人的 時間/人生 管理系統。