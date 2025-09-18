# Doc Con Music Apps Website

A professional, modern website for Doc Con Music Apps - a company specializing in innovative music application development.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Animated music visualization, hover effects, and smooth scrolling
- **Contact Form**: Integrated contact form that opens email client
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Accessibility**: Keyboard navigation and focus management
- **Performance**: Optimized CSS and JavaScript for fast loading

## Sections

1. **Hero Section**: Eye-catching introduction with animated music visualization
2. **Services**: Overview of development services offered
3. **Portfolio**: Featured projects showcase
4. **About**: Company information and statistics
5. **Contact**: Contact form and company details
6. **Footer**: Additional links and company information

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## Setup Instructions

### Option 1: Neocities (Recommended for Free Hosting)

1. **Create Neocities Account**:
   - Go to [neocities.org](https://neocities.org)
   - Sign up for a free account
   - Upload all files from this folder

2. **Domain Setup**:
   - Purchase `doc-con.com` from a domain registrar (Namecheap, GoDaddy, etc.)
   - Point the domain to your Neocities site
   - Follow Neocities' domain setup instructions

### Option 2: GitHub Pages

1. **Create GitHub Repository**:
   - Create a new repository named `doc-con-website`
   - Upload all files to the repository

2. **Enable GitHub Pages**:
   - Go to repository Settings > Pages
   - Select source branch (usually `main`)
   - Your site will be available at `username.github.io/doc-con-website`

3. **Custom Domain**:
   - Add `doc-con.com` to your repository
   - Update DNS settings to point to GitHub Pages

### Option 3: Netlify

1. **Deploy to Netlify**:
   - Go to [netlify.com](https://netlify.com)
   - Drag and drop this folder to deploy
   - Your site will get a random URL

2. **Custom Domain**:
   - Add `doc-con.com` in Netlify dashboard
   - Update DNS settings as instructed

## Email Forwarding Setup

### Using WebRaven (Free)

1. **Sign Up**:
   - Go to [webraven.com/free-email-forwarding](https://webraven.com/free-email-forwarding)
   - Create a free account

2. **Add Domain**:
   - Add `doc-con.com` to your account
   - Verify domain ownership

3. **Configure Forwarding**:
   - Set up `info@doc-con.com` to forward to your personal email
   - Follow their DNS setup instructions

### Using Porkbun (Free with Domain)

1. **Domain Registration**:
   - Register `doc-con.com` with Porkbun
   - They offer 20 free email forwards with domain registration

2. **Email Setup**:
   - Go to domain management
   - Set up email forwarding for `info@doc-con.com`
   - Forward to your personal email address

### Using Addy.io (Free)

1. **Sign Up**:
   - Go to [addy.io](https://addy.io)
   - Create a free account

2. **Domain Configuration**:
   - Add your domain `doc-con.com`
   - Set up email aliases
   - Configure forwarding to your email

## DNS Configuration

For email forwarding, you'll need to add these DNS records:

### MX Records
```
Type: MX
Name: @
Value: mail.webraven.com (or your email service provider)
Priority: 10
```

### TXT Records (SPF)
```
Type: TXT
Name: @
Value: v=spf1 include:webraven.com ~all
```

## Customization

### Colors
The website uses a purple/blue color scheme. To change colors, update these CSS variables in `styles.css`:
- Primary: `#6366f1`
- Secondary: `#8b5cf6`
- Background: `#f8fafc`

### Content
- Update company information in `index.html`
- Modify services, portfolio items, and contact details
- Replace placeholder images with actual project screenshots

### Contact Form
The contact form currently opens the user's email client. To integrate with a backend service:
1. Update the form action in `script.js`
2. Add server-side processing
3. Consider using services like Formspree or Netlify Forms

## Performance Optimization

- Images are optimized for web
- CSS and JavaScript are minified-ready
- Fonts are loaded from Google Fonts CDN
- Smooth animations use CSS transforms for better performance

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This website template is created for Doc Con Music Apps. Feel free to modify and use for your own projects.

## Support

For questions about this website template, contact info@doc-con.com

---

**Total Cost Estimate:**
- Domain registration: $10-15/year
- Hosting: Free (with chosen platform)
- Email forwarding: Free
- **Total: ~$10-15/year**
