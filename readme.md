# 🔍 Live User Profile Viewer

A clean and interactive web app that displays user profile cards and lets you **filter them in real time** using a simple search input. Each card features a background image, a stylish blurred overlay, and a short bio.

---

## ✨ Features

- 📇 **Predefined user cards** with:
  - Profile image
  - Name
  - Aesthetic short bio

- 🔍 **Live search functionality**:
  - Filters user cards **as you type**
  - Matches based on the **start of the name**

- 🎨 **Stylish card layout**:
  - Background images with blurred overlays
  - Smooth UI using basic CSS and JavaScript

---

## 🛠️ Tech Stack

- **HTML5**  
- **CSS3**  
- **JavaScript (Vanilla)**  

No libraries or frameworks needed!

---

## 📁 Project Structure

```

/user-profile-viewer
│
├── index.html
├── style.css
├── index.js
├── README.md
````

---

## 🧪 How to Use

1. **Clone the repository**

```bash
git clone https://github.com/your-username/user-profile-viewer.git
````

2. **Open `index.html` in your browser**
   No setup required — works entirely in the browser.

---

## 💡 Example Users

Includes a small set of sample users with aesthetic bios and high-quality images, such as:

* Amisha Rathore – "silent chaos in a loud world 🌑🖤"
* Tanay Rawat – "don’t text, just vibe 🪩"

### User Cards Layout

![User Cards](images/user-cards.png)

### Live Search Filtering

![Live Search](images/live-search.png)

---

## 🔧 Customization

To add or update users, simply modify the `users` array in the `script.js` file:

```js
let users = [
  {
    name: "Your Name",
    pic: "your-image-url.jpg",
    bio: "your short, aesthetic bio",
  },
  // add more users here
];

