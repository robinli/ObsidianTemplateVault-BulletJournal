---
type: Journal
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
---
<< [[<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>]] | [[<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-W<% moment(tp.file.title, "YYYY-MM-DD").add(-1,'days').format("ww") %>]] | [[<% moment(tp.file.title,'YYYY-MM-DD').add(1,'days').format("YYYY-MM-DD") %>]] >>
## Daily Log(<% moment(tp.file.title,'YYYY-MM-DD').format("MM-DD")%>)

## Routine
- [ ] Read Email

## Daily Review(<% moment(tp.file.title,'YYYY-MM-DD').format("MM-DD") %>)

## Reminder
![[<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>##Daily Review(<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("MM-DD") %>)]]
![[<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-W<% moment(tp.file.title, "YYYY-MM-DD").format("ww") %>##本週計畫]]
![[<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-M<% moment(tp.file.title, "YYYY-MM-DD").format("MM") %>##本月計畫]]
![[<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY")%>-FutureLog##<%moment(tp.file.title,'YYYY-MM-DD').format("YYYY-MM")%> Future Log]]