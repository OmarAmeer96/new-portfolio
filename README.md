# Omar Ameer - Portfolio

A modern, elegant dark mode portfolio showcasing Flutter development expertise.

## 🚀 Features

- ✨ Modern dark theme design
- 📱 Fully responsive (mobile-first)
- ⚡ Performance optimized with lazy loading & caching
- 📧 Functional contact form (Web3Forms)
- 🎨 Smooth animations & transitions
- 🔒 Secure configuration management

## 📁 Project Structure

```
new_omar_cv/
├── index.html          # Main portfolio file
├── config.js          # Web3Forms key (DO NOT COMMIT - in .gitignore)
├── .gitignore         # Git ignore rules
├── SECURITY_SETUP.md  # Security configuration guide
└── assets/            # Images and resources
```

## 🔧 Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/OmarAmeer96/new-portfolio.git
   cd new-portfolio
   ```

2. **Configure Web3Forms**

   - The `config.js` file contains your Web3Forms access key
   - This file is already in `.gitignore` and won't be committed
   - Keep a backup of your access key in a secure location

3. **Open locally**

   ```bash
   # Windows (PowerShell)
   Start-Process "index.html"

   # Or double-click index.html
   ```

## 🌐 Deployment

### GitHub Pages

1. Push code to GitHub (config.js won't be included)
2. Go to Settings → Pages
3. Select main branch
4. **Important**: Manually add `config.js` to your repository via GitHub UI or create it in the deployment

### Netlify / Vercel

1. Connect your GitHub repository
2. Deploy settings:
   - Build command: (none needed)
   - Publish directory: `.`
3. Add `WEB3FORMS_KEY` as environment variable (recommended)
4. Or manually upload `config.js` after deployment

## 🔒 Security

- ✅ Web3Forms access key is in `config.js` (ignored by Git)
- ✅ Never commit `config.js` to public repositories
- ✅ Use environment variables for production deployments

## 📧 Contact Form

The contact form uses [Web3Forms](https://web3forms.com) to send emails to: **omar.ameer244@gmail.com**

**Validation Rules:**

- Name: Required (minimum 2 characters)
- Email: Required (valid email format)
- Phone: Optional
- Message: Required (non-empty)

## 🎨 Customization

### Colors

Edit CSS variables in `index.html`:

```css
:root {
  --primary-color: #00d4ff;
  --secondary-color: #a855f7;
  --accent-color: #f59e0b;
}
```

### Content

Update the HTML sections directly in `index.html`:

- Hero Section
- About
- Skills
- Experience
- Projects
- Education
- Contact

## 📦 Performance Features

- **Lazy Loading**: Images load only when visible
- **Image Caching**: LocalStorage caching with WebP conversion
- **Shimmer Effects**: Loading placeholders for smooth UX
- **GPU Acceleration**: Hardware-accelerated animations
- **Debounced Scroll**: Optimized scroll event handling

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

© 2026 Omar Ameer. All rights reserved.

## 🤝 Contact

- Email: omar.ameer244@gmail.com
- Phone: +20 1554111002
- LinkedIn: [Omar Ameer](https://www.linkedin.com/in/omar-ameer-a57314261/)
- GitHub: [OmarAmeer96](https://github.com/OmarAmeer96)

---

Made with 🧡 by Omar Ameer
