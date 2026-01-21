# 🛡️ AI Dark Pattern Detector

AI Dark Pattern Detector is a browser extension that helps users **identify, understand, and evaluate deceptive interface patterns** (dark patterns) in cookie banners, consent dialogs, and popups while browsing the web.

Instead of blocking websites or forcing decisions, the extension focuses on **awareness, explanation, and informed consent**, allowing users to understand *how* and *why* an interface may be influencing their choices.

---

## 📌 Motivation & Problem Background

Many modern websites rely on carefully designed interfaces that subtly guide users toward actions they may not fully intend—especially when it comes to privacy and consent.

These designs, commonly known as **dark patterns**, include tactics such as:
- Making “Accept” the easiest or only visible option  
- Hiding or de-emphasizing rejection choices  
- Using emotional or guilt-inducing language  
- Creating urgency so users act without reflection  
- Blocking access to content until consent is given  

While these patterns are often legal, they reduce **meaningful, informed consent** and exploit human psychology rather than user intent.

Most users are unaware when this happens.

---

## 💡 What This Project Does

AI Dark Pattern Detector is a **Chrome extension** that scans the current webpage and analyzes visible text to detect common manipulation patterns.

For each detected pattern, the extension:
- Identifies the **type of dark pattern**
- Explains **why it may influence user behavior**
- Assigns a **risk level** (Low / Medium / High)
- Suggests **what the user can do next**

The extension does **not**:
- Block content  
- Modify website behavior  
- Make legal claims  

Its role is to **inform, not enforce**.

---

## ✨ Core Features

- 🔍 Real-time scanning of the active webpage  
- 🍪 Forced cookie consent detection  
- 😔 Guilt-tripping language detection  
- ⏰ Urgency and pressure cue detection  
- 🚫 Obstruction or hidden exit detection  
- 🧠 Explainable, user-readable output  
- 📊 Risk-based classification instead of binary alerts  
- 🎨 Clean, calm, and user-friendly popup UI  

---

## 🧠 Dark Pattern Types Explained

### 1. Forced Cookie Consent
**What it looks like:**  
An “Accept all” option is clearly visible, while a reject option is hidden or missing.

**Why it matters:**  
Users feel there is only one valid choice, even when alternatives should exist.

**Risk level:** High

---

### 2. Guilt Tripping
**What it looks like:**  
Emotionally loaded language that frames privacy-respecting choices negatively.

Example:  
> “No thanks, I don’t care about my privacy”

**Why it matters:**  
It exploits emotion to override rational decision-making.

**Risk level:** High

---

### 3. Urgency / Pressure
**What it looks like:**  
Messages that rush the user with time or scarcity cues.

Examples:
- “Hurry! Offer ends soon”
- “Last chance”
- “Only a few spots left”

**Why it matters:**  
Rushed users are less likely to evaluate consent carefully.

**Risk level:** Medium

---

### 4. Obstruction / Hidden Exit
**What it looks like:**  
A clear primary action (e.g., “Continue” or “Accept”) exists, but cancel, close, or back options are unclear or absent.

**Why it matters:**  
Users may feel trapped into proceeding.

**Risk level:** Medium

---

## 🧩 How the Extension Works (Architecture)

