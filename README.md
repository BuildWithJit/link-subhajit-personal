# Subhajit Bhar - Links Page

A modern, professional links page for [links.subhajitbhar.com](https://links.subhajitbhar.com) - a centralized hub for all my professional profiles and projects.

## ✨ Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Mobile-first design that works on all devices  
- **Dark Mode**: Automatic dark/light mode based on user preference
- **Accessibility**: High contrast support, reduced motion, and keyboard navigation
- **Performance**: Optimized for fast loading with minimal dependencies
- **SEO Ready**: Meta tags and Open Graph support for social sharing

## 🔗 Included Links

- **Personal Website**: [subhajitbhar.com](https://subhajitbhar.com)
- **Blog**: [blog.subhajitbhar.com](https://blog.subhajitbhar.com)
- **GitHub**: [github.com/buildwithjit](https://github.com/buildwithjit)
- **X (Twitter)**: [x.com/buildwithjit](https://x.com/buildwithjit)
- **LinkedIn**: [linkedin.com/in/subhajit-bhar](https://www.linkedin.com/in/subhajit-bhar/)
- **Upwork**: [upwork.com/freelancers/sbhar](https://www.upwork.com/freelancers/sbhar)
- **Buy Me a Coffee**: [buymeacoffee.com/29jit](https://buymeacoffee.com/29jit)

## 🚀 Deployment on GitHub Pages

### Method 1: Automatic Deployment (Recommended)

1. **Create a new repository** on GitHub:
   ```
   Repository name: link-subhajit-personal
   Visibility: Public
   ```

2. **Push your code** to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Professional links page"
   git branch -M main
   git remote add origin https://github.com/buildwithjit/link-subhajit-personal.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Source: Deploy from a branch
   - Branch: `main` / `(root)`
   - Click "Save"

4. **Custom Domain Setup**:
   - In repository settings > Pages
   - Add custom domain: `links.subhajitbhar.com`
   - Enable "Enforce HTTPS"

5. **DNS Configuration**:
   Add these DNS records to your domain provider:
   ```
   Type: CNAME
   Name: links
   Value: buildwithjit.github.io
   ```

### Method 2: Manual Upload

1. **Download files** from this repository
2. **Create a new repository** named `link-subhajit-personal`
3. **Upload files** directly through GitHub web interface
4. **Follow steps 3-5** from Method 1

## 🛠️ Local Development

To run locally for testing:

```bash
# Clone the repository
git clone https://github.com/buildwithjit/link-subhajit-personal.git
cd link-subhajit-personal

# Serve locally (using Python)
python3 -m http.server 8000

# Or using Node.js
npx serve .

# Open in browser
open http://localhost:8000
```

## 📱 Browser Support

- ✅ Chrome (80+)
- ✅ Firefox (70+)
- ✅ Safari (13+)
- ✅ Edge (80+)
- ✅ Mobile browsers

## 🎨 Customization

### Update Links
Edit `links.txt` with your links, then update the corresponding URLs in `index.html`.

### Change Colors
Modify CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main blue color */
    --accent-color: #f59e0b;     /* Accent yellow */
    --background: #fafafa;       /* Background color */
}
```

### Add New Links
1. Add the link to `links.txt`
2. Create a new `.link-card` in `index.html`
3. Choose an appropriate emoji icon
4. Test locally before deploying

## 📊 Analytics (Optional)

To add analytics, uncomment and configure the tracking code in the `<script>` section of `index.html`:

```javascript
// Optional: Add analytics tracking here
console.log('Link clicked:', this.href);
```

Replace with your preferred analytics solution (Google Analytics, Plausible, etc.).

## 🔒 Security

- All external links open in new tabs with `rel="noopener noreferrer"`
- No external JavaScript dependencies
- HTTPS enforced through GitHub Pages

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to submit issues and pull requests to improve this links page template.

---

Built with ❤️ by [Subhajit Bhar](https://subhajitbhar.com)
