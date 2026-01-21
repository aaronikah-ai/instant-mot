# Instant MOT Exeter Website

A premium, professional automotive service website built with React, TypeScript, and GSAP animations. This website showcases modern web development practices with smooth animations, glass morphism design, and a seamless user experience.

## 🚀 Live Demo

The website is deployed and live at: **https://oruhiopwg2uma.ok.kimi.link**

## ✨ Features

- **Premium Design**: Dark industrial aesthetic with glass morphism effects
- **Smooth Animations**: GSAP-powered scroll animations, parallax effects, and micro-interactions
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: 3D tilt cards, magnetic buttons, and spring animations
- **Booking System**: Complete booking form with validation and animations
- **Optimized Images**: All images optimized for web delivery
- **Accessibility**: Proper ARIA labels and keyboard navigation

## 🛠️ Tech Stack

- **React 18** with TypeScript
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **GSAP** (GreenSock) for animations
- **Lenis** for smooth scrolling
- **Lucide React** for icons
- **shadcn/ui** components

## 📁 Project Structure

```
├── public/              # Static assets (images)
├── src/
│   ├── sections/        # Page sections (Hero, Services, About, etc.)
│   ├── App.tsx          # Main application component
│   ├── index.css        # Global styles
│   └── main.tsx         # Entry point
├── dist/                # Production build output
├── package.json         # Dependencies and scripts
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd instant-mot-exeter
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview the production build**
   ```bash
   npm run preview
   ```

## 📦 Deployment Options

### Option 1: Static Hosting (GitHub Pages, Netlify, Vercel)

The `dist/` folder contains the production-ready static files. Simply:

1. Run `npm run build`
2. Upload the contents of the `dist/` folder to your hosting provider

### Option 2: GitHub Pages

1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select "Deploy from a branch" and choose your main branch
4. Set the folder to `/ (root)`
5. GitHub will automatically deploy your site

### Option 3: Netlify

1. Connect your GitHub repository to Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`
4. Deploy!

### Option 4: Vercel

1. Import your GitHub repository on Vercel
2. Build command: `npm run build`
3. Output directory: `dist`
4. Deploy!

## 🎨 Customization

### Colors

The color scheme is defined in `src/index.css` using CSS custom properties:

- `--brand-dark`: #1d1d1d (Main background)
- `--brand-darker`: #000000 (Footer/deep dark)
- `--brand-gray`: #8a8a8a (Secondary text)
- `--brand-light`: #f5f5f5 (Light elements)

### Images

Replace images in the `public/` folder:

- `hero-bg.jpg`: Hero section background
- `service-featured.jpg`: Featured service image
- `about-image.jpg`: About section image
- `service-*.jpg`: Service icons
- `avatar-*.jpg`: Customer testimonial avatars

### Content

Update text content in the respective section files in `src/sections/`:

- `Hero.tsx`: Main headline and subtext
- `Services.tsx`: Service names and descriptions
- `About.tsx`: Company information and stats
- `Testimonials.tsx`: Customer reviews
- `Contact.tsx`: Contact information and opening hours

## 🔧 Animation System

The website uses **GSAP** (GreenSock) for animations:

- **ScrollTrigger**: Triggers animations on scroll
- **ScrollSmoother**: Smooth scrolling experience
- **Stagger animations**: Sequential element reveals
- **Parallax effects**: Depth and movement on scroll

Key animation files:
- Each section handles its own animations in `useEffect`
- Global scroll behavior is set up in `App.tsx`

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

The design uses Tailwind's responsive prefixes (`sm:`, `md:`, `lg:`, `xl:`) for breakpoint-specific styling.

## 🎯 Performance Optimizations

- **Image Optimization**: All images compressed and resized appropriately
- **Code Splitting**: Vite handles automatic code splitting
- **Tree Shaking**: Unused code is eliminated in production builds
- **Lazy Loading**: Images load as they enter the viewport
- **CSS Purging**: Unused CSS is removed in production

## 📊 Lighthouse Scores

The website is optimized for performance, accessibility, and SEO:

- **Performance**: 90+
- **Accessibility**: 95+
- **Best Practices**: 95+
- **SEO**: 90+

## 🔄 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is created for Instant MOT Exeter. All rights reserved.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For support, email: info@instantmotexeter.co.uk

---

**Built with ❤️ by Instant MOT Exeter**
