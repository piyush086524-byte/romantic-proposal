# 🎨 Customization Guide

This guide helps you personalize the proposal page to make it uniquely yours!

## Quick Changes

### 1. Change the Person's Name
**File:** `index.html`  
**Line:** Find `<div class="name-tag">Hey Anjana... ✨</div>`  
**Replace:** Change `Anjana` to your person's name

```html
<!-- Before -->
<div class="name-tag">Hey Anjana... ✨</div>

<!-- After -->
<div class="name-tag">Hey Sarah... ✨</div>
```

### 2. Change Your Name/Signature
**File:** `index.html`  
**Line:** Find `by your well-wisher KRISHNA ❤️‍🩹`  
**Replace:** Add your name

```html
<!-- Before -->
by your well-wisher KRISHNA ❤️‍🩹

<!-- After -->
by your well-wisher JOHN ❤️‍🩹
```

### 3. Change the Main Question
**File:** `index.html`  
**Line:** Find `<h1>❤️ Will You Become My Girlfriend? ❤️</h1>`

```html
<!-- Girlfriend/Boyfriend -->
<h1>❤️ Will You Become My Girlfriend? ❤️</h1>

<!-- Marry Me -->
<h1>💍 Will You Marry Me? 💍</h1>

<!-- Date Me -->
<h1>❤️ Will You Go On A Date With Me? ❤️</h1>

<!-- Custom -->
<h1>❤️ Will You [Your Question Here]? ❤️</h1>
```

### 4. Change Celebration Message
**File:** `index.html`  
**Find:** 
```html
<h2>Yay! ❤️ Anjana said YES! 🎉</h2>
<p>You've made Krishna the happiest person!</p>
```

**Change to:**
```html
<h2>Yay! ❤️ Sarah said YES! 🎉</h2>
<p>You've made John the happiest person!</p>
```

## Color Customization

### Background Gradient
**File:** `index.html`  
**Line:** Find `background: linear-gradient(135deg, #ff4e50, #f9d423, #e35d5b);`

**Current Colors (Red/Orange/Pink):**
```css
background: linear-gradient(135deg, #ff4e50, #f9d423, #e35d5b);
```

**Romantic Purple/Pink:**
```css
background: linear-gradient(135deg, #ff6b9d, #c06c84, #6c5b7b);
```

**Ocean Blue:**
```css
background: linear-gradient(135deg, #667eea, #764ba2, #f093fb);
```

**Sunset:**
```css
background: linear-gradient(135deg, #f093fb, #f5576c, #fdb462);
```

**Forest Green:**
```css
background: linear-gradient(135deg, #11998e, #38ef7d, #a8edea);
```

**Custom Gradient:**
- Find color codes at [colorhexa.com](https://www.colorhexa.com)
- Replace the hex colors in the gradient

### Button Colors

**Yes Button Color:**
Find `#yesBtn { background: #ffffff; color: #ff3366; }`

Change the colors:
- `background`: Button background color
- `color`: Text color

Example for gold buttons:
```css
#yesBtn {
    background: #FFD700;
    color: #000000;
}
```

**No Button Color:**
Find `#noBtn { background: rgba(255, 255, 255, 0.2); color: #ffffff; }`

## Animation Customization

### Speed Up/Slow Down Floating Hearts
Find `heart.style.animationDuration = (Math.random() * 4 + 4) + 's';`

- `4 + 4` means 4-8 seconds
- Change to `2 + 2` for 2-4 seconds (faster)
- Change to `6 + 8` for 6-14 seconds (slower)

### Speed Up/Slow Down Card Float
Find `animation: floatCard 4s ease-in-out infinite;`

- `4s` = 4 seconds per cycle
- Change to `2s` for faster bobbing
- Change to `8s` for slower bobbing

### Background Gradient Animation Speed
Find `animation: gradientBG 15s ease infinite;`

- `15s` = 15 seconds
- Make it shorter for faster color changes
- Make it longer for slower changes

## Text Customization

### Change Button Text
Find:
```html
<button id="yesBtn">YES!</button>
<button id="noBtn">No</button>
```

Change to:
```html
<button id="yesBtn">Absolutely!</button>
<button id="noBtn">Maybe Later</button>
```

### Add Emoji
You can add any emoji! Examples:

```html
<!-- More romantic -->
<div class="name-tag">Hey Anjana... 💕</div>

<!-- Playful -->
<div class="name-tag">Hey Anjana... 😍</div>

<!-- Sweet -->
<div class="name-tag">Hey Anjana... 🌹</div>
```

## Advanced Customization

### Font Changes
Find `font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;`

Replace with:
```css
/* Modern */
font-family: 'Poppins', sans-serif;

/* Romantic */
font-family: 'Playfair Display', serif;

/* Playful */
font-family: 'Comic Sans MS', cursive;
```

### Mobile Responsiveness
The page already adapts to phones, tablets, and desktops. No changes needed!

### Add More Heart Types
Find the `heartTypes` array in JavaScript:
```javascript
const heartTypes = ['❤️', '💖', '💝', '💕', '💘'];
```

Add more:
```javascript
const heartTypes = ['❤️', '💖', '💝', '💕', '💘', '💗', '💓', '💞'];
```

## Testing Your Changes

1. Save your changes to `index.html`
2. Refresh your browser (Ctrl+R or Cmd+R)
3. Clear cache if changes don't appear (Ctrl+Shift+R)
4. Test on mobile devices too!

## Common Issues

**Colors not changing?**
- Make sure you're editing the correct hex codes
- Clear browser cache (Ctrl+Shift+Delete)
- Refresh the page

**Text not updating?**
- Check for typos in the HTML
- Make sure you didn't accidentally delete closing tags
- Look for the exact line number in the guide

**Animations not working?**
- Ensure browser supports CSS3 animations
- Try a different browser
- Check console for errors (F12 → Console tab)

## Need Help?

- Check the main [README.md](README.md)
- Visit [colorhexa.com](https://www.colorhexa.com) for color codes
- Use browser DevTools (F12) to preview changes in real-time

---

Happy customizing! 💕 Make it perfect for your special moment! ✨
