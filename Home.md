---
tags: home
---
# 🏠 Product Development Hub

## 🚀 Active Spaces
```dataview
LIST
FROM "Spaces"
WHERE status != "archived"
```
## 📅 Quick Access

- [[Daily Note|Today]]
    
- [[Encounters/Inbox|Quick Capture]]
    
- [[Atlas/Product MOC|Product Overview]]
    

## 🗺️ Atlas Maps

- [[Atlas/Product MOC]]
    
- [[Atlas/Technical MOC]]
    
- [[Atlas/Customers MOC]]

## ⚡ Recent Activity

```dataview
TABLE file.mtime as "Modified" FROM "" SORT file.mtime DESC LIMIT 10
```
