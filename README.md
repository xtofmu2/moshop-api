# WhatsApp HTTP API

A memory-optimized WhatsApp HTTP API server that supports multiple sessions and message queuing.

## Features

- 🚀 Lightweight and fast
- 💾 Memory optimized
- 👥 Multiple session support
- 📨 Message queuing
- 🔒 Rate limiting
- 📝 Swagger documentation
- 🐳 Docker support

## Quick Start

### Using Docker (Recommended)

```bash
# Clone the repository
git clone https://github.com/yourusername/whatsapp-api.git
cd whatsapp-api

# Copy environment file
cp .env.example .env

# Start with Docker
docker-compose up -d
```

### Manual Installation

```bash
# Install dependencies
npm install

# Start the server
npm start
```

## API Documentation

Once the server is running, visit:
- http://localhost:3000/api-docs

## Configuration

Edit `.env` file to configure:
- Port number
- API key
- Session limits
- Rate limiting
- Webhook URLs

## Commands

```bash
# Development
npm run dev

# Production
npm start

# Docker commands
npm run docker:build
npm run docker:start
npm run docker:stop
```

## Support

- Create an issue for bug reports
- Pull requests are welcome

## License

MIT License