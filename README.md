# ClimateSync

> Empowering individuals with intelligent, personalized weather insights that enhance daily decision-making

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/climatex/climatex)

## Overview

ClimateSync is an AI-powered weather platform designed to provide hyper-local, actionable weather insights. By combining advanced meteorological data with personalized recommendations, users can make more informed decisions about their daily activities and understand climate impacts.

## Features

- ✨ Hyper-local weather predictions
- 🚀 AI-powered personalized recommendations
- 💡 Climate impact visualization
- 🔒 Secure user authentication
- 📍 Interactive geolocation mapping

## Tech Stack

**Frontend:**
- React 18 with TypeScript
- Vite 5.x
- Tailwind CSS
- React Router v6
- TanStack Query

**Backend:**
- Node.js 20 LTS
- Next.js API Routes
- PostgreSQL with Prisma ORM
- NextAuth.js

**Deployment:**
- Vercel (Frontend)
- Railway (Backend)
- Supabase (Database)

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/climatex/climatex.git

# Install dependencies
cd climatex
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

## Project Structure

```
/
├── src/
│   ├── components/     # React UI components
│   ├── pages/          # Application pages
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   └── styles/         # Tailwind CSS
├── prisma/             # Database schema
├── public/             # Static assets
└── tests/              # Test suites
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build production version
npm run test        # Run test suite
npm run lint        # Lint code
```

### Environment Variables

```env
NEXT_PUBLIC_API_URL=your_api_endpoint
DATABASE_URL=your_postgresql_connection_string
NEXTAUTH_SECRET=your_auth_secret
```

## Testing

```bash
# Run unit and integration tests
npm test

# Run end-to-end tests
npm run test:e2e
```

## Deployment

### Vercel Deployment

```bash
npm run build
vercel --prod
```

## Contributing

Contributions are welcome! Please read our [Contribution Guidelines](CONTRIBUTING.md) before submitting a pull request.

### Steps to Contribute
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a pull request

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

## Support

For support, please [open an issue](https://github.com/climatex/climatex/issues) or contact support@climatex.com.

---

**Built with ❤️ for Climate-Conscious Innovators**