# 🌀 Virtual Fidget Spinner

A modern and interactive **Virtual Fidget Spinner** built using **HTML, JavaScript, and Tailwind CSS**. Designed with a sleek neon-green-on-black aesthetic, this web application simulates the satisfying spinning motion of a real fidget spinner directly in your browser.

---

# ✨ Features

### 🌀 Realistic Spinner Animation

* Smooth rotational motion
* Momentum-based spinning
* Friction simulation for gradual slowdown

### 🎯 Interactive Controls

* Click the **"Spin Me!"** button to spin the fidget spinner
* Supports mouse and touch interactions

### 📱 Mobile Friendly

* Optimized for smartphones and tablets
* Touch gesture support
* Responsive design

### 🌟 Neon Theme

* Neon green glow effects
* Deep black background
* Modern minimalist design

### ⚡ Smooth Performance

* Powered by `requestAnimationFrame()`
* Efficient browser rendering
* Fluid animations across devices

---

# 🛠️ Technologies Used

| Technology       | Purpose                        |
| ---------------- | ------------------------------ |
| HTML5            | Structure                      |
| JavaScript (ES6) | Spinner Physics & Interactions |
| Tailwind CSS     | Styling & Layout               |
| CSS3             | Custom Effects & Animations    |

---

# 📂 Project Structure

```text
virtual-fidget-spinner/
│
├── index.html
├── image-SPINNER.png
└── README.md
```

---

# 🚀 How to Run

## Method 1: Direct Launch

1. Download the project files.
2. Ensure `image-SPINNER.png` is in the same folder as `index.html`.
3. Open `index.html` in your web browser.

No installation or setup is required.

---

# 🎮 How to Use

### Using the Spin Button

1. Open the application.
2. Click the **Spin Me!** button.
3. Watch the spinner rotate and gradually slow down.

### Touch Devices

* Tap and interact with the spinner on mobile devices.
* Optimized for touch input.

---

# ⚙️ How It Works

The spinner uses:

### Velocity System

```javascript
velocity += amount;
```

Each interaction increases rotational velocity.

### Friction Simulation

```javascript
velocity *= friction;
```

The spinner gradually loses speed over time, mimicking real-world physics.

### Animation Loop

```javascript
requestAnimationFrame(animate);
```

Provides smooth and efficient animation rendering.

---

# 🎨 Design Highlights

### Color Scheme

| Element      | Color                |
| ------------ | -------------------- |
| Background   | Deep Black (#000000) |
| Neon Text    | Neon Green (#39ff14) |
| Button       | Emerald Green        |
| Glow Effects | Neon Green Shadow    |

### Visual Features

* Glowing neon button
* Clean spinner display
* Minimalist user interface
* Modern cyber-style appearance

---

# 📱 Browser Compatibility

Tested and works on:

* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Opera
* Brave
* Mobile Browsers

---

# 💻 Performance Features

* Lightweight project
* No external JavaScript frameworks
* Fast loading time
* Optimized for desktop and mobile devices

---

# 👨‍💻 Author

**Soumyadeep Basu**

Crafted with ❤️ using HTML, JavaScript, and Tailwind CSS.

---

# 📄 License

This project is open-source and available under the MIT License.

You are free to use, modify, and distribute it for educational and personal purposes.

---


