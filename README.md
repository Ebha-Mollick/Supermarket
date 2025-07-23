# 🛒 Super Market Billing System (C++)

A simple command-line Super Market Billing System built using C++.  
This project allows users to manage inventory and perform billing operations with ease.

## 📌 Features

- Add items to inventory
- View current inventory
- Clear the inventory
- Generate bills by selecting items and quantities
- Automatically deduct quantities after billing

## 💡 How It Works

The system uses a class-based structure:
- `Item` class stores the name, rate, and quantity of each item.
- `BillSystem` class manages inventory and billing operations.
- A simple menu-driven interface allows the user to interact with the system.

## 🚀 Getting Started

### Prerequisites
- A C++ compiler like `g++`
- Terminal or Command Prompt

### Compilation

```bash
g++ -o billing_system main.cpp

