# Lemona Hub 🎨

> Everything in Lemona Hub

A modern Next.js application that powers **Melody**, an AI-powered creative assistant platform. Create stunning images, videos, music, and more with cutting-edge AI tools—all from a single, seamless interface.

![Melody Interface](Oniooo_screenshot%201.png)

## ✨ Features

- **AI Chat Assistant** - Interactive conversation interface powered by real-time WebSocket communication
- **Image Generation** - Create beautiful images from text descriptions
- **Video Generation** - Generate videos with AI-powered tools
- **Music Creation** - Compose and generate music tracks
- **File Support** - Upload and process various file types (audio, PDF, images)
- **Payment Integration** - Stripe-powered payment system with Mochi credits
- **Authentication** - Google OAuth integration for secure access
- **Real-time Chat** - Socket.io powered chat interface for instant responses

![Chat Interface](Oniooo_screenshot%202.png)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd oniooo-client
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory with the following variables:
```env
NEXT_PUBLIC_PRODUCTION_BACKEND_URL=your-production-backend-url
NEXT_PUBLIC_DEVELOPMENT_BACKEND_URL=your-development-backend-url
BACKEND_PORT=8080
API_VERSION=v1
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

![Melody Features](Oniooo_screenshot%203.png)

## 🛠️ Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Redux Toolkit
- **Real-time**: Socket.io Client
- **Authentication**: Supabase Auth + Google OAuth
- **Payments**: Stripe
- **File Storage**: AWS S3 / Google Cloud Storage
- **UI Components**: Material-UI, Framer Motion

## 📁 Project Structure

```
oniooo-client/
├── src/
│   ├── app/              # Next.js app router pages
│   │   ├── melody/       # Main Melody chat interface
│   │   ├── shop/         # Mochi marketplace
│   │   └── api/          # API routes
│   ├── components/       # React components
│   │   ├── melody/      # Melody-specific components
│   │   ├── auth/        # Authentication components
│   │   └── modals/      # Modal components
│   ├── contexts/        # React contexts
│   ├── lib/             # Utility functions and types
│   └── utils/           # Helper utilities
├── public/              # Static assets
└── package.json
```

## 🎯 Key Components

- **MelodyInterface** - Main chat interface component
- **ChatSocketContext** - Real-time WebSocket connection management
- **AuthContext** - Authentication state management
- **FileUpload** - Multi-file upload with preview
- **MessageList** - Chat message rendering with markdown support

## 🧪 Development

```bash
# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linter
npm run lint
```

## 📝 License

This project is private and proprietary.

## 🤝 Contributing

This is a private project. For questions or support, please contact the development team.

---

Built with ❤️ by the Oniooo team
