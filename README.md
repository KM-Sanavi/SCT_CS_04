# 📝 Typing Recorder (Safe Keystroke Logger for GUI Only)

This project is a **safe, local typing recorder** built using Python’s **Tkinter GUI**.  
It records keystrokes **only inside the application window** and **only while recording is enabled**.

✔️ Useful for typing practice  
✔️ Input debugging  
✔️ Accessibility testing  
❌ Does NOT record system-wide/global keystrokes  
❌ NOT a harmful keylogger  

---

## 📌 Features

- GUI built with Tkinter  
- Records timestamp, keysym, and printable characters  
- Displays logs in a TreeView table  
- Save logs to text file  
- Start/Stop recording buttons  
- Records events **only when the app is focused**  
- Clean, safe, educational purpose

---

## 🛠️ Requirements

- Python 3.x  
- Tkinter (pre-installed with Python)

No additional libraries needed.

---

## ▶️ How to Run

```bash
python typing_recorder.py
