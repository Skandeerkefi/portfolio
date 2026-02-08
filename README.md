# Portfolio - Skander Kefi

🚀 A modern, responsive portfolio website for Skander Kefi, Fullstack JavaScript Developer.

## ✨ Features

- **Modern Design**: Clean, professional dark theme with gradient accents
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Performance Optimized**: Built with Astro.js for lightning-fast load times
- **SEO Ready**: Complete meta tags, Open Graph, and Twitter cards
- **Accessible**: Semantic HTML and ARIA labels for better accessibility
- **Smooth Animations**: Subtle scroll animations and transitions
- **Interactive Components**: Mobile-friendly navigation, contact form, and more

## 🛠️ Built With

- **[Astro.js](https://astro.build)** - Modern static site generator
- **[Tailwind CSS](https://tailwindcss.com)** - Utility-first CSS framework
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript

## 📋 Sections

1. **Hero** - Eye-catching landing section with call-to-actions
2. **Experience** - Professional work history with timeline layout
3. **Education** - Academic background and certifications
4. **Projects** - Showcase of featured projects with live demos
5. **Testimonials** - Client and colleague recommendations
6. **Contact** - Contact form and information
7. **Footer** - Quick links and social media connections

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed on your machine
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Skandeerkefi/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:4321`

## 📝 Customization

### Update Personal Information

All placeholder content is marked with comments for easy customization:

1. **Hero Section** (`src/components/Hero.astro`):
   - Update name, title, and bio
   - Change social media links

2. **Experience Section** (`src/components/Experience.astro`):
   - Replace with your actual work experience
   - Update job titles, companies, and descriptions

3. **Education Section** (`src/components/Education.astro`):
   - Add your degrees and certifications
   - Update institutions and dates

4. **Projects Section** (`src/components/Projects.astro`):
   - Replace placeholder projects with your real projects
   - Add project descriptions, tech stacks, and links

5. **Testimonials Section** (`src/components/Testimonials.astro`):
   - Add real testimonials from colleagues or clients

6. **Contact Section** (`src/components/Contact.astro`):
   - Update contact information (email, phone, location)
   - Configure form action (use Formspree or similar service)

### Configure Form Submission

The contact form uses [Formspree](https://formspree.io/) by default:

1. Sign up for a free Formspree account
2. Create a new form and get your form ID
3. Replace `YOUR_FORM_ID` in `src/components/Contact.astro` with your actual form ID

Alternatively, you can use other form services like:
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [EmailJS](https://www.emailjs.com/)
- Custom backend API

### Styling and Theme

Colors and styles can be customized in:
- `tailwind.config.mjs` - Theme colors and design tokens
- `src/styles/global.css` - Global styles and custom CSS

## 🏗️ Building for Production

Build the site for production:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

The built files will be in the `dist/` directory.

## 🚢 Deployment

### Deploy to Vercel

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel
```

### Deploy to Netlify

1. Install Netlify CLI:
```bash
npm install -g netlify-cli
```

2. Deploy:
```bash
netlify deploy --prod
```

### Deploy to GitHub Pages

1. Update `astro.config.mjs` with your repository name:
```javascript
export default defineConfig({
  site: 'https://skandeerkefi.github.io',
  base: '/portfolio',
});
```

2. Build and deploy:
```bash
npm run build
```

3. Push the `dist` folder to the `gh-pages` branch

### Other Deployment Options

- **[Cloudflare Pages](https://pages.cloudflare.com/)**
- **[AWS Amplify](https://aws.amazon.com/amplify/)**
- **[Render](https://render.com/)**

## 📁 Project Structure

```
/
├── public/
│   ├── favicon.svg          # Site favicon
│   └── images/              # Image assets
├── src/
│   ├── components/          # Astro components
│   │   ├── Contact.astro
│   │   ├── Education.astro
│   │   ├── Experience.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── Navbar.astro
│   │   ├── Projects.astro
│   │   └── Testimonials.astro
│   ├── layouts/
│   │   └── Layout.astro     # Base layout with SEO
│   ├── pages/
│   │   └── index.astro      # Main page
│   └── styles/
│       └── global.css       # Global styles
├── astro.config.mjs         # Astro configuration
├── tailwind.config.mjs      # Tailwind configuration
├── tsconfig.json            # TypeScript configuration
└── package.json             # Dependencies and scripts
```

## 🎨 Color Scheme

The portfolio uses a dark theme with blue accents:

- **Background**: Gray-900 (#111827)
- **Cards**: Gray-800 (#1f2937)
- **Primary**: Blue-600 (#0284c7)
- **Text**: White/Gray variations

Customize colors in `tailwind.config.mjs`.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👤 Author

**Skander Kefi**

- GitHub: [@Skandeerkefi](https://github.com/Skandeerkefi)
- LinkedIn: [Skander Kefi](https://linkedin.com/in/skandeerkefi)

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

---

**Note**: Remember to replace all placeholder content with your actual information before deploying to production.
