# Ved Notes

Ved Notes is a feature-rich, cross-platform desktop note-taking application built with Electron, React, and TypeScript. It provides a clean, intuitive interface for creating and organizing notes with powerful editing capabilities.

## Features

- **Rich Text Editing**: Create notes with formatting options including bold, italic, underline, strikethrough, and code formatting
- **Multiple List Types**: Support for bullet lists, numbered lists, and task lists with checkboxes
- **Link Integration**: Easily add hyperlinks to your notes
- **Themed Notes**: Choose from multiple color themes for personalizing your notes
- **Pin Important Notes**: Keep important notes easily accessible
- **Searchable Notes**: Quickly find notes by title or content
- **Cross-Platform**: Available for Windows, macOS, and Linux

## Technology Stack

- **Electron**: Cross-platform desktop application framework
- **React**: Modern UI library for building interactive interfaces
- **TypeScript**: Strongly typed programming language for better code quality
- **Tiptap**: Headless rich text editor
- **Tailwind CSS**: Utility-first CSS framework for styling
- **SQLite**: Local database for storing notes
- **Zustand**: Lightweight state management solution

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Project Setup

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

```bash
$ npm install
```

### Development

To run the application in development mode:

```bash
$ npm run dev
```

### Building for Production

```bash
# For Windows
$ npm run build:win

# For macOS
$ npm run build:mac

# For Linux
$ npm run build:linux
```

## Project Structure

```
src/
├── common/          # Shared types and utilities
├── main/            # Electron main process code
├── preload/         # Preload scripts for secure IPC
├── renderer/        # React frontend application
│   ├── components/  # Reusable UI components
│   ├── pages/       # Application pages
│   ├── store/       # State management
│   └── hooks/       # Custom React hooks
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.