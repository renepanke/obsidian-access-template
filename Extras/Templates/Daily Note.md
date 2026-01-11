---
create: <%tp.date.now("YYYY-MM-DD") %>
tags:
  - daily
---
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

 [[<% moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY-MM-DD') %> |← Yesterday]] | [[Home|🏠]] | [[<% moment(tp.file.title, 'YYYY-MM-DD').add(1,'d').format('YYYY-MM-DD') %> |Tomorrow →]] 

## 🎯 Focus


## 📝 Notes


## 🤝 Meetings


## 📊 Created Today 

```dataview 
LIST WHERE file.cday = date(<% tp.file.title %>)
```