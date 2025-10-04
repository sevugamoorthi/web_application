# 🌐 Personal Portfolio Website

This project is a **responsive personal portfolio webpage** designed to showcase an individual's background, education, experiences, ambitions, and hobbies.  
It’s built using **HTML**, **CSS**, and **Bootstrap 4**, with a clean and elegant layout.

---

## 📁 Project Structure

```
📦 Santhos_Mobile_Web_Application
 ┣ 📜 index.html
 ┗ 📜 style.css
```

- **index.html** → Main webpage structure, navigation, and content sections.  
- **style.css** → Custom styles for typography, layout, and visuals.

---

## 🎨 Features

- 🏠 **Home Section** – Attractive landing screen with a "Know More" button.  
- 👨‍💼 **About Section** – Displays personal background and profile photo.  
- 👪 **Family Sections** – Includes Parents, Siblings, and Childhood memories.  
- 🏫 **College Section** – Educational background with visuals.  
- 🚗 **Car Love Section** – Highlights passion for automobiles.  
- 🎯 **Ambition & Dream Sections** – Describes career goals and life dreams.  
- 💼 **Work Experience Section** – Contains information about professional history.  
- 📞 **Contact Section** – Lists WhatsApp, Facebook, and Email details.  

---

## ⚙️ Technologies Used

- **HTML5**
- **CSS3**
- **Bootstrap 4.3.1**
- **JavaScript** (for dynamic page display)
- **Font Awesome Icons**
- **Google Fonts**

---

## 🧩 How It Works

Each section (e.g., About, Hobbies, College) is hidden by default and displayed dynamically when clicked.  
This behavior is managed using a simple JavaScript function:

```js
function display(sectionId) {
  document.querySelectorAll("div[id^='section']").forEach(sec => sec.style.display = "none");
  document.getElementById(sectionId).style.display = "block";
}
```

By default, the **Home Page** is shown first.

---

## 🖥️ How to Run Locally

1. **Download or Clone** this repository:
   ```bash
   git clone https://github.com/sevugamoorthi/web_application.git
   ```
2. Open the folder:
   ```bash
   cd web_application/Santhos_Mobile_Web_Application/
   ```
3. Open `index.html` in any web browser:
   ```bash
   open index.html
   ```
   or simply **double-click** the file.

---


## 👤 Author

**Sevugamoorthi**  
📧 [sevugamoorthi738@gmail.com](mailto:sevugamoorthi738@gmail.com)  

---

> ✨ A simple yet personal digital portfolio built with love and Bootstrap.
