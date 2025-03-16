# Express.js TypeScript Project Created with Vratix

## Features

- Express.js with TypeScript
- Common Error objects
- Error middleware
- Response object for structured API responses
- Test configuration and coverage using Vitest 
- Common scripts to run and test your APIs
- Hot-reloading for development

## Prerequisites

- Node.js 20 or higher
- npm, pnpm or yarn
- Docker (optional)

## Getting Started

### Local Development

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev:local
```

The server will start on `http://localhost:3000` with hot-reloading enabled.

### Production Build

```bash
npm run build:prod
npm run prod:serve
```

## Scripts

- `npm run dev:local` - Start local development server with hot-reload
- `npm run build:prod` - Build for production
- `npm run prod:serve` - Run production server
- `npm run test` - Run tests
- `npm run coverage` - Run tests with coverage report

## License

[MIT](./LICENSE)
