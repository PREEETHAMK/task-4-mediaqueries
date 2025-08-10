# task-4-mediaquerie

## 📝 About the Task
This project is part of my internship assignments.  
The goal was simple: take an existing landing page (built for desktop only) and make it look great on **any screen size**.  
I achieved this by applying **CSS media queries** and making adjustments to the layout, fonts, and navigation for mobile and tablet users.

---

## ⚙️ Technologies Used
- HTML  
- CSS  
- Media Queries  

---

## 🎯 What I Did
- Created a flexible layout that adapts to smaller devices
- Improved navigation for mobile screens
- Adjusted font sizes and element spacing
- Added hover effects for better interactivity on desktop
- Tested the page on multiple screen widths

---

## 📂 Project Files
├── index.html # Landing page structure
├── style.css # Styling + media queries
└── README.md # Documentation


---

## 📱 Responsive Adjustments
Some changes made for mobile:
- Navigation menu stacks vertically
- Text and buttons scale for better readability
- Reduced padding/margin for smaller screens
- Footer layout adjusts to fit narrow devices

Example:
```css
@media (max-width: 768px) {
  nav {
    flex-direction: column;
    gap: 8px;
  }
  
  .hero h2 {
    font-size: 24px;
  }
}
🚀 How to View

Download or clone the repository:

git clone https://github.com/username/task-4-responsive.git
Open index.html in any web browser.

