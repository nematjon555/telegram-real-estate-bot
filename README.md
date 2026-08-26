# 🏡 Telegram Bot for Real Estate Agencies & Realtors

An asynchronous, feature-rich Telegram bot built for real estate agencies, property brokers, and individual realtors. Designed to showcase categorized listings (residential & commercial) and capture targeted client inquiries directly into an Excel database.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat&logo=python)
![Aiogram](https://img.shields.io/badge/Aiogram-3.x-green?style=flat&logo=telegram)
![OpenPyXL](https://img.shields.io/badge/Database-Excel%20%2F%20OpenPyXL-brightgreen)

---

## 🔥 Key Features

* **Categorized Property Search:** Organized sub-menus for:
  * 🔑 Rent Residential (Apartments / Houses)
  * 🏬 Rent Commercial (Offices / Retail Spaces)
  * 🏡 Buy Residential
  * 🏢 Buy Commercial
* **Excel Database Integration:** Automatically loads property listings from `real_estate_catalog.xlsx` without requiring complex SQL databases.
* **Lead Generation (FSM):** Multi-step request collection (Client Name, Target Category, Preferences/Budget, Phone Number).
* **Automated Request Logging:** Saves client responses directly to `property_requests.xlsx`.
* **Instant Admin Alerts:** Automatically forwards new client inquiries to the head agent's Telegram account in real-time.
* **Office & Realtor Contact Details:** Integrated geolocation sharing and direct contact links.

---

## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **Framework:** Aiogram 3.x (Asyncio Telegram Bot API)
* **Data Management:** OpenPyXL (Excel `.xlsx` processing)
* **Environment:** Python-dotenv

---

## 🚀 Quick Start & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/nematjon555/telegram-real-estate-bot.git](https://github.com/nematjon555/telegram-real-estate-bot.git)
   cd telegram-real-estate-bot
