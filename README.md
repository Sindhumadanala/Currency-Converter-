# Currency-Converter

**NAME** : MADANALA SINDHUJA

**COMPANY** : CODTECH IT SOLUTIONS PRIVATE LIMITED

**INTERN ID** :CITS762

**DOMAIN** : FRONTEND WEB DEVELOPMENT 

**INTERNSHIP PERIOD** : 17 MAY 2026 - 28 JUNE 2026 (6 WEEKS)

<h1 align='center'><a href="https://sindhumadanala.github.io/Currency-Converter-/">➡️ LIVE DEMO</a></h1>

**DESKTOP VIEW**

<img width="1917" height="902" alt="Image" src="https://github.com/user-attachments/assets/aa84bb3b-1248-4484-a1cf-2c3548d590e5" />


**MOBILE VIEW**

<p align='center'><img width="467" height="827" alt="Image" src="https://github.com/user-attachments/assets/a30cb8c4-058f-4e69-b209-fef5f97dad2e" />
</p>

## 📝 Description

This project is a clean, intuitive financial utility tool designed to help users instantly calculate exchange rates between 10 major global currencies. It features a striking, stylized interface built using custom CSS and Bootstrap, paired with asynchronous JavaScript to deliver seamless network performance.

## ✨ Key Features

* **Live Exchange Rates:** Integrates a reliable, open-access Exchange Rate API to pull the most up-to-date conversion metrics.
* **Fully Responsive UI:** Optimized across a dynamic range of screen dimensions, using explicit mobile breakpoints (`768px` and `480px`) for seamless mobile/tablet viewing.
* **Instant Validation:** Built-in client-side exception handling to prevent invalid inputs (empty or negative values) from making redundant API calls.

## 🛠️ Tech Stack

* **Markup:** HTML5
* **Styling:** CSS3, Bootstrap 5 (CDN), Google Fonts
* **Logic & API Handling:** Vanilla JavaScript (ES6+, Async/Await, Fetch API)

## 🚀 How It Works

1. The script automatically populates the `From` and `To` dropdown menus dynamically using a structured JavaScript object array.
2. When the user hits **Convert**, an asynchronous request (`fetch`) is dispatched to the endpoint based on the selected base currency.
3. The response JSON object parsing isolates the targeted target currency multiplier, computes the converted value, and updates the DOM immediately without needing a full page reload.
