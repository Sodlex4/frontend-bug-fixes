# 🐞 JavaScript Daily Bug Fixes

Welcome to my daily bug fixing journey!  
I'm practicing HTML, CSS, and JavaScript by fixing real-world frontend bugs using Chrome DevTools and logging each one.

---

## 🔧 Why I'm Doing This

As a growing frontend developer, debugging is a **core skill**.  
This project helps me:

- 🔍 Improve my problem-solving using DevTools
- 🧠 Understand how browsers interpret JS
- 💪 Build consistency and focus
- 💼 Prepare for real client work (freelance/Upwork/Reddit)

---

## 🛠️ Tools I Use

- [VS Code](https://code.visualstudio.com/)
- Chrome + DevTools
- Git + GitHub
- HTML | CSS | JavaScript (Vanilla)

---

## 📅 Daily Fixes Log

| Day | Bug | Status | File |
|-----|-----|--------|------|
| 1   | Button click not working (wrong selector) | ✅ Fixed | [`bug-fix-01-button-alert.html`](./bug-fix-01-button-alert.html) |
| 2   | Text not updating on button click (script runs before DOM ready) | ✅ Fixed | [`bug-fix-02-update-text.html`](./bug-fix-02-update-text.html) |
| 3   | Form doesn't log submission (missing `preventDefault`) | ✅ Fixed | [`bug-fix-03-silent-logic-error.html`](./bug-fix-03-silent-logic-error.html) |

---


## 💡 How I Solve Each Bug

1. 🔍 Observe errors in DevTools Console
2. 📖 Read the code and DOM structure
3. 🛠️ Fix the bug in code
4. ✅ Test again in browser
5. 📝 Log the fix in Markdown
6. 💾 Commit with Git

---

## 🧪 Example Bug Summary

```js
// ❌ Original Bug
document.querySelector("#button") // returns null

// ✅ Fix
document.getElementById("clickBtn") // returns <button>
