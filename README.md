🍔 FoodExpress — Console-Based Food Delivery System

A feature-rich, console-based Food Delivery Management System built in C++ using Object-Oriented Programming, File Handling, and real-world business logic.


📌 Project Overview
FoodExpress simulates a complete online food ordering platform with separate portals for Customers and Admins. The system handles everything from browsing the menu and placing orders to wallet payments, promo code discounts, automatic rider assignment, and detailed business reports — all through a clean console interface.

✨ Features
👤 Customer Panel
FeatureDescription📋 View MenuBrowse all available food items with prices🔍 Search FoodSearch items by name🛒 Place OrderAdd items and confirm orders💰 Wallet SystemRecharge wallet and pay via balance🎟️ Promo CodesApply discount codes at checkout📦 Order TrackingReal-time order status updates❌ Cancel OrderCancel a pending order⭐ Feedback & RatingsRate your experience after delivery
🛠️ Admin Panel
FeatureDescription📂 View All OrdersSee complete order history🔄 Update Order StatusChange status (Pending → On the Way → Delivered)🍽️ Manage MenuToggle food item availability🏍️ View RidersSee assigned delivery riders📊 Sales AnalyticsSummary of revenue and order counts📝 Business ReportsGenerate and save business reports💬 Customer FeedbackView all ratings and comments
💳 Payment & Delivery

Cash on Delivery (COD)
Wallet-based Payment
Promo Code Validation & Auto Discount
GST / Tax Calculation
Automatic Rider Assignment
Estimated Delivery Time Display


🛠️ Technologies Used

Language: C++ (C++17)
Concepts: OOP, File Handling, STL (vectors, maps, strings)
Programming Style: Modular / Function-based Architecture
UI: Console-Based Interface


📁 Project Structure
Food-Delivery-System-CPP/
│
├── FoodExpress.cPP           # Main source code
├── orders.txt                # Stores all order records
├── feedback.txt              # Customer feedback & ratings
├── wallet.txt                # Wallet balances per user
├── riders.txt                # Delivery rider data
├── promocodes.txt            # Valid promo codes
├── business_report.txt       # Generated sales reports
└── Cpp PROJECT Report.pdf    # Full project documentation

🚀 How to Run
Prerequisites

A C++ compiler (g++ / MinGW / MSVC)

Compile & Run
bashg++ FoodExpress.cPP -o FoodExpress
./FoodExpress

Windows users: Use MinGW or compile via Visual Studio / Code::Blocks.


👥 Group Members
Name :Faizan Gul

📚 Course Information

Subject: Programming Fundamentals / OOP
Semester: 2026
Submission: University Lab Project


📄 License
This project is submitted as a university assignment. Feel free to use it for learning purposes.
