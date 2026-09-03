# 🚗 AutoPro — Vehicle Sales & Service Management System

A clean, fully functional **front-end demo** of a Vehicle Sales & Service Management System built with pure HTML, CSS, and JavaScript (no frameworks, no dependencies except Google Fonts).

## 🌐 Live Demo
> Open `index.html` in any web browser — no server required!

---

## ✨ Features

| Module | Description |
|--------|-------------|
| 📊 **Dashboard** | Overview stats — inventory count, sales, service bookings, bills |
| 🔍 **Search Vehicle** | Browse & filter vehicles by type and status; quick Buy / Service buttons |
| 🛒 **Purchase Vehicle** | Record vehicle sales with customer details, payment mode, and discount |
| 📅 **Book Service** | Schedule service jobs — general service, oil change, engine repair, etc. |
| 🔧 **Service Vehicle** | Track and update service job status (Booked → In Progress → Completed) |
| 🧾 **Generate Bill** | Create GST invoices for sales or service; print-ready invoice view |

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/vsss.git

# Open in browser
start vsss/index.html   # Windows
open vsss/index.html    # macOS
xdg-open vsss/index.html # Linux
```

No npm, no build steps — just open the HTML file!

---

## 🖼 Screenshots

> Dashboard with live stats, inventory table, and service overview.

---

## 📦 Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** — All logic without any framework
- **Google Fonts** — Inter typeface

---

## 📋 Sample Data

The app comes pre-loaded with **12 vehicles**:
- Maruti Suzuki Swift, Hyundai Creta, Tata Nexon, Honda City
- Toyota Fortuner, Mahindra Thar, Bajaj Pulsar 150
- Royal Enfield Classic 350, Kia Seltos, Volkswagen Polo
- Tata Tigor EV, Ashok Leyland Dost

---

## 🛠 Modules Walkthrough

### 1. Search Vehicle
- Filter by vehicle type (Sedan, SUV, Hatchback, Bike, Truck)
- Filter by status (Available / Sold)
- Quick **Buy** and **Book Service** buttons on each card

### 2. Purchase Vehicle
- Select from available inventory
- Enter customer details (name, phone, email)
- Choose payment mode (Cash, Card, Loan/EMI, Bank Transfer)
- Apply discount
- Confirm purchase → auto-marks vehicle as Sold

### 3. Book Service
- Enter customer and vehicle details
- Choose service type from dropdown
- Set service date and expected delivery date
- Add complaint/notes

### 4. Service Vehicle (Tracking)
- View all service jobs in a table
- Update status: Booked → In Progress → Completed
- Generate bill directly from completed service

### 5. Generate Bill (Invoice)
- Select from purchase or service records
- Apply GST (0%, 5%, 12%, 18%, 28%)
- Add discount
- Generate print-ready invoice with company letterhead

---

## 📄 License

MIT License — Free to use for demo and educational purposes.

---

> Built as a demo project for Vehicle Dealership Management.
