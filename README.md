# Abhishek Jha - Portfolio Website 🚀

A modern, interactive 3D portfolio website showcasing engineering projects and creative work.

## ✨ Features

- **3D Interactive Hero Section** - Powered by Three.js with floating particles and responsive 3D geometry
- **Smooth Animations** - GSAP-powered scroll animations and transitions
- **Responsive Design** - Mobile-first approach using Tailwind CSS
- **Contact Form** - Firebase integration for message handling
- **Modern UI/UX** - Dark theme with gradient accents and hover effects

## 🛠️ Built With

- **HTML5** - Semantic structure
- **CSS3** - Custom properties and modern styling
- **JavaScript ES6+** - Interactive functionality
- **Three.js** - 3D graphics and animations
- **GSAP** - Advanced animations
- **Tailwind CSS** - Utility-first CSS framework
- **Firebase** - Backend services for contact form

## 🚀 Live Demo

Visit: [https://abhishek-dbz.github.io/portfolio](https://abhishek-dbz.github.io/abhishek/#portfolio)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main website file
├── README.md          # Project documentation
└── assets/            # Images and other assets (if any)
```

## 🔧 Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abhishek-dbz/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. Visit `http://localhost:8000` to view the website

## 📧 Contact Form Setup

To enable the contact form functionality:

1. Create a Firebase project at [https://console.firebase.google.com/](https://console.firebase.google.com/)
2. Enable Firestore Database
3. Get your Firebase config
4. Replace the placeholder config in `index.html`:
   ```javascript
   const firebaseConfig = {
     apiKey: "your-api-key",
     authDomain: "your-project.firebaseapp.com",
     projectId: "your-project-id",
     storageBucket: "your-project.appspot.com",
     messagingSenderId: "123456789",
     appId: "your-app-id"
   };
   ```

## 🌟 Performance Features

- **Optimized Loading** - CDN-hosted libraries
- **Responsive Images** - Placeholder service integration
- **Smooth Scrolling** - Hardware-accelerated animations
- **Mobile Optimized** - Touch-friendly interface

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy theming:
```css
:root {
  --bg-dark: #0A0A0A;
  --bg-medium: #111111;
  --primary: #3B82F6;
  --secondary: #8B5CF6;
}
```

### Content
Update the content sections in `index.html`:
- Hero section text
- About section content
- Portfolio projects
- Skills and technologies
- Contact information

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Abhishek Jha**
- 3D Generalist & Technical Artist
- Electronic Engineering Student
- Portfolio: [https://abhishek-dbz.github.io/portfolio](https://abhishek-dbz.github.io/portfolio)

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) for 3D graphics
- [GSAP](https://greensock.com/gsap/) for animations
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Firebase](https://firebase.google.com/) for backend services
