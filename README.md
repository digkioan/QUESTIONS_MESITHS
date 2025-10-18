# 🧠 Exam Trainer — Insurance Broker Certification

A lightweight interactive web app to study and prepare for the **Insurance Broker Certification Exam**.
Supports structured study, 60-question simulations, and adaptive review of mistakes — all stored locally in your browser.

---

## 🚀 Features

### 🧩 Study Mode

* Browse all questions in order.
* Reveal correct answers anytime.
* Tracks:

  * Seen questions
  * Correct / wrong attempts
  * Answer views
* Updates real-time **progress coverage %**.

### 🧮 Simulation Mode (60 Random)

* Generates a random 60-question exam.
* Hides numbering and labels (α, β, γ, δ) for realism.
* Shuffles both question and answer order.
* Tracks time and shows:

  * Score & percentage
  * Total duration
  * Detailed list of **mistaken questions** with correct answers.

### 🔁 Adaptive Mistake Review

* Focuses only on questions answered **wrong more often than right**.
* Removes questions automatically once corrected.
* Includes quick search and jump navigation.

---

## 📊 Progress Tracking

* Study coverage (%)
* Total answer views
* Per-question stats (correct / wrong)
* Fully stored in browser `localStorage` (no login required).

---

## 💾 Data Import

Supports `.xlsx`, `.csv`, and `.json` question sets.
You can upload or paste JSON directly from the interface.

---

## ⚙️ Extras

* Export / import progress as JSON
* Reset progress anytime
* Offline use — no server needed
* Search or jump directly to any question

---

## 🧠 Tech Stack

* **Pure HTML, CSS, JavaScript**
* [SheetJS (XLSX)](https://sheetjs.com/) for Excel parsing
* Browser **LocalStorage API**
* Responsive dark UI

---

## 🏁 Usage

1. Open `index.html` in your browser.
2. Load your Excel or JSON file.
3. Choose a mode: Study, Simulation, or Mistake Review.
4. Train, track progress, and improve your accuracy.

---
