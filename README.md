# Landing Page

A modern, animated landing page perfect for domain placeholders or coming soon pages.

## Features

- 🎨 Modern gradient design with animations
- 📱 Fully responsive (mobile-first)
- ⚡ Lightning fast loading
- 🎯 Email signup functionality
- 🌟 Floating background animations
- 🔗 Social media links ready
- 🐳 Docker support

## Preview

The landing page includes:
- Animated logo with pulsing effect
- Gradient text effects
- Floating background shapes
- Interactive email signup
- Hover effects on all interactive elements
- Modern glassmorphism design elements

## Docker Deployment

### Local Development & Testing

1. **Build and run with Docker:**
   ```bash
   docker build -t landing-page .
   docker run -p 80:80 landing-page
   ```

2. **Or use Docker Compose:**
   ```bash
   docker-compose up -d
   ```

3. **Access your site:**
   - Open http://localhost in your browser

### Coolify Deployment

1. **Push to GitHub:**
   - Create a private repository on GitHub
   - Push this code to your repository

2. **Connect to Coolify:**
   - In Coolify, create a new application
   - Connect your GitHub repository
   - Set build context to repository root
   - Coolify will automatically detect the Dockerfile

3. **Deploy:**
   - Coolify will build and deploy automatically
   - Your landing page will be available on your domain

## Customization

### Colors and Branding
- Edit the CSS custom properties in `styles.css`
- Replace gradient colors in the `:root` section
- Update the logo section with your own branding

### Content
- Update the title and subtitle in `index.html`
- Modify the features section
- Add your social media links
- Customize the email signup functionality

### Email Integration
The email signup is currently frontend-only. To make it functional:
1. Add a backend service (Node.js, PHP, Python)
2. Integrate with email services like Mailchimp, ConvertKit, or SendGrid
3. Or use a service like Netlify Forms or Formspree

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── Dockerfile          # Docker configuration
├── docker-compose.yml  # Docker Compose setup
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Minimal dependencies (only Google Fonts)
- Optimized animations with CSS transforms
- Responsive images and layouts
- Fast loading times

## License

This project is open source and available under the MIT License.
