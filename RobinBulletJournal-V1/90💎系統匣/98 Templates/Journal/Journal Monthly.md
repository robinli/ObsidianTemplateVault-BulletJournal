---
type: Journal
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
---
[[<% moment(tp.file.title.split("-M")[0]+"-"+tp.file.title.split("-M")[1]+"-01").day(-10).format("YYYY") %>-M<% moment(tp.file.title.split("-M")[0]+"-"+tp.file.title.split("-M")[1]+"-01").day(-10).format("MM") %>]] <== This Month ==> [[<% moment(tp.file.title.split("-M")[0]+"-"+tp.file.title.split("-M")[1]+"-01").day(+45).format("YYYY") %>-M<% moment(tp.file.title.split("-M")[0]+"-"+tp.file.title.split("-M")[1]+"-01").day(+45).format("MM") %>]]
## 本月計畫

## 本月完成

## Reminder
![[<%tp.file.title.split("-M")[0]%>-FutureLog##<%tp.file.title.split("-M")[0]%>-<%tp.file.title.split("-M")[1]%> Future Log]]

## Weeks
- [[<% tp.file.title.split("-M")[0] %>-W<% moment([tp.file.title.split("-M")[0], tp.file.title.split("-M")[1]-1, 01]).format("ww") %>]]
- [[<% tp.file.title.split("-M")[0] %>-W<% moment([tp.file.title.split("-M")[0], tp.file.title.split("-M")[1]-1, 01]).day(8).format("ww") %>]]
- [[<% tp.file.title.split("-M")[0] %>-W<% moment([tp.file.title.split("-M")[0], tp.file.title.split("-M")[1]-1, 01]).day(15).format("ww") %>]]
- [[<% tp.file.title.split("-M")[0] %>-W<% moment([tp.file.title.split("-M")[0], tp.file.title.split("-M")[1]-1, 01]).day(22).format("ww") %>]]
- [[<% tp.file.title.split("-M")[0] %>-W<% moment([tp.file.title.split("-M")[0], tp.file.title.split("-M")[1]-1, 01]).day(29).format("ww") %>]]
<%* if (moment(tp.file.title.split("-M")[0]+"-"+tp.file.title.split("-M")[1]+"-01").day(29).format("ww") != moment(tp.file.title.split("-M")[0]+"-"+tp.file.title.split("-M")[1]+"-01").add(1, 'months').subtract(1, 'days').format("ww")) { 
%>- [[<% tp.file.title.split("-M")[0] %>-W<% moment(tp.file.title.split("-M")[0]+"-"+tp.file.title.split("-M")[1]+"-01").add(1, 'months').subtract(1, 'days').format("ww") %>]]
<%* } _%>