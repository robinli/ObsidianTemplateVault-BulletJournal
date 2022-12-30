---
type: Journal
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
---
[[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(-1).format("YYYY")%>-W<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(-1).format("ww")%>]] <== This Week ==> [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(7).format("YYYY")%>-W<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(7).format("ww")%>]]

![[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(0).format("YYYY")%>-M<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(0).format("MM")%>##本月計畫]]

## 本週計畫
- 

## Days
- [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(0).format("YYYY-MM-DD")%>]]
- [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(1).format("YYYY-MM-DD")%>]]
- [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(2).format("YYYY-MM-DD")%>]]
- [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(3).format("YYYY-MM-DD")%>]]
- [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(4).format("YYYY-MM-DD")%>]]
- [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(5).format("YYYY-MM-DD")%>]]
- [[<%moment().year(tp.file.title.split("-W")[0]).week(tp.file.title.split("-W")[1]).startOf('week').day(6).format("YYYY-MM-DD")%>]]