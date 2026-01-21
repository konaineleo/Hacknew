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

This architecture ensures:
- Real-time performance  
- Low false positives  
- Transparency and explainability  
- Easy extension for future AI models  

---

## 🤖 AI & NLP Design Approach

The project uses a **hybrid intelligence approach**:

### Rule-Based Logic
- Encodes known UX and dark pattern heuristics
- Ensures reliability and predictable behavior

### NLP-Inspired Semantic Analysis
- Focuses on *meaning*, not just button labels
- Detects emotional and psychological manipulation cues

### Explainability First
- Every detection includes a reason and context
- Avoids black-box predictions
- Builds user trust

This design reflects **responsible AI principles** rather than opaque automation.

---

## 🎨 User Experience Philosophy

The extension is designed to behave like a **digital safety assistant**, not a warning system.

UX principles:
- Inform without alarming  
- Explain without accusing  
- Respect user agency  

The goal is to help users **slow down, reflect, and decide consciously**.

---

## 🧪 Test & Demo Pages

The repository includes styled test pages to clearly demonstrate each pattern:

### `test.html` — Forced Cookie Consent
Simulates a cookie banner with only an “Accept” option.

**Expected detection:**  
- Forced Cookie Consent (High Risk)

---

### `test_guilt.html` — Guilt-Tripping Language
Demonstrates emotional manipulation through wording.

**Expected detection:**  
- Guilt Tripping (High Risk)

---

### `test_urgency.html` — Urgency & Obstruction
Simulates time pressure and lack of exit options.

**Expected detection:**  
- Urgency / Pressure  
- Obstruction / Hidden Exit  

These test pages make the system easy to evaluate and demo.

---

## 🌐 Real-World Behavior & Nuance

On real websites (e.g., news or subscription platforms), the extension may detect **medium-risk patterns** such as:

- Consent walls that block access until a choice is made  
- Persistent overlays that interrupt the primary user goal  

These detections are **intentional** and highlight UX friction rather than illegal behavior.

The extension presents **risk and explanation**, leaving final judgment to the user.

---

## 🏆 Why This Project Is Different

- Focuses on **understanding**, not just detection  
- Uses explainable logic instead of black-box AI  
- Handles real-world complexity and grey areas  
- Prioritizes ethical UX and user autonomy  
- Built as a realistic, usable MVP  

---

## 🚀 Future Scope

- Integration with LLM-based NLP models  
- Multilingual dark pattern detection  
- Visual UI analysis (button prominence, contrast, layout bias)  
- Aggregate dark pattern risk scoring  
- Compliance and auditing tools for organizations  

---

## 🏁 Hackathon Context

This project was developed as a **hackathon MVP**, with emphasis on:
- Real-world relevance  
- Working demonstrations  
- Clear explanations over overengineering  
- Ethical and responsible design choices  

---

## 🧑‍💻 How to Run the Extension

1. Clone the repository  
2. Open `chrome://extensions`  
3. Enable **Developer Mode**  
4. Click **Load unpacked**  
5. Select the project directory  
6. Open any webpage and click **Scan This Page**  

---

## 📸 Screenshots

Screenshots demonstrating real-time detection and test scenarios are available in the `/screenshots` directory.

---

## 📜 License

This project is released under the MIT License.

---

## 🔚 Final Note

**AI Dark Pattern Detector helps users recognize manipulation, understand risk, and regain control over consent decisions—before those decisions are made unconsciously.**

