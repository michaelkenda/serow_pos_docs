# Installation & Setup

Welcome to Serow!  
This guide will help you get started with installing or accessing Serow for the first time.

---

## 1. Accessing Serow

For web-based application. You don’t need to install heavy software to use it.

- Open your browser (Chrome, Firefox, Safari, or Edge).
- Go to [https://serow.app](https://serow.app).
- Sign up for a new account or log in if you already have one.

---
## 1. Download the Latest Release

1. Visit [https://serow.app](https://serow.app).  
2. Navigate to the **Downloads** section.  
3. Choose the latest version of Serow for your platform:
   - **Windows (.exe)**
   - **macOS (.dmg)**
   - **Linux (.AppImage / .deb / .rpm)**

> 💡 Always download the latest stable release to ensure you have new features and security updates.

---

## 2. Creating an Account

1. Click **Sign Up** on the homepage.  
2. Provide your **business name**, **email address**, and **password**. 
3. select server
4. Verify your email by clicking the link sent to your inbox.  
5. Log in using your new credentials.

---

## 3. Initial Configuration

After logging in, set up your workspace:

- **Business details**: name, location, currency, tax settings.  
- **Inventory preferences**: categories, units of measurement, stock thresholds.  
- **Notification settings**: choose how you want to receive alerts (email, in-app, SMS).  

---

## 4. Adding Your First Inventory Item

1. Navigate to the **Inventory** section.  
2. Click **Add Item**.  
3. Enter details:
   - Item name  
   - SKU (optional but recommended)  
   - Quantity in stock  
   - Unit price  
   - Supplier (if applicable)  
4. Save the item.

---

## 5. Mobile App (Optional)

If Serow provides a mobile app:

- **Android**: Download from [Google Play Store](#)  
- **iOS**: Download from [Apple App Store](#)  
- Log in using your Serow account.

---

## 6. Self-Hosted (Advanced)

> ⚠️ *Only for enterprise customers who need on-premise installation.*  

Requirements:
- Docker + Docker Compose  
- PostgreSQL database  
- Minimum server specs: 2 CPU, 4GB RAM, 20GB disk  

Steps:
```bash
git clone https://github.com/serow/serow.git
cd serow
docker-compose up -d
