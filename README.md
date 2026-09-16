# 💕 Romantic Proposal Page

A beautiful, interactive proposal page with animations and a playful dodging button. Built with HTML5, CSS3, and vanilla JavaScript.

## 🎉 Features

- **Glassmorphism Design**: Modern frosted glass effect with animated gradient background
- **Interactive Buttons**: 
  - "YES!" button triggers a celebration
  - "No" button that dodges away when you hover over or click it
- **Smooth Animations**: 
  - Floating hearts in the background
  - Falling hearts during celebration
  - Pulsing celebration text
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Accessible**: 
  - ARIA labels and roles for screen readers
  - Keyboard navigation support
  - High contrast focus indicators
  - Semantic HTML

## 🚀 Quick Start

### View Live Preview
The page is live at: **[https://piyush086524-byte.github.io/romantic-proposal/](https://piyush086524-byte.github.io/romantic-proposal/)**

Simply open the link in your browser and enjoy! 💕

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/piyush086524-byte/romantic-proposal.git
   cd romantic-proposal
   ```

2. **Open in browser**
   - Double-click `index.html` in your file explorer, OR
   - Right-click → "Open with" → Select your browser, OR
   - Use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. **Visit** `http://localhost:8000` in your browser

## 📱 Customization

### Change the Name
Open `index.html` and find this line:
```html
<div class="name-tag">Hey Anjana... ✨</div>
```
Replace `Anjana` with your special person's name!

### Change the Signature
Find this line:
```html
by your well-wisher KRISHNA ❤️‍🩹
```
Replace with your name!

### Change Colors
Modify the background gradient in the CSS:
```css
background: linear-gradient(135deg, #ff4e50, #f9d423, #e35d5b);
```

### Change Celebration Message
Find this section and customize:
```html
<h2>Yay! ❤️ Anjana said YES! 🎉</h2>
<p>You've made Krishna the happiest person!</p>
```

## ♿ Accessibility

This page includes:
- ✅ ARIA labels for screen readers
- ✅ Keyboard navigation (Tab, Enter, Space)
- ✅ Focus indicators for keyboard users
- ✅ Semantic HTML elements
- ✅ Skip to content link
- ✅ High contrast colors
- ✅ Responsive text sizing

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with animations and glassmorphism
- **JavaScript (Vanilla)**: Interactive button behavior and animations

## 🎨 Browser Support

- Chrome/Chromium ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## 📝 Features Breakdown

### Button Dodging Logic
The "No" button intelligently dodges within the card boundaries when you try to click it. It won't escape the container!

### Celebration Screen
When "YES!" is clicked:
- Full-screen celebration overlay appears
- Falling hearts with various emojis (❤️, 💖, 💝, 💕, 💘)
- Pulsing celebration text
- Smooth transition animations

### Background Animation
Continuously floating hearts in the background add to the romantic atmosphere.

## 🤝 Contributing

Feel free to fork this project and customize it for your own special moment!

## 📄 License

This project is open source and available under the MIT License.

## 💡 Tips for Use

1. **Mobile Friendly**: Works great on phones - try it on your mobile device!
2. **Full Screen**: Press F11 for full-screen mode for maximum impact
3. **Share**: You can share the GitHub Pages link with anyone
4. **Personalize**: Customize colors, text, and messages to make it unique

## 🎯 Perfect For

- 💍 Asking someone to be your girlfriend/boyfriend
- 💒 Proposal moments
- 🎉 Anniversary celebrations
- 💑 Showing love and affection
- 🎁 Special occasions

---

**Made with ❤️ by Krishna**

Good luck with your special moment! 🍀✨