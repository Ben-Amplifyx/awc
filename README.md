# All About Cat's 🐱

A modern, educational web application built to help people learn everything about cats. Built with Astro and the Odyssey theme, optimized for performance and SEO.

## 📖 Description

All About Cat's is a comprehensive learning resource dedicated to helping people understand and appreciate cats. Whether you're a new cat owner, considering adopting a cat, or just a cat enthusiast, this site provides valuable information about our feline friends.

## ✨ Features

- **Cat Breed Information** - Comprehensive details about different cat breeds, their characteristics, and traits
- **Cat Care Guides** - Step-by-step guides on feeding, grooming, and general cat care
- **Photo Gallery** - Beautiful collection of cat images showcasing different breeds and behaviors
- **Fun Facts** - Interesting and entertaining facts about cats
- **Behavior Tips** - Understanding cat behavior and communication
- **Health Information** - Essential health care information and common health concerns

## 🚀 Tech Stack

- **Framework:** [Astro](https://astro.build/) - The web framework for content-driven websites
- **Theme:** [Odyssey Theme](https://github.com/treefarmstudio/odyssey-theme) by Tree Farm Studio
- **Language:** TypeScript
- **Styling:** Tailwind CSS (included in Odyssey theme)
- **UI Components:** Shadcn/ui
- **Deployment:** Vercel
- **Database:** Ready for integration (Prisma, Supabase, or your choice)

## 🎯 Why Odyssey Theme?

The Odyssey theme provides:
- ⚡ Perfect Lighthouse scores
- 📝 Full-featured blog with tagging
- 🎨 Fully theme-able to match your branding
- 🔍 SEO best practices with Open Graph meta tags
- 🧩 Ready-to-use UI components
- 📱 Fully responsive design

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ben-Amplifyx/awc.git
   cd awc
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:4321` to see your site.

## 📦 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the production site
- `npm run preview` - Preview the production build locally
- `npm run astro` - Run Astro CLI commands

## 🚀 Deploy to Vercel

The easiest way to deploy your Astro site is with Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Ben-Amplifyx/awc)

### Manual Deployment

1. Push your code to GitHub
2. Import your repository in Vercel
3. Vercel will automatically detect Astro and configure the build settings
4. Click "Deploy"

### Build Settings (Auto-detected by Vercel)
- **Framework Preset:** Astro
- **Build Command:** `npm run build`
- **Output Directory:** `dist`
- **Install Command:** `npm install`

## 📁 Project Structure

```
/
├── public/              # Static assets (images, fonts, etc.)
├── src/
│   ├── components/      # Reusable Astro/React/Vue components
│   ├── layouts/         # Page layouts
│   ├── pages/           # File-based routing pages
│   │   ├── blog/        # Blog posts
│   │   └── cats/        # Cat-specific pages
│   │       ├── gallery.astro      # Photo gallery
│   │       ├── fun-facts.astro    # Fun cat facts
│   │       ├── behavior.astro     # Behavior guide
│   │       └── health.astro       # Health information
│   ├── styles/          # Global styles and Tailwind config
│   └── config/          # Site configuration
├── astro.config.mjs     # Astro configuration
├── tailwind.config.cjs  # Tailwind CSS configuration
├── tsconfig.json        # TypeScript configuration
└── package.json         # Project dependencies
```

## 📝 Content Structure

### Blog Posts
Located in `src/pages/blog/posts/`:
- **Cat Breed Guides**: Persian, Maine Coon, Siamese (with placeholders for more)
- **Care Guides**: Grooming, Nutrition, Litter Box Training

### Dedicated Pages
Located in `src/pages/cats/`:
- **Gallery** (`/cats/gallery`) - Photo gallery with categories
- **Fun Facts** (`/cats/fun-facts`) - Interesting cat facts and trivia
- **Behavior** (`/cats/behavior`) - Body language and behavior guide
- **Health** (`/cats/health`) - Health information and wellness tips

## 🎨 Customization

### Theme Configuration

The Odyssey theme is highly customizable. Edit `src/config/settings.js` to change:
- Site colors and branding
- Navigation menu items
- Footer content
- Social media links

### Adding Content

1. **Blog Posts:** Add `.md` or `.mdx` files to `src/pages/blog/posts/`
2. **Pages:** Create new `.astro` files in `src/pages/`
3. **Components:** Add reusable components to `src/components/`

### Styling

Tailwind CSS is pre-configured. You can:
- Modify `tailwind.config.cjs` for custom colors and themes
- Add global styles in `src/styles/global.css`
- Use Tailwind utility classes directly in your components

## 🗄️ Database Integration (Coming Soon)

This project is ready for database integration. Popular options include:
- **Prisma** with PostgreSQL or MySQL
- **Supabase** for a full backend solution
- **MongoDB** with Mongoose
- **Turso** for edge databases

## 🔐 Environment Variables

When you need environment variables, create a `.env` file:

```env
# Example for future use
# DATABASE_URL=your_database_url
# API_KEY=your_api_key
```

## 📚 Learn More

- [Astro Documentation](https://docs.astro.build)
- [Odyssey Theme Documentation](https://github.com/treefarmstudio/odyssey-theme)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Vercel Documentation](https://vercel.com/docs)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**AWC**

## 🐾 Acknowledgments

- Theme by [Tree Farm Studio](https://github.com/treefarmstudio)
- Built with [Astro](https://astro.build/)
- Deployed on [Vercel](https://vercel.com)

---

Made with ❤️ for cat lovers everywhere 🐱
