# MeGoVerse Lecture Tracker

A modern financial management and lecture tracking system built with Python and CustomTkinter.

![MeGoVerse](https://img.shields.io/badge/Developed%20by-MegoVerse-667eea)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![License](https://img.shields.io/badge/License-Proprietary-red)

## 🌐 About

**Developed by MegoVerse**  
Website: [megotech.tech](https://megotech.tech)

## ✨ Features

### 📊 Dashboard
- Financial summary cards (Income, Expenses, Profit)
- Quick overview of all metrics

### 🎓 Lectures Management
- Track lectures by academy
- Record hours, rates, and payment status
- Filter by academy, date, and payment status

### 💸 Expenses Tracking
- Categorize expenses
- Track spending over time

### 🏫 Academies Management
- Manage multiple academies
- Set default rates per academy

### 📈 Reports & Analytics
- Generate financial reports
- Filter by date range and academy
- Export to CSV and PDF

### 👥 User Management
- Role-based access control
- Multiple user accounts
- Password management

### 💼 Freelance Work
- **Companies**: Manage client companies
- **Projects**: Track projects with status
- **Work Sessions**: Log work hours and rates

## 🚀 Getting Started

### Prerequisites
- Python 3.10 or higher
- pip (Python package manager)

### Installation

1. Clone or download the project

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python run.py
```

### Default Login
- **Username**: admin
- **Password**: admin123

## 📦 Dependencies

- customtkinter - Modern UI framework
- tkcalendar - Calendar widget
- reportlab - PDF generation
- Pillow - Image processing

## 🎨 Theme

The application features a modern dark theme inspired by [megotech.tech](https://megotech.tech):

- Dark backgrounds with purple accents
- Responsive design
- Clean, modern UI components

## 📁 Project Structure

```
├── config/
│   └── settings.py       # App configuration
├── src/
│   ├── core/
│   │   ├── database.py   # SQLite operations
│   │   └── permissions.py # Role-based access
│   └── ui/
│       ├── theme.py      # UI theming
│       ├── components/   # Reusable components
│       └── views/        # Application views
├── assets/               # Images and icons
├── run.py               # Entry point
└── requirements.txt     # Dependencies
```

## 🔒 Security

- Passwords are hashed using SHA-256
- Role-based permission system
- Session management

## 📄 License

Proprietary software developed by MegoVerse.  
All rights reserved.

## 📞 Contact

- **Website**: [megotech.tech](https://megotech.tech)
- **Developer**: MegoVerse

---

© 2024 MegoVerse. All Rights Reserved.

