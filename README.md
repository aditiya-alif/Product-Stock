<div align="center">

<img src="imgs/landing.jpg" width="250" alt="Logo Alzi Petshop">

# Alzi Petshop - Stock Management System

A simple and efficient web application for managing pet shop product inventory.  
Built using native PHP, this app separates roles between sellers and buyers, providing a functional interface to manage and display products to customers.

<p align="center">
  <img src="https://img.shields.io/badge/platform-Web-blue.svg" alt="Platform">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
</p>

</div>

---

## ✨ Main Features

- [x] **Product Management (Full CRUD):**
  - `[✓]` **Create:** Sellers can add new products along with details, prices, stock, and images.
  - `[✓]` **Read:** Displays an organized product catalog categorized for buyers.
  - `[✓]` **Update:** Edit existing product information, including images.
  - `[✓]` **Delete:** Remove products from the list.
- [x] **Role-Based Login System:**
  - `[✓]` **Seller:** Access to a dedicated dashboard for managing products and stock.
  - `[✓]` **Buyer:** Can browse products without needing to log in.
- [x] **Stock Management:** Each product includes a stock attribute visible to buyers, with a “Out of Stock” label when inventory reaches zero.
- [x] **Automatic Image Optimization:** Uploaded images are automatically converted to `.webp` format for faster web performance.
- [x] **Responsive Layout:** Interface adapts seamlessly across desktop and mobile devices.
- [x] **Third-Party Integrations:**
  - `[✓]` **Google Maps:** Displays the shop’s physical location to help customers find it easily.
  - `[✓]` **WhatsApp:** A “Contact” button on the product detail page directly opens a WhatsApp chat.

---

## 🛠️ Technologies Used

<div align="center">
    <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
</div>

---

## 🚀 Installation & Setup Guide

Follow these steps to run the project in your local environment.

### **1. Prerequisites**

Make sure you have the following software installed:

- **Local Web Server:** [XAMPP](https://www.apachefriends.org/index.html) or WAMP.
- **Web Browser:** Chrome, Firefox, or Edge.

### **2. Setup Steps**

1.  **Clone the Repository**  
    Open the terminal and run the following command:

    ```bash
    git clone https://github.com/aditiya-alif/Product-Stock.git
    ```

2.  **Move the Project Folder**  
    Move the cloned project folder into the `htdocs` directory (for XAMPP) or `www` (for WAMP).

3.  **Database Setup**
    - Open phpMyAdmin (`http://localhost/phpmyadmin`).
    - Create a new database named `alzipetshop`.
    - Select the database, then go to the **"Import"** tab.
    - Upload the `alzipetshop.sql` file located in the project’s root directory.

4.  **php.ini Setup**
    - Open XAMPP.
    - Open `php.ini` by clicking the Apache config.
    - Search line `;extension=gd`, remove the semicolon ; in front of it, like this: `extension=gd`.
    - Save the file and restart Apache from XAMPP.

5.  **Run the Application**
    - Open your browser and go to `http://localhost/project-folder-name`.
    - The application is now ready to use!

---

## 📸 Application Preview

<details>
<summary>Click to view screenshots</summary>
<br>
<table>
  <tr>
    <td><center>Home Page (Product Catalog)</center></td>
  </tr>
  <tr>
    <td><center><img src="preview/dProduct.png" width="80%" alt="Home Page"></center></td>
  </tr>
  <tr>
    <td><center>Product Detail Page</center></td>
  </tr>
  <tr>
    <td><center><img src="preview/home.png" width="80%" alt="Product Detail"></center></td>
  </tr>
</table>
</details>

---

## 📁 Project Structure

The folder structure is designed to separate assets, backend logic, and interface pages.


```
.
├── css/ # Custom CSS and Bootstrap styling files
├── font/ # Fonts used in the project
├── imgs/ # Image assets (products, slides, icons)
├── js/ # JavaScript scripts
├── login/ # Login, register, and logout pages & logic
├── php/ # Backend PHP scripts (DB connection, form processing)
├── script/ # Additional JavaScript scripts
├── alzipetshop.sql # MySQL database dump file
├── index.php # Main page for buyers (catalog)
├── index_p.php # Main page for sellers (dashboard)
├── produk.php # Product detail page
├── tambah.php # Form for adding new products
├── edit.php # Form for editing existing products
└── README.md # The file you are reading
```

---

## ⚖️ License

Distributed under the MIT License.  See [LICENSE](LICENSE) for more details.
