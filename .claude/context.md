# Luca Critelli's Portfolio Website

## Project Overview
This is a static personal portfolio website for Luca Critelli - an entrepreneur, programmer, and tinkerer based in New York City. The site is hosted on GitHub Pages at luca.critel.li.

## Technology Stack
- **Frontend**: HTML5, CSS3
- **CSS Framework**: Tailwind CSS
- **Build Tool**: Laravel Mix (for CSS compilation)
- **Hosting**: GitHub Pages
- **Domain**: luca.critel.li (custom domain via CNAME)

## Project Structure
```
/
├── index.html          # Main landing page with hero, bio, and projects
├── resume.html         # Detailed professional resume/CV
├── css/
│   └── main.css       # Compiled Tailwind CSS (11.7 KB)
├── images/            # Project thumbnails and hero images
├── CNAME              # Custom domain configuration
├── version.txt        # Current version number
└── mix-manifest.json  # Laravel Mix asset manifest
```

## Key Features
- **Responsive Design**: Built with Tailwind CSS responsive utilities
- **Professional Sections**:
  - Hero section with NYC background
  - Who I Am (professional background)
  - What I Do (core competencies)
  - My Projects (portfolio showcase)
  - Detailed resume page
- **Social Media Integration**: Links to Facebook, GitHub, Twitter, LinkedIn, YouTube
- **Performance Optimized**: Minified CSS, responsive images

## Projects Showcased
1. **LoopSpark** - Fitness studio management software
2. **ClickView Interactive** - Interactive solutions
3. **StudioGo** - Studio management platform
4. **Diventare Ricchi** - Italian financial education
5. **PayPerTrail** - Trail-based payment system
6. **HelloManagers** - Management tools

## Version Management
The project uses semantic versioning tracked in `version.txt` (currently 2.0.6).

## Development Workflow
Since this is a static site:
1. Edit HTML/CSS files directly
2. Update version.txt when making significant changes
3. Commit and push to deploy (GitHub Pages auto-deploys)

## Deployment
The site automatically deploys to GitHub Pages when changes are pushed to the main branch. The CNAME file ensures the custom domain luca.critel.li points to the site.

## Important Notes
- This is a **static site** - no server-side processing or database
- Images are already optimized (including @0.5x variants for responsive loading)
- CSS is pre-compiled and minified
- No build process needed for deployment
