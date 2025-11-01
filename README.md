This project is a **responsive sidebar navigation menu** built using **HTML and CSS only**, with Font Awesome icons and Google Fonts integration.  
The sidebar slides in and out smoothly using a simple checkbox toggle trick — no JavaScript needed!

---

## 📋 Features

- 🧭 Sliding sidebar navigation  
- 🎨 Transparent glass-like UI with shadow effects  
- 💡 Smooth transition animations  
- 📱 Fully responsive layout  
- 🔠 Google Fonts integration (`Poppins`)  
- 🌐 Font Awesome social media icons  
- ⚡ Toggle using hamburger (`☰`) and close (`×`) icons

---

## 🛠️ Technologies Used

- **HTML5**  
- **CSS3**  
- **Font Awesome 6.4.0** (for icons)  
- **Google Fonts** (Poppins)

---

## 📁 Project Structure

project-folder/
│
├── index.html # Main HTML file
├── mp photo.jpg # Background image used in the design
└── README.md # Project documentation

## ⚙️ How It Works

- A hidden checkbox (`#check`) is used as a toggle switch.
- When checked, the sidebar slides in from the left (`left: 0`).
- When unchecked, it hides again (`left: -300px`).
- CSS transitions and sibling selectors (`~`) handle the animations and visibility.

---

## 🧩 Key CSS Concepts Used

- `position: fixed` for sidebar placement  
- `transition: all 0.3s linear` for smooth animation  
- `:checked` pseudo-class for toggle functionality  
- `rgba()` for transparent overlay  
- `box-shadow` for subtle depth effect  
- `hover` effects on icons and menu items

---

## 🖼️ Preview

When the user clicks the **hamburger icon (☰)**, the sidebar appears with navigation links and social media icons.  
Click the **close icon (×)** to hide it again.

---

## 🚀 How to Run

1. Clone or download this repository.  
2. Place your background image (`mp photo.jpg`) in the same folder.  
3. Open `index.html` in your web browser.



## 💡 Customization Tips

- Change the **background image** by replacing `mp photo.jpg`.
- Modify menu links or icons in the `<ul>` inside `.menu`.
- Adjust sidebar width (`300px`) and colors to match your theme.
- Add animations or JavaScript for extra interactivity.

---

## 📜 License

This project is open-source and free to use for learning or personal projects.  
Feel free to modify and enhance it as you like!

---

## 👨‍💻 Author

**PRUTHVIKA SH**
📧 pruthvihuchcheshwarmath@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/pruthvika-sh-316964317?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BMfJjKw8dRL%2Bs%2BUHFjbe%2FCQ%3D%3D) | [GitHub](https://github.com/Pruthvish77)
