# Shiqiang Huang's Academic Homepage

A modern, responsive academic personal homepage built with Jekyll, based on the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) template.

## 🌐 Live Demo

Visit: [https://kshqsz.github.io](https://kshqsz.github.io)

## ✨ Features

- 📱 **Responsive Design**: Automatically adapts to different screen sizes
- 🎨 **Clean & Minimal**: Beautiful and simple design suitable for academic pages
- 📊 **Google Scholar Integration**: Auto-update citation statistics (optional)
- 🔍 **SEO Optimized**: Better search engine visibility
- ⚡ **Fast Loading**: Optimized for performance

## 🛠️ Quick Start

### Local Development

1. Install Ruby and Jekyll
2. Clone this repository
3. Run `bundle install`
4. Run `bundle exec jekyll serve`
5. Open `http://localhost:4000` in your browser

### Customization

1. Edit `_config.yml` for site settings and author information
2. Edit `_pages/about.md` for main page content
3. Edit `_data/navigation.yml` for navigation menu
4. Add your profile image to `images/` folder

## 📁 Project Structure

```
├── _config.yml          # Site configuration
├── _data/
│   └── navigation.yml   # Navigation menu
├── _includes/           # HTML components
├── _layouts/            # Page layouts
├── _pages/
│   └── about.md         # Main page content
├── _sass/               # SCSS stylesheets
├── assets/              # CSS, JS, fonts
├── images/              # Images folder
└── google_scholar_crawler/  # Citation crawler (optional)
```

## 📝 Content Editing

### Add News
```markdown
# 🔥 News
- *2024.09*: 🎉 Your news here!
```

### Add Projects/Publications
```markdown
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Label</div><img src='images/image.png' alt="alt" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Project Title**

Description here.
</div>
</div>
```

## 🙏 Acknowledgments

- [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) by RayeRen
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)
- [Font Awesome](https://fontawesome.com/)

## 📄 License

MIT License
