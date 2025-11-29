<div align="center">

![Thumbnail](images/Thumbnail.png)

# 🚀 Fadhil Annaufal Musyafa - Portfolio Website

**A modern, responsive portfolio website showcasing projects, skills, and professional experience**

[![Next.js](https://img.shields.io/badge/Next.js-15.0-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18.3-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38bdf8?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-3178c6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

[🌐 Live Demo](#) • [📖 Documentation](#) • [🐛 Report Bug](#) • [💡 Request Feature](#)

</div>

---

## ✨ Features

- 🎨 **Modern UI/UX Design** - Clean, intuitive interface with smooth animations
- 📱 **Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- 🌙 **Dark Theme** - Beautiful dark mode with smooth theme transitions
- ⚡ **Performance Optimized** - Built with Next.js 15 and Turbopack for blazing-fast performance
- 🎭 **Smooth Animations** - Powered by Framer Motion for delightful user interactions
- 📧 **Contact Form** - Integrated EmailJS for seamless communication
- 🔗 **GitHub Integration** - Dynamic project fetching from GitHub API
- 🎯 **SEO Friendly** - Optimized meta tags and semantic HTML
- ♿ **Accessible** - WCAG compliant for better accessibility

## 🛠️ Tech Stack

### Frontend
- **Framework**: [Next.js 15](https://nextjs.org/) with App Router
- **UI Library**: [React 18.3](https://reactjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + [tailwindcss-animate](https://github.com/jamiebuilds/tailwindcss-animate)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/) + [React Icons](https://react-icons.github.io/react-icons/)
- **Forms**: [React Hook Form](https://react-hook-form.com/)
- **UI Components**: [Radix UI](https://www.radix-ui.com/)

### Backend & Services
- **Email Service**: [EmailJS](https://www.emailjs.com/)
- **Data Fetching**: [SWR](https://swr.vercel.app/)
- **API**: GitHub API integration

### Development Tools
- **Package Manager**: npm
- **Build Tool**: Turbopack (Next.js 15)
- **Linting**: ESLint with Next.js config
- **Version Control**: Git

## 📦 Installation

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Step-by-Step Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/KEI404-A/my-portofolio.git
   cd my-portofolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables** (if needed)
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
# Create production build
npm run build

# Start production server
npm start
```

## 📁 Project Structure

```
my-portofolio/
├── app/                    # Next.js App Router
│   ├── (contact)/         # Contact page route
│   ├── (home)/            # Home page route
│   ├── (projects)/        # Projects page route
│   ├── fonts/             # Custom fonts
│   ├── globals.css        # Global styles
│   └── layout.js          # Root layout
├── components/            # Reusable components
│   ├── Footer/           # Footer component
│   ├── Header/           # Header/Navigation
│   ├── Providers/        # Context providers
│   └── ui/               # UI components (buttons, cards, etc.)
├── lib/                  # Utility functions
├── public/               # Static assets
│   └── projects/        # Project images
├── images/              # Images and thumbnails
├── config.js            # Site configuration
├── package.json         # Dependencies
└── README.md            # This file
```

## 🎯 Key Sections

- **🏠 Home** - Hero section, skills showcase, experience timeline
- **💼 Projects** - Portfolio projects with detailed descriptions
- **📧 Contact** - Contact form with EmailJS integration

## 🚀 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with Turbopack |
| `npm run build` | Create production build |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint |
| `npm run spotify-auth` | Spotify authentication script |

## 🎨 Customization

### Update Personal Information

Edit `config.js` to customize:
- Developer name
- Social media links
- Projects
- Skills
- Experience
- Contact information

### Styling

- Global styles: `app/globals.css`
- Tailwind config: `tailwind.config.js`
- Component styles: Inline Tailwind classes

## 📸 Screenshots

![Portfolio Screenshot](images/Screenshot%202025-11-30%20003655.png)

> Screenshot showcasing the portfolio website interface

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Fadhil Annaufal Musyafa**

- 🌐 Website: [Portfolio](https://my-portofolio-mu-six.vercel.app)
- 💼 LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/fadhil-annaufal-musyafa-0223a2372)
- 📧 Email: solohunter696@gmail.com
- 🐙 GitHub: [@KEI404-A](https://github.com/KEI404-A)
- 📍 Location: Indonesia

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) for the amazing framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS
- [Framer Motion](https://www.framer.com/motion/) for smooth animations
- [Radix UI](https://www.radix-ui.com/) for accessible components
- All the open-source contributors and libraries used in this project

---

<div align="center">

**⭐ If you like this project, give it a star on GitHub! ⭐**

Made with ❤️ by [Fadhil Annaufal Musyafa](https://github.com/KEI404-A)

</div>
