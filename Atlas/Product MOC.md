# 🗺️ Product Development Map

## 🚀 Active Spaces
```dataview
TABLE status, owner, started
FROM "Spaces"
WHERE status = "active"
```

## 📚 Key Knowledge

- [[Product Strategy Framework]]
    
- [[User Research Methods]]
    
- [[Prioritization Techniques]]

## 🔥 Recent (7 Days)

```dataview
TABLE file.mtime as "Modified" FROM "Spaces" OR "Cards" WHERE file.mtime >= date(today) - dur(7 days) SORT file.mtime DESC
```

Related: [[Technical MOC]] | [[Customers MOC]]