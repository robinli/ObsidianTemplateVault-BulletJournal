---
type: Journal
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
---
<< [[<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>]] | [[<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-W<% moment(tp.file.title, "YYYY-MM-DD").add(-1,'days').week() %>]] | [[<% moment(tp.file.title,'YYYY-MM-DD').add(1,'days').format("YYYY-MM-DD") %>]] >>

![[<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-M<% moment(tp.file.title, "YYYY-MM-DD").format("MM") %>##本月計畫]]
![[<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-W<% moment(tp.file.title, "YYYY-MM-DD").format("ww") %>##本週計畫]]
![[<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>##未完成事項(<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("MM-DD") %>)]]

## 待辦工作
- 

## Daily Log 日誌
- 

## 未完成事項(<% moment(tp.file.title,'YYYY-MM-DD').format("MM-DD") %>)
- 