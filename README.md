# Terminal Portfolio Website

A retro CRT terminal-style portfolio website for Abdul Wahid, featuring a distinctive green-on-black aesthetic with authentic terminal effects.

## 🚀 Features

- **Authentic Terminal Aesthetics**: CRT monitor effects with scanlines and screen flicker
- **Fully Responsive**: Works on desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, animated typing, and blinking cursor
- **Professional Content**: Complete work experience, skills, and education
- **One-File Deployment**: Single HTML file for easy hosting

## 📦 Deployment to GitHub Pages

### Method 1: Quick Deploy (Recommended)

1. **Create a new repository** on GitHub:
   - Go to https://github.com/new
   - Name it: `wahidsaeed.github.io` (or your-username.github.io)
   - Make it public
   - Don't initialize with README

2. **Upload the file**:
   - Click "uploading an existing file"
   - Drag and drop `index.html`
   - Commit changes

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from branch → `main` → `/root`
   - Save

4. **Visit your site**:
   - Your portfolio will be live at: `https://wahidsaeed.github.io`
   - May take 1-2 minutes to deploy

### Method 2: Using Git CLI

```bash
# Clone your repository
git clone https://github.com/wahidsaeed/wahidsaeed.github.io.git
cd wahidsaeed.github.io

# Copy the index.html file to the repository
cp /path/to/index.html .

# Commit and push
git add index.html
git commit -m "Add terminal portfolio website"
git push origin main
```

Then enable GitHub Pages in repository settings as described above.

## 🎨 Customization

To customize the portfolio:

1. **Personal Information**: Update the contact details in the "about.txt" section
2. **Skills**: Modify the skill tags in the "skills/" section
3. **Experience**: Edit the experience items with your work history
4. **Colors**: Change CSS variables in `:root` for different terminal themes
5. **Links**: Update the command menu items with your social media links

### Color Themes

The current theme uses classic green terminal (`#00ff41`). Here are alternatives:

**Amber Terminal:**
```css
--terminal-green: #ffb000;
```

**Blue Terminal:**
```css
--terminal-green: #00d9ff;
```

**White/Green (IBM 3270):**
```css
--terminal-green: #00ff00;
--terminal-bg: #000000;
```

## 📱 Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Technical Stack

- Pure HTML/CSS/JavaScript
- No frameworks or dependencies
- Google Fonts: VT323 & Share Tech Mono
- CSS Grid & Flexbox for layout
- CSS animations for effects

## 📄 License

Feel free to use this template for your own portfolio. Attribution appreciated but not required.

## 🤝 Contact

- **Email**: wahidsaeed1@outlook.com
- **LinkedIn**: [linkedin.com/in/wahidsaeed](https://www.linkedin.com/in/wahidsaeed)
- **GitHub**: [github.com/wahidsaeed](https://github.com/wahidsaeed)

---

Made with ❤️ and nostalgia for the golden age of terminals
