# Brave-Browser-Replica---HTML-CSS-New-Tab-Page
```markdown
# Brave Browser Replica - HTML/CSS New Tab Page

A faithful front-end replica of the Brave Browser's new tab page, built with pure HTML and CSS. This project recreates the clean, privacy-focused interface of Brave including stats cards, top sites, Brave News, and the iconic URL bar.

![Brave Browser Replica Preview](https://via.placeholder.com/800x450/ff7e4a/ffffff?text=Brave+Replica+Preview)

##  Features

- **Complete Browser UI** - Title bar with traffic light controls (macOS style)
- **Authentic URL Bar** - Combined address/search bar with Brave icon, lock indicator, and action buttons
- **Stats Dashboard** - Trackers blocked, time saved, and BAT earnings cards
- **Brave Creators Panel** - Tipping and rewards interface
- **Favourite Sites Grid** - Customizable top sites with icons
- **Brave News Section** - Latest news cards with sources and timestamps
- **Extension Tray** - Simulated extension icons in the toolbar
- **Status Footer** - Shields, rewards, wallet, and playlist shortcuts

##  Live Demo

[View Live Demo](#) - *Add your deployment link here*

##  Prerequisites

No special prerequisites! This is a pure HTML/CSS project that runs in any modern web browser.
##  Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/brave-browser-replica.git
   cd brave-browser-replica
   ```

2. **Open in browser**
   - Simply open `index.html` in your preferred browser
   - Or use a local development server (e.g., Live Server for VS Code)

##  Customization

### Colors
The main Brave orange color is `#ff6b3d`. You can modify the gradient backgrounds and accent colors in the CSS variables and classes.

### Top Sites
Edit the `.top-sites` grid section to add/remove favourite sites:
```html
<div class="site-tile">
  <div class="tile-icon"><i class="fab fa-github"></i></div>
  <span class="tile-name">GitHub</span>
</div>
```

### News Cards
Update the `.news-grid` section with your own headlines and sources:
```html
<div class="news-card">
  <div class="news-source">
    <div class="source-icon" style="background-color: #ff7e4a;"></div>
    <span class="source-name">Source · time</span>
  </div>
  <div class="news-title">Your headline</div>
  <div class="news-desc">Description text...</div>
</div>
```

### Stats Numbers
Modify the values in the `.stats-info` section:
```html
<h3>5.2k</h3>  <!-- Change to your desired number -->
<p>trackers blocked</p>
```

##  Project Structure

```
brave-browser-replica/
├── index.html          # Main HTML file with embedded styles
├── README.md           # Project documentation
└── assets/            # (Optional) Images and icons
```

##  Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Gradients)
- Font Awesome 6 (icons)
- No JavaScript - pure static interface

##  Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

- Inspired by [Brave Browser](https://brave.com/)
- Icons by [Font Awesome](https://fontawesome.com/)
- Design replica for educational purposes

