# AGENTS.md

## 🎯 Objective
This project is a **single-page web app** used in a children's birthday scavenger hunt.

It simulates a "secret code panel" with:
- input field
- success / error visual states
- sound effects
- animations

The goal is to keep the experience **simple, immersive, and reliable on mobile devices**.

---

## 🧱 Project Structure

- `index.html` → main and only application file
- No backend
- No build system
- No frameworks

All logic (HTML, CSS, JS) is contained in this single file.

---

## 🚫 Strict Constraints

When making changes, you MUST:

1. **NOT introduce new files** unless explicitly requested
2. **NOT introduce frameworks** (React, Vue, etc.)
3. **NOT add build tools** (Vite, Webpack, etc.)
4. **NOT refactor into multiple files**
5. **NOT change the overall UI structure drastically**
6. **NOT remove existing animations or sound behavior unless asked**

---

## ✅ Allowed Changes

You CAN:

- Improve UX (buttons, flows, small interactions)
- Add small features (e.g., counter, timer, attempts)
- Improve visual effects
- Improve sound handling
- Refactor small JS functions for clarity
- Fix bugs

---

## 🧠 Code Style Guidelines

- Keep everything **simple and readable**
- Prefer **vanilla JavaScript**
- Avoid overengineering
- Keep functions small
- Do not introduce complex abstractions

---

## ⚠️ Important Behaviors to Preserve

These behaviors are critical and must NOT break:

- Code validation flow
- Visual feedback (red = incorrect, green = correct)
- Full-screen overlay messages
- Sound playback on interaction
- Mobile compatibility

---

## 🧪 Testing Instructions

After making changes, ensure:

1. Page loads correctly
2. Entering incorrect code:
   - triggers red screen
   - plays sound
3. Entering correct code:
   - triggers green screen
   - plays victory sound
4. "Borrar" button clears input
5. Works on mobile screen sizes

---

## 🧩 Change Strategy

When implementing a change:

1. Make the **smallest possible modification**
2. Avoid touching unrelated code
3. Clearly state:
   - which part was changed
   - why
4. Prefer **incremental improvements**

---

## 🗣️ Output Expectations

When responding:

- Explain changes briefly
- Provide exact code changes
- Avoid unnecessary rewrites of the entire file unless required

---

## 🚀 Future Extensions (optional)

Possible features (only if requested):

- countdown timer
- limited attempts
- multi-step code input (per child)
- sound customization
- visual themes

---

## 🧱 Philosophy

This is a **fun, real-world tool for kids**, not a production system.

➡️ Simplicity > Perfection  
➡️ Reliability > Complexity  
➡️ Fun > Technical elegance
