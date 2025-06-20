# 🏟️ Football Ticketing System – C++ Project

This is a console-based **Football Match Ticketing System** written in C++. It allows users to:
- Select from different football matches
- Choose ticket categories (Child, Adult, Senior Citizen, Disabilities)
- Upgrade seat classes (Single, Couple, VIP, Deluxe)
- Purchase additional items and food
- Receive discounts through memberships and card payments
- View detailed receipts
- Track total income and customer count

---

## 📌 Features

### 🎫 Ticket Booking
- Four football leagues:
  - AFC Champions League
  - Malaysian Super League
  - Premier League
  - M3 League
- Ticket categories with different prices:
  - Child
  - Adult
  - Senior Citizen
  - Disabilities

### 💺 Seat Class Upgrades
- **Single** – RM 0 (Default)
- **Couple** – RM 20
- **VIP** – RM 70
- **Deluxe** – RM 100

### 🛍️ Item Purchases
Users can purchase items such as:
- Whistle (RM 5.00)
- Scarf (RM 10.00)
- Mask (RM 12.00)
- T-Shirt (RM 13.50)

### 🍔 Food Menu
Food set options include:
- Set A – RM 19.90
- Set B – RM 16.70
- Set C – RM 15.35
- Set D – RM 22.00

> Note: Actual food prices charged differ slightly in code logic, e.g., Set A = RM 5.00 (hardcoded).

### 💳 Discounts and Payment
- **Membership**: 10% discount
- **Cashless (Card)**: Additional 4.5% discount
- **Cash**: Balance calculated and returned

---

## 🧾 Output
At the end of each transaction, the system generates a detailed receipt showing:
- Buyer details
- Ticket information
- Item and food purchases
- Total price before and after discounts
- Payment method and final amount
- Daily summary of customers and income

---

## 🚀 How to Run

1. Clone this repository or download the `groupProject.cpp` file.
2. Compile using a C++ compiler:
   ```bash
   g++ groupProject.cpp -o ticketing
