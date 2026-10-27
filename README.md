# 🚆 Smart Transit Kiosk System (EMTECH Project)

An automated commuter kiosk prototype developed in Python. Designed to streamline transit station operations in the Philippines by automating fare calculation, coin exchange/change processing, and route condition monitoring.

---

## 📌 Project Overview
Commuters in urban transit areas frequently experience long lines at ticket booths and coin exchange counters. This project simulates an all-in-one Smart Transit Kiosk that integrates:
* **Philippine LTFRB Fare Calculation:** Computes regular and discounted matrix fares based on distance and vehicle type.
* **Coin Exchange & Change Management:** Handles bill-to-coin conversions with configurable service fee rates.
* **Traffic & Flood Status Updates:** Displays real-time or simulated route conditions for commuter safety.

---

## 🛠️ Features

| Feature | Description |
| :--- | :--- |
| **LTFRB Fare Engine** | Calculates distance-based fares starting from a base fare (PHP 13.00 for the first 5 km) plus succeeding rates, with automatic 20% discounts for eligible commuters (Seniors, Students, PWDs). |
| **Cash Machine Module** | Tracks kiosk balance, processes exact change, and calculates net payouts after transaction fee deductions. |
| **Route Status Checker** | Reports current traffic congestion levels and flood/passability status along travel routes. |

---

## 🚀 How to Run the Project Locally

### Prerequisites
* **Python 3.10 or higher** installed on your system.

### Steps
1. **Clone or Download** this repository:
   ```bash
   git clone [https://github.com/ethel19/commuter_kiosk_emtech.git](https://github.com/ethel19/commuter_kiosk_emtech.git)
   cd commuter_kiosk_emtech
