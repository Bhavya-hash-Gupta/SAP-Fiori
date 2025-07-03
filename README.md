# SAP-Fiori
# 🚗 SAPUI5 Car Dealer App

A customer-focused, responsive SAPUI5 application designed using Fiori principles. The **Car Dealer App** provides an intuitive interface for users to browse, filter, and review a catalog of cars with detailed views and offline-friendly data export features.

---

## ✨ Features at a Glance

- 🏷️ **Filterable Car List**: Users can filter cars by **Brand** and **Year**.
- ⛽ **Key Attributes**: Highlights fuel type, availability, and essential specs.
- 🔁 **Detailed View Navigation**: Seamless routing to individual car pages.
- 📤 **Excel Export**: Export full car listings for offline access or sharing.
- 📱 **Responsive UI**: Built with SAP Fiori design for cross-device compatibility.

---

## 🖼️ Screenshots

| Main List View | Car Detail View | Excel Export |
|----------------|-----------------|---------------|
| _Add screenshots here_ | _Add screenshots here_ | _Add screenshots here_ |

---

## 🛠️ Technical Overview

| Feature | Description |
|--------|-------------|
| **Framework** | SAPUI5 (OpenUI5-compatible) |
| **Architecture** | MVC with JSON Model |
| **Navigation** | Hash-based routing (`manifest.json`) |
| **Binding** | JSON Model Binding (one-way & two-way) |
| **Export** | Excel download using `Spreadsheet` utility |
| **Views** | Main List (Master), Car Details (Detail) |

---

## 🚀 Getting Started

### 📦 Prerequisites

- Node.js
- UI5 CLI (optional)
- SAP Business Application Studio or Visual Studio Code

### 🔧 Run Locally

```bash
git clone https://github.com/your-username/sapui5-car-dealer-app.git
cd sapui5-car-dealer-app
npm install
npm start
