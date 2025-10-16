# 🚁 Drone E-commerce | DJI Mavic 4 Pro Landing Page

### 🌐 Live Demo
[View Website](https://mkhaled-ahmed.github.io/Drone-E-commerce/#home)

---

## 📖 Overview

This project is a **responsive landing page** for the DJI Mavic 4 Pro drone, designed to showcase the product’s features, comparisons, customer reviews, and related accessories.  
The page focuses on **clean design**, **smooth scrolling**, and **fully responsive behavior** across all devices — without using JavaScript.

---

## 🧩 Sections

| Section | Description |
|----------|-------------|
| **Navbar** | Fixed navigation bar with smooth scrolling to each section |
| **Home / Hero** | Product image, pricing details, offers, and “Add to Cart” / “Wishlist” buttons |
| **Specifications / Comparison** | Comparison table between DJI Mavic 4 Pro and competitors |
| **Reviews** | Customer feedback, rating statistics, and recommendation rates |
| **Related Products** | Accessory cards to complement the main drone |
| **Footer** | Company info, links, social icons, and payment methods |

---

## 💻 Features

- ✅ Fully responsive layout (desktop, tablet, mobile)
- ✅ Pure HTML & CSS — no JavaScript required
- ✅ Sticky navbar with smooth scroll behavior
- ✅ Scroll offset handled via `scroll-padding-top`
- ✅ Comparison tables with highlight styling
- ✅ Product cards with hover effects
- ✅ Consistent color scheme using `#8E51FF` accent color

---

## 🧱 Technologies Used

- **HTML5**  
- **CSS3**  
- **Font Awesome** (for icons)  

---

## 📱 Responsive Behavior

- The design automatically adapts to screen sizes using **media queries**:
  - Navbar links are hidden on mobile (<768px)
  - `.sticky-review` becomes static (non-sticky) on smaller screens
  - Images and text stack vertically for better readability
  - Product cards adjust from 4-columns → 2-columns → 1-column
- Smooth scrolling is implemented via:
  ```css
  html {
    scroll-behavior: smooth;
    scroll-padding-top: 80px;
  }
