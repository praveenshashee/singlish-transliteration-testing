# Transliteration Accuracy Testing - Sinhala Chat Translator

## 📌 Project Overview
This project evaluates the accuracy of a live Sinhala chat transliteration system using automated testing with Playwright. The system converts Singlish (Romanized Sinhala) input into Sinhala script.

## 🎯 Objective
To test how accurately the application:
https://www.pixelssuite.com/chat-translator  
converts informal Singlish input into Sinhala output.

---

## 🧪 Test Design
- Total Test Cases: 50
- Covers all 24 Singlish input types:
  - Questions
  - Commands
  - Greetings
  - Requests
  - Responses
  - Repetition
  - Punctuation
  - Romanization variants
  - English mix
  - Digital terms, apps, abbreviations
  - Dates, currency, time
  - Slang, URLs, emojis, etc.

---

## ⚙️ Automation Tool
- Python 3.12
- Playwright
- OpenPyXL (Excel automation)

---

## 🚀 How to Run

```bash
pip install playwright openpyxl
playwright install
python test_automation.py --excel "Assignment 1 - Test cases.xlsx"