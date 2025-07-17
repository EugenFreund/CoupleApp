# CoupleApp

A cross-platform app for couples to manage tasks, communicate, and share experiences.

## Features (Planned)

- **Shared Task Lists** - Manage daily tasks together
- **Private Messenger** - Secure communication between partners  
- **Photo Collection** - Shared memories in one place
- **Mood Status** - Share how you're feeling with your partner
- **Trip Planning** - Plan adventures together

## Getting Started

### Prerequisites

- **Node.js**: Version 18 or later (required for LynxJS)
- **npm**: Comes with Node.js
- **Lynx Explorer**: For testing the app (iOS Simulator or Android)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/EugenFreund/CoupleApp.git
cd CoupleApp
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Scan the QR code in the terminal with your Lynx Explorer app to see the result.

### Project Structure

- `src/`: Source code for the app
- `docs/`: Project documentation
  - `project-context.md`: Project vision and roadmap
  - `tech-documentation.md`: Technical resources and links
  - `interaction-guidelines.md`: Development guidelines
- Configuration files for TypeScript, Biome, Prettier, and Vitest

## Development

Start editing the app by modifying `src/App.tsx`. The app auto-updates as you edit files.

## Tech Stack

- **Framework**: [LynxJS](https://lynxjs.org/) - JavaScript framework for native apps
- **Language**: TypeScript
- **Build Tool**: Rspeedy (Rspack-based)
- **Testing**: Vitest + ReactLynx Testing Library
- **Code Quality**: Biome + ESLint + Prettier

## Contributing

This is a personal project, but suggestions and feedback are welcome!

## License

This project is licensed under the MIT License.
