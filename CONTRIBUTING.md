# Contributing to Building Trustworthy AI

Thank you for your interest in contributing to this learning resource!

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Local Development Setup

1. Clone the repository:
```bash
git clone https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI.git
cd OREDEV-Building-Trustworthy-AI
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Start the development server:
```bash
mkdocs serve
```

4. Open your browser to `http://127.0.0.1:8000`

## 📝 Making Changes

### Content Structure

- **Home Page**: `docs/index.md`
- **Chapters**: `docs/chapters/chapter-XX.md` (01-50)
- **Styling**: `docs/stylesheets/extra.css`
- **Images**: `docs/images/`
- **Configuration**: `mkdocs.yml`

### Editing Chapters

Each chapter follows a standard template with:
- Hero section with chapter title
- Overview
- Learning objectives
- Key concepts (in card sections)
- Practical examples (with code)
- Resources and links
- Hands-on exercises
- Common challenges
- Summary and next steps

### Customizing Styles

The custom color scheme (purple-blue-green) is defined in `docs/stylesheets/extra.css`. Key CSS variables:
- `--gradient-purple: #6a1b9a`
- `--gradient-blue: #1976d2`
- `--gradient-teal: #00897b`
- `--gradient-green: #43a047`

### Adding New Content

1. Edit the relevant markdown files
2. Test locally with `mkdocs serve`
3. Build to verify: `mkdocs build --strict`
4. Commit your changes

## 🎨 Custom Components

### Hero Sections
```html
<div class="hero">
  <h2>Your Title</h2>
  <p>Your description</p>
</div>
```

### Content Cards
```html
<div class="card">
Your content here
</div>
```

### Image Placeholders
```html
<div class="image-placeholder">
  Placeholder text
</div>
```

### Styled Buttons
```html
<a href="link" class="button">Button Text</a>
```

## 🔧 Building and Testing

### Build the Site
```bash
mkdocs build
```

### Build with Strict Mode (catches warnings as errors)
```bash
mkdocs build --strict
```

### Preview Built Site
```bash
cd site
python -m http.server 8001
```

## 📦 Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch via GitHub Actions (`.github/workflows/deploy-docs.yml`).

### Manual Deployment
```bash
mkdocs gh-deploy
```

## 🐛 Reporting Issues

If you find issues or have suggestions:
1. Check existing issues first
2. Create a new issue with:
   - Clear description
   - Steps to reproduce (if applicable)
   - Expected vs actual behavior
   - Screenshots (if relevant)

## 📚 Resources

- [MkDocs Documentation](https://www.mkdocs.org/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- [Markdown Guide](https://www.markdownguide.org/)

## 📄 License

See [LICENSE](LICENSE) file for details.
