# Giderim - Smart Personal Finance & Expense Analytics

Giderim is a mobile application built with Flutter and Dart for tracking personal expenses. It scans receipts with OCR, categorizes spending automatically and visualizes it on a dashboard. Built during my mobile application development internship.

---

## Application Showcase

<p align="center">
  <img src="giderim_dashboard_analytics.jpeg" width="300" alt="Dashboard Analytics" />
  <img src="giderim_expense_entry_ocr.jpeg" width="300" alt="OCR Expense Entry" />
</p>

---

## How It Works

* **Bottom-up OCR scanning:** A custom algorithm identifies the total amount by scanning receipt text from bottom to top, which avoids picking up unrelated numbers.
* **Month-end projection:** Estimates month-end spending from the current spending rate and previous months.
* **Merchant identification:** An ignore-list prevents technical receipt terms (for example "Mali Degeri Yoktur") from being read as merchant names.
* **Automatic categorization:** Assigns expenses to categories using merchant name patterns and keyword matching.

---

## Tech Stack

* **Framework:** Flutter and Dart for cross-platform mobile development
* **OCR:** Google ML Kit text recognition
* **Storage:** SQLite for local relational data, SharedPreferences for settings
* **Charts:** FL Chart

---

## Source Code

The source code is private. Screenshots use placeholder data. I'm happy to walk through the code on request.
