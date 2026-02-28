# Responsive Sidebar Navigation Menu

A modern and responsive sidebar navigation menu built using pure HTML and CSS. This project demonstrates how interactive UI components can be created without using JavaScript.

## 📌 Features
- Sidebar toggle using checkbox technique (No JavaScript)
- Smooth slide-in and slide-out animation
- Hover effects on menu items
- Font Awesome icons integration
- Social media icons section
- Clean and minimal UI design

## 🛠 Technologies Used
- HTML5
- CSS3
- Google Fonts
- Font Awesome

## 🧠 Key Concept
The sidebar visibility is controlled using a hidden checkbox and CSS sibling selectors:

```css
#check:checked ~ .sidebar_menu {
    left: 0;
}
