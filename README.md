# 🛒 MyShopify Test Automation Framework

## 📌 Overview
This project is a **Test Automation Framework** built for the **MyShopify application** using **Selenium WebDriver**, **Java**, and **TestNG**.  

It automates common e-commerce workflows such as **login, product search, add-to-cart**, along with a **utility to detect broken links** on the homepage.  
The framework follows the **Page Object Model (POM)** for improved readability, maintainability, and reusability.  

---

## ⚙️ Technology Stack
- **Programming Language**: Java  
- **Automation Tool**: Selenium WebDriver  
- **Test Framework**: TestNG  
- **Build Tool**: Maven  
- **Version Control**: Git/GitHub  
- **Reporting**: TestNG Reports / Extent Reports (if configured)  

---

## 🧪 Test Cases Automated
### 🔐 Login  
Automates login to MyShopify using valid credentials.  

### 🔎 Product Search  
Searches for a product in MyShopify and validates that results are displayed correctly.  

### 🛒 Add to Cart  
Adds a product from the search results to the shopping cart and verifies its presence.  

### 🔗 Broken Links Check  
Identifies and reports broken links on the MyShopify homepage using HTTP response codes.  

---

## 📂 Project Structure

myshopify-automation
│── pom.xml # Maven dependencies
│── README.md # Project documentation
│
├── src
│ ├── main
│ │ └── java
│ │ └── pages # Page Object classes for MyShopify
│
└── testng.xml # TestNG Suite configuration

## 📊 Reporting
- **TestNG Report**: Automatically generated under the `test-output/` directory after execution.  
 
---

## 👤 Author
- **Name**: Vineeth Babu  
- **Role**: Senior SDET 
