	---
id: <% tp.file.creation_date("YYYYMMDDHHmmss") %>
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
updated: <% tp.date.now("YYYY-MM-DD HH:mm") %>
tags: [note]
type: <% await tp.system.suggester(["idea","note","project","learning"], ["idea","note","project","learning"]) %>
status: <% await tp.system.suggester(["draft","active","completed"], ["draft","active","completed"]) %>
---

# <% tp.file.title %>

## 🧠 Summary
- 

## 📌 Key Points
- 

## 🔗 Related
- 

## ⚡ Actionables
- [ ] 

## 📚 References
- 

## 📝 Notes
- 