# 🌐 Responsive Website Using CSS Media Queries

This project demonstrates how to convert a static, desktop-only webpage into a **responsive and mobile-friendly** layout using **CSS media queries**. The goal is to create a smooth user experience across various screen sizes — especially mobile devices.

---

## 📌 Objective

Convert an existing desktop HTML page into a mobile-responsive version using CSS media queries and modern design practices.

---

## 🛠️ Tools Used

- HTML5
- CSS3
- VS Code (or any code editor)
- Chrome DevTools (for responsive testing)

---

## 🚀 Features

- Responsive layout that adapts to different screen widths (especially below 768px)
- Flexbox-based structure for clean alignment
- Collapsible or stacked nav menu on small screens
- Responsive image scaling and text resizing
- Visually appealing, modern UI using gradients and shadows

---

## 📂 Project Structure

📁 project-folder/
│
├── index.html # Main HTML file
├── styles.css # External stylesheet with media queries
├── image.jpg # Sample image
└── README.md # This file


---

## 📱 Mobile Responsiveness

The CSS includes a media query for devices with a **max-width of 768px**, which:
- Stacks elements vertically
- Reduces font size for readability
- Scales images within containers
- Prevents overflow and horizontal scrolling

```css
@media (max-width: 768px) {
  /* Responsive rules go here */
}
