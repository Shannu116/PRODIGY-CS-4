This is a **basic keylogger** tool built using Python and the `pynput` library. It is intended **strictly for educational and ethical use**, such as learning how input devices interact with software, or for authorized monitoring within legal and institutional boundaries.

> ⚠️ **Disclaimer:** This tool must **not** be used for unauthorized surveillance or data collection. Misuse can lead to serious legal consequences. Always ensure proper **consent** and **compliance with applicable laws and organizational policies**.

---

## 🎓 Purpose

As part of training and research in cybersecurity and software monitoring techniques, this tool helps to:

- Understand low-level keyboard input capturing.
- Learn how keylogging works as a concept.
- Demonstrate the need for robust system and endpoint security.
- Analyze potential threats in a controlled environment.

---

## 🧠 How It Works

- Captures each key press using `pynput.keyboard.Listener`.
- Saves key events into a local file `keylog.txt`.
- Logs are written every 5 seconds using a background timer.

---

## 🛠 Requirements

- Python 3.x
- `pynput` library

Install with:

```bash
pip install pynput
