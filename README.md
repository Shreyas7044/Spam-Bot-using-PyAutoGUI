# Spam Bot using PyAutoGUI

## 📌 Overview
A spam bot is a program that automatically sends repeated messages to a target platform, chat, or application. Spamming refers to sending the same or similar messages continuously.

This project demonstrates how to build a simple spam bot using Python’s PyAutoGUI library, which allows automation of mouse movements and keyboard inputs to simulate human actions.

---

## ⚠️ Disclaimer
This project is strictly for **educational and learning purposes only**.  
Using automation tools to spam messages may violate the terms of service of messaging platforms. The author is not responsible for misuse.

---

## 🛠️ Prerequisites

- Python 3.x installed
- PyAutoGUI library

---

## ▶️ How to Run the Bot
- Open any chat application (WhatsApp Web, Notepad, Telegram Web, etc.)
- Click inside the message input box.
- Run the script: python main.py
- You have 2 seconds to place your cursor in the desired text field.
- The bot will start typing messages automatically at 31-second intervals.

---

## 🧠 How It Works
- pyautogui.typewrite() simulates typing text.
- pyautogui.press("enter") sends the message.
- time.sleep() controls delay between messages.
- Infinite while True loop ensures continuous execution.

---

## 🖼️ Screenshot
![Application Screenshot]()

---

## 🔧 Customization
- Change messages inside typewrite()
- Modify delay using time.sleep(seconds)
- Add or remove reminders as needed.
