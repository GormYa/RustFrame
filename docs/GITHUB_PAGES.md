# GitHub Pages Setup

This directory contains the GitHub Pages site for RustFrame.

## View the Site

Once GitHub Pages is enabled, the site will be available at:
`https://salihcantekin.github.io/RustFrame/`

## Enabling GitHub Pages

1. Go to repository Settings
2. Navigate to "Pages" section
3. Under "Source", select:
   - Branch: `master` (or the branch containing this docs folder)
   - Folder: `/docs`
4. Click "Save"
5. Wait a few minutes for the site to build and deploy

## Local Development

To preview the site locally:

1. Open `index.html` in a web browser
2. Or use a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then visit http://localhost:8000
   ```

## Files

- `index.html` - Main page with all content
- `styles.css` - Styling and layout
- `script.js` - Interactive features and animations
- `_config.yml` - Jekyll configuration for GitHub Pages

## Content Structure

The page includes:
- Hero section with download links
- What is RustFrame section
- Core features overview
- Quick start guide
- Platform support details
- Documentation links
- Video walkthroughs
- Footer with links

## Updating Content

To update the content:
1. Edit `index.html` for content changes
2. Edit `styles.css` for styling changes
3. Edit `script.js` for interactive features
4. Commit and push changes
5. GitHub Pages will automatically rebuild

## Notes

- All documentation markdown files are preserved in their subdirectories
- The main page provides an overview and links to detailed docs
- The site is responsive and mobile-friendly
