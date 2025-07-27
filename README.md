# Medical Supply Management & Counterfeit Drug Analysis (India)

## 🧠 Overview

This project implements an integrated **Medical Supply Management System** with a focus on addressing **drug shortages** and the **proliferation of counterfeit medicines** in India, especially during public health emergencies like COVID-19.

It combines **web-based inventory tracking** with **Markov Chain-based simulation** to forecast drug availability and detect vulnerabilities in the supply chain.

## 🔍 Key Features

- 📊 **Dynamic Dashboard**: Stock levels, supplier updates, and order tracking.
- 🔐 **User Authentication**: Flask-based login system via XAMPP (localhost).
- 🗃️ **Inventory & Supplier Management**: Add/update medical stock, batch tracking, expiry, and supplier logs.
- 📉 **Predictive Analytics**: Markov Chain model forecasts drug authenticity and availability using historical data.
- 📈 **Real-Time Visualization**: Chart.js integration for supply trend analysis.
- ⚠️ **Automated Alerts**: Low stock and potential counterfeit alerts for proactive decision-making.

## 🏗️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python), PHP
- **Database**: MySQL
- **Simulation & Analytics**: NumPy, Pandas, Matplotlib (Google Colab)
- **Visualization**: Chart.js
- **Localhost Server**: XAMPP

## 📦 System Modules

```mermaid
flowchart TD
    A[User Login] --> B[Dashboard]
    B --> C[Inventory Management]
    B --> D[Order Placement]
    B --> E[Supplier Management]
    B --> F[Analytics & Reports]
    C --> G[MySQL Database]
    D --> G
    E --> G
