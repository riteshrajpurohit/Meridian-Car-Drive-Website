# MERIDIAN — Drive Beyond

MERIDIAN is a conceptual, high-end automotive brand portfolio website. The project demonstrates a premium, modern web experience using HTML, CSS, JavaScript, and immersive multimedia elements.

## ✨ Features

- **Immersive Video Background:** Full-screen video backgrounds with scroll-linked playback for a "Scrollytelling" experience.
- **Custom Loading Screen:** A sleek loading sequence ensuring all assets are ready before the experience begins.
- **Scroll-Linked Animations:** Text blocks and visual elements reveal and animate dynamically as the user scrolls.
- **Responsive Design:** Optimized for both desktop and mobile viewing with a custom full-screen overlay navigation menu.
- **Modern Typography:** Utilizing the 'Bebas Neue' and 'Inter' font families for a bold, adventurous aesthetic.

## 📂 Project Structure

- `index.html`: The main landing page featuring the video scroll animation and dynamic text blocks.
- `story.html`: The story page detailing the brand's origin, philosophy, and future vision with scroll reveal effects.
- `Car Video.mp4`: The background video asset used on the homepage.
- `scroll-animation-best-practices.md`: Reference documentation for building efficient scroll animations.

## 🚀 Getting Started

To view the website locally, you do not need any build tools or dependencies. 

1. **Clone or Download** the repository.
2. **Open `index.html`** in your preferred web browser.
   - *Note: For the best experience and to avoid local file CORS restrictions with video playback on some browsers, it is recommended to serve the files using a local development server.*

### Running a Local Server (Optional but Recommended)

If you have Node.js installed, you can use `npx`:
```bash
npx serve .
```

Alternatively, if you have Python installed:
```bash
# Python 3
python -m http.server
```

Then navigate to `http://localhost:3000` (or the port specified by your server) in your browser.

## 🛠️ Technologies Used

- **HTML5** (Structure and semantic elements)
- **CSS3** (Styling, Flexbox, Grid, CSS Variables, and Keyframe Animations)
- **Vanilla JavaScript** (Scroll linking, event handling, and DOM manipulation)
- **requestAnimationFrame** (For performant scroll-bound animations)

## 📝 License

This project is created for conceptual and portfolio purposes.
