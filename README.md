# React JavaScript Boilerplate

A minimal and flexible boilerplate for building modern web applications with React and JavaScript. Get started quickly with best practices and essential tooling pre-configured.

## ✨ Features

- **⚡ Fast Development** - Built with Vite for lightning-fast development and hot module replacement
- **🎨 Modern UI** - Tailwind CSS with shadcn/ui components for beautiful, accessible interfaces
- **🌙 Dark Mode** - Built-in dark/light theme toggle with persistent storage
- **📱 Responsive** - Mobile-first responsive design with modern CSS
- **🧪 Testing** - Comprehensive test suite with Vitest and Testing Library
- **🔧 Developer Experience** - ESLint, Prettier, and TypeScript support
- **📦 Package Manager** - Yarn for fast, reliable dependency management
- **🚀 Production Ready** - Optimized build process with Vite

## 🛠️ Tech Stack

- **Framework**: React 18
- **Language**: JavaScript (ES6+)
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Components**: shadcn/ui
- **Routing**: React Router v6
- **Testing**: Vitest + Testing Library
- **Linting**: ESLint + Prettier
- **Package Manager**: Yarn

## 🚀 Quick Start

### Prerequisites

- Node.js 18.0.0 or higher
- Yarn 1.22.0 or higher

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bolorundurovj/React-Javascript-Boilerplate.git
   cd React-Javascript-Boilerplate
   ```

2. **Install dependencies**
   ```bash
   yarn install
   ```

3. **Start the development server**
   ```bash
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:5173](http://localhost:5173)

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # shadcn/ui components
│   │   ├── Button.jsx
│   │   ├── Card.jsx
│   │   ├── Input.jsx
│   │   └── Label.jsx
│   ├── Layout.jsx      # Main layout component
│   └── __tests__/      # Component tests
├── contexts/           # React contexts
│   ├── ThemeContext.jsx
│   └── __tests__/      # Context tests
├── lib/                # Utility functions
│   └── utils.js
├── pages/              # Page components
│   ├── Home.jsx
│   ├── About.jsx
│   ├── Contact.jsx
│   ├── NotFound.jsx
│   └── __tests__/      # Page tests
├── test/               # Test configuration
│   └── setup.js
├── App.jsx             # Main app component
├── main.jsx            # App entry point
└── index.css           # Global styles
```

## 🧪 Testing

This boilerplate includes comprehensive testing setup with Vitest and Testing Library.

### Run Tests

```bash
# Run all tests
yarn test

# Run tests in watch mode
yarn test:watch

# Run tests with UI
yarn test:ui

# Generate coverage report
yarn test:coverage
```

### Test Structure

- **Component Tests**: Test individual UI components
- **Context Tests**: Test React contexts and hooks
- **Page Tests**: Test page components and user interactions
- **Integration Tests**: Test component interactions

## 🎨 Styling

### Tailwind CSS

The project uses Tailwind CSS for styling with a custom configuration that includes:

- Custom color palette with CSS variables
- Dark mode support
- Responsive design utilities
- Custom animations and transitions

### shadcn/ui Components

Pre-built, accessible components that follow modern design patterns:

- **Button**: Multiple variants and sizes
- **Card**: Flexible card layouts
- **Input**: Form input components
- **Label**: Accessible form labels

### Customization

1. **Colors**: Modify CSS variables in `src/index.css`
2. **Components**: Customize shadcn/ui components in `src/components/ui/`
3. **Theme**: Update `tailwind.config.js` for custom configurations

## 🔧 Development

### Available Scripts

```bash
# Development
yarn dev          # Start development server
yarn build        # Build for production
yarn preview      # Preview production build

# Testing
yarn test         # Run tests
yarn test:watch   # Run tests in watch mode
yarn test:ui      # Run tests with UI
yarn test:coverage # Generate coverage report

# Code Quality
yarn lint         # Run ESLint
yarn lint:fix     # Fix ESLint errors
yarn format       # Format code with Prettier
```

### Code Quality

- **ESLint**: JavaScript linting with React-specific rules
- **Prettier**: Code formatting for consistent style
- **TypeScript**: Type checking (optional, can be enabled)

### Git Hooks

Consider adding pre-commit hooks for:
- Running tests
- Linting code
- Formatting code

## 📦 Building for Production

```bash
# Build the project
yarn build

# Preview the production build
yarn preview
```

The build output will be in the `dist/` directory, optimized for production deployment.

## 🌐 Deployment

### Vercel (Recommended)

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect the Vite configuration
3. Deploy with zero configuration

### Netlify

1. Build the project: `yarn build`
2. Deploy the `dist/` folder to Netlify
3. Configure build settings if needed

### Other Platforms

The built application can be deployed to any static hosting service:
- GitHub Pages
- AWS S3 + CloudFront
- Firebase Hosting
- Surge.sh

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

### Development Guidelines

- Follow the existing code style
- Write tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Vite](https://vitejs.dev/) - Next generation frontend tooling
- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- [shadcn/ui](https://ui.shadcn.com/) - Beautifully designed components
- [Vitest](https://vitest.dev/) - Fast unit test framework
- [Testing Library](https://testing-library.com/) - Simple and complete testing utilities

## 📞 Support

If you have any questions or need help:

- Open an [issue](https://github.com/bolorundurovj/React-Javascript-Boilerplate/issues)
- Check the [documentation](https://docs.example.com)
- Contact us at contact@example.com

---

Made with ❤️ by the React JavaScript Boilerplate team
