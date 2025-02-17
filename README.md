# Nayamax E-commerce Platform

A modern, production-ready e-commerce platform built specifically for African businesses. This platform provides a complete solution for launching and managing online stores with features tailored for the African market.


## Features

- 🛍️ **Complete E-commerce Solution**
  - Product management
  - Order processing
  - Inventory tracking
  - Multi-store support

- 💳 **African Payment Integration**
  - Mobile Money support
  - Local payment methods
  - Secure transactions

- 📱 **Responsive Design**
  - Mobile-first approach
  - Fast loading times
  - Offline capabilities

- 📊 **Advanced Analytics**
  - Real-time sales tracking
  - Customer insights
  - Performance metrics

- 🔒 **Security**
  - Secure authentication
  - Data encryption
  - Regular security updates

## Quick Start

### Prerequisites

- Node.js 16.x or higher
- npm 7.x or higher

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd nayamax
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Project Structure

```
nayamax/
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── Navbar.tsx
│   │   └── VideoModal.tsx
│   ├── pages/              # Page components
│   │   ├── About.tsx
│   │   ├── Blog.tsx
│   │   ├── Contact.tsx
│   │   ├── Documentation.tsx
│   │   ├── Ecommerceconnect.tsx
│   │   ├── Investors.tsx
│   │   ├── Login.tsx
│   │   ├── Pricing.tsx
│   │   └── SignUp.tsx
│   ├── App.tsx            # Main application component
│   ├── main.tsx          # Application entry point
│   └── index.css         # Global styles
├── public/               # Static assets
├── dist/                # Production build output
├── package.json         # Project dependencies and scripts
├── tsconfig.json        # TypeScript configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── vite.config.ts       # Vite configuration
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint

## Technology Stack

- **Frontend Framework**: React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **Code Quality**: ESLint

## Customization

### Styling

The project uses Tailwind CSS for styling. You can customize the theme in `tailwind.config.js`:

```javascript
theme: {
  extend: {
    colors: {
      'nayamax': {
        blue: '#000080',
        yellow: '#FFD700',
      }
    },
    // Add your customizations here
  }
}
```

### Adding New Pages

1. Create a new component in `src/pages/`
2. Add the route in `src/App.tsx`:

```typescript
<Route path="/your-path" element={<YourComponent />} />
```

## Deployment

The project is configured for deployment on Netlify. The `netlify.toml` file contains the necessary build settings:

```toml
[build]
  command = "npm run build"
  publish = "dist"

[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200
```

## Best Practices

- Follow the existing component structure
- Use TypeScript for type safety
- Implement responsive designs
- Optimize images and assets
- Write meaningful commit messages
- Document new features

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, email support@nayamax.com or join our Slack community.

## Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)
- [Lucide Icons](https://lucide.dev/)

---

Made with ❤️ by the Nayamax Team
