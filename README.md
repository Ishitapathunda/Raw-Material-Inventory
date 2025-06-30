# 🏭 Raw Material Inventory Management System

## 📋 Project Description

This is a **single-page web application** developed to manage the inventory of raw materials for a manufacturing unit. It supports full CRUD operations, real-time stock tracking, and report generation. The project utilizes **HTML**, **Bootstrap**, **jQuery**, and **JsonPowerDB** as the backend service.

It was created as part of an internship to gain hands-on experience in front-end development and server-less backend integration using JsonPowerDB.

---

## 🎥 Demo Video

🎬 [Click here to watch the demo](https://www.loom.com/share/7a68f0b6a6424a1ea669a5c9a0def7e1?sid=6373cbcc-3a74-4184-8080-8552d71cf322)

---

## 🚀 Live Demo

**Frontend Live Link**: [Click to View](https://ishitapathunda.github.io/Raw-Material-Inventory/)

> ⚠️ **Note**: This is a static frontend hosted on GitHub Pages.  
> Due to browser security policies, **API calls to JsonPowerDB (HTTP) are blocked** on this live site (served over HTTPS).

📌 To fully experience the app:
- **Download the project**
- **Run it locally** in a browser (like Chrome/Firefox)
- Make sure your browser allows HTTP requests from local files (or use Firefox for easier testing)

---

## 🔗 Important Links

- 🔸 [Home Page of JsonPowerDB](https://login2explore.com)
- 🔸 [Register to use JsonPowerDB](http://api.login2explore.com)
- 🔸 [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)

---

## ✅ Scope of Functionalities

- **Item Management**
  - Add/Edit/Delete items
  - Navigation using First/Next/Previous/Last buttons

- **Item Received (Inward)**
  - Add inward stock
  - Auto-update `ItemsReceived` in item record

- **Item Issue (Outward)**
  - Issue stock after stock check
  - Update `ItemsIssued` in item record

- **Item Report**
  - View current stock
  - Filter using Item ID range

---

## 📸 Illustrations

![Screenshot 2025-06-29 122222](https://github.com/user-attachments/assets/9ea57f23-1b27-4cf8-b7dc-4d8fffdcabcc)
> Welcome screen with menu

![Screenshot 2025-06-29 122245](https://github.com/user-attachments/assets/a90ffdd7-b99e-4b91-998a-dfe75b726683)
> Item CRUD operations

![Screenshot 2025-06-29 122310](https://github.com/user-attachments/assets/76a883a3-49f2-4a28-8cc7-d4453f1c8f27)
> Report
---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3 / Bootstrap 5**
- **JavaScript / jQuery**
- **JsonPowerDB** (serverless backend)
- **AJAX API Integration**

---

🚀 How to Run This App
Follow these steps to run the Raw Material Inventory Management Web App locally:

1. Clone this repository

git clone https://github.com/Ishitapathunda/Raw-Material-Inventory.git
cd Raw-Material-Inventory

2. Open the project
You can open the project in any code editor (e.g., VS Code) or directly open the index.html file in your browser.

3. Register on JsonPowerDB
Go to: Register to use JsonPowerDB

Get your Connection Token (you will use it in the code if you want to replace the default one)

4. Update your token (Optional)
If you generated a new token:

Open <script> section in index.html

Replace the existing token value in:

const connToken = "your-new-token-here";
5. Done! 🎉
Now you can:

Add and manage items

Record item inward and outward transactions

View live stock reports
## 🚧 Project Status

✅ **Completed** – All core functionalities are implemented and working.

---

## 💡 Future Enhancements (Optional)

- Authentication & Role-Based Access
- Advanced filters in reports
- Export reports to CSV

---

## 📚 Sources / References

- [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)
- [Bootstrap Documentation](https://getbootstrap.com)
- [jQuery API](https://api.jquery.com)

---

## 📩 Contact

Feel free to reach out on [LinkedIn](https://linkedin.com/in/ishita-pathunda-8ab902215/) if you'd like to connect or discuss the project.

---
