# 📅 <% tp.date.now("dddd, MMMM Do YYYY") %>

[[<% tp.date.now("YYYY-MM-DD", -1) %>]] ← Yesterday | Tomorrow → [[<% tp.date.now("YYYY-MM-DD", 1) %>]]

---

## 🚀 Focus Today
- [ ] 

## 📌 Tasks
- [ ] 
- [ ] 

## 🧠 Quick Notes
- 

## 📊 Reflection
### ✅ Wins
- 

### ❌ Improvements
- 

### 📖 Learned
- 

---

## 🔁 Random Notes (Review)
<%*
const files = app.vault.getMarkdownFiles();
const random = files.sort(() => 0.5 - Math.random()).slice(0,5);
tR += random.map(f => `- [[${f.basename}]]`).join("\n");
%>