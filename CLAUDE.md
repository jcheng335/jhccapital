# JHC Capital Website Documentation

## Project Overview

JHC Capital is a professional financial services website built with modern web technologies. The site showcases investment management services, financial advisory solutions, and partnership opportunities.

### Key Features
- Responsive design with mobile-first approach
- Professional financial services presentation
- Netlify Forms integration for contact functionality
- Accessible navigation with mobile menu
- Clean, modern design with brand colors

## Project Structure

```
jhccapital-site/
├── index.html          # Homepage
├── about.html          # About page with company info and leadership
├── services.html       # Services page with detailed offerings
├── contact.html        # Contact page with Netlify form
├── CLAUDE.md          # This documentation file
├── assets/
│   ├── css/
│   │   └── style.css  # Complete stylesheet
│   ├── js/
│   │   └── main.js    # JavaScript functionality
│   └── images/        # Image assets (placeholder)
└── netlify.toml       # Netlify configuration
```

## Brand Guidelines

### Colors
- Primary Blue: `#1f365b` - Used for headers, navigation, buttons
- Accent Orange: `#fb6f3f` - Used for CTAs and highlights
- Light Gray: `#f8f9fa` - Background sections
- Dark Gray: `#333333` - Body text

### Typography
- Base font size: 18px
- Font family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif
- Headings: Bold weight with specific sizing hierarchy

## Development Guidelines

### HTML Structure
- Semantic HTML5 elements used throughout
- Consistent navigation structure across all pages
- Accessible form elements with proper labels
- Mobile-responsive meta viewport tag

### CSS Architecture
- Mobile-first responsive design
- Utility classes for common patterns
- Component-based styling approach
- CSS Grid and Flexbox for layouts

### JavaScript Features
- Mobile menu toggle functionality
- Smooth scroll behavior
- Form validation enhancements
- No external dependencies

## Netlify Integration

### Forms
Contact form uses Netlify Forms with:
- Hidden `form-name` input field set to "inquiry"
- `data-netlify="true"` attribute on form element
- Automatic spam filtering
- Form submissions accessible in Netlify dashboard

### Deployment
1. Push to Git repository
2. Connect repository to Netlify
3. Deploy with default build settings
4. Forms automatically detected and configured

## Content Management

### Page Content
- **Homepage**: Hero section, services overview, value proposition
- **About**: Company story, mission, core values, leadership team
- **Services**: Detailed service offerings, partnership programs
- **Contact**: Contact form, office information, FAQ section

### Images
Currently using placeholder divs for images. Replace with actual images:
- Hero background: `assets/images/hero-bg.jpg`
- Team photos: Add to `assets/images/team/`
- Service icons: Consider adding custom icons

## Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Mobile Optimizations
- Hamburger menu for navigation
- Stacked layouts for cards and grids
- Adjusted typography sizes
- Touch-friendly button sizes

## SEO Considerations

- Descriptive page titles
- Semantic HTML structure
- Alt text placeholders for images
- Clean URL structure
- Mobile-responsive design

## Future Enhancements

### Recommended Additions
1. Analytics integration (Google Analytics)
2. Cookie consent banner
3. Live chat integration
4. Blog/Resources section
5. Client portal login
6. Newsletter signup
7. Social media links
8. Testimonials section

### Performance Optimizations
1. Image optimization and lazy loading
2. CSS and JS minification
3. Critical CSS inlining
4. CDN integration
5. Browser caching headers

## Maintenance

### Regular Updates
- Content reviews quarterly
- Security updates as needed
- Performance monitoring
- Form submission testing
- Mobile responsiveness checks

### Backup Strategy
- Git repository for version control
- Netlify automatic deployments
- Regular content backups
- Form submission exports

## Support Resources

- Netlify Documentation: https://docs.netlify.com
- Web Accessibility Guidelines: https://www.w3.org/WAI/
- CSS Grid Guide: https://css-tricks.com/snippets/css/complete-guide-grid/
- Responsive Design Best Practices: https://web.dev/responsive-web-design-basics/