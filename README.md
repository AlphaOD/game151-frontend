# Game 151 Frontend

This is the frontend monorepo for Game 151, containing the web and native applications, as well as shared components.

## Project Structure

- `web/` - Next.js web application
- `native/` - React Native mobile application
- `shared/` - Shared components and utilities

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm 9 or later
- For native development:
  - Xcode (for iOS)
  - Android Studio (for Android)

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

To start the web application:
```bash
npm run dev:web
```

To start the native application:
```bash
npm run dev:native
```

### Building

To build the web application:
```bash
npm run build:web
```

To build the native application:
```bash
npm run build:native
```

### Testing

Run tests for all packages:
```bash
npm test
```

### Linting

Run linting for all packages:
```bash
npm run lint
```

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Run tests and linting
4. Submit a pull request

## License

ISC 