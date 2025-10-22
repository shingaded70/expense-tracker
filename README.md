cat > README.md << 'EOF'
# 📊 Personal Expense Tracker

A lightweight, offline-first expense tracker built with **Python Flask** and **SQLite** — designed to run **100% on Android via Termux**.

## 💡 Real-Life Problem Solved
- No need for internet or cloud apps
- Track daily spending without subscriptions
- Full control of your data

## 📱 How to Run (on Android with Termux)
1. Install Termux from F-Droid (recommended)
2. Run:
   ```bash
   pkg install python git
   pip install Flask
   git clone https://github.com/Shingade70/expense-tracker.git
   cd expense-tracker
   python app.py
