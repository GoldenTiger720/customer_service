# Loyalty Flow 87 - Customer Service Management System

A modern customer service management platform built with React, TypeScript, and Tailwind CSS. This application provides comprehensive tools for managing customer cases, campaigns, reports, and more.

## Getting Started

### Prerequisites

- Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

### Installation

```sh
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to the project directory
cd loyalty-flow-87

# Install dependencies
npm install

# Start the development server
npm run dev
```

The application will start in development mode and open at `http://localhost:5173`.

## Configuration

### Theme Settings

The application defaults to dark mode. Users can change the theme using the theme toggle in the application header. The theme preference is stored in local storage and persists across sessions.

To modify the default theme, edit the `defaultTheme` prop in `src/App.tsx`:

```tsx
<ThemeProvider defaultTheme="dark" storageKey="servicehub-theme">
```

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run typecheck` - Run TypeScript type checking

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## Features

- **Dashboard**: Overview of key metrics and performance indicators
- **Case Management**: Track and manage customer service cases
- **Customer Database**: Comprehensive customer information management
- **Campaign Management**: Create and monitor marketing campaigns
- **Reports & Analytics**: Generate detailed reports and insights
- **Template System**: Reusable templates for common workflows
- **Notifications**: Real-time notification system
- **Dark Mode**: Application defaults to dark mode for reduced eye strain

## What technologies are used for this project?

This project is built with:

- **Vite**: Fast build tool and development server
- **TypeScript**: Type-safe JavaScript
- **React**: UI library
- **shadcn-ui**: Modern component library
- **Tailwind CSS**: Utility-first CSS framework
- **React Router**: Client-side routing
- **Tanstack Query**: Data fetching and caching
- **Recharts**: Data visualization library
