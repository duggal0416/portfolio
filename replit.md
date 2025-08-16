# Overview

BranchArc is a premium e-commerce website specializing in exotic trees and landscape plants. The application showcases a curated collection of rare olive trees, topiaries, and flowering plants with detailed product information, care instructions, and pricing. Built as a full-stack web application, it features a modern React frontend with a Node.js/Express backend, designed to provide an elegant shopping experience for landscape enthusiasts and professionals.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern development
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack Query for server state management and React Context for cart state
- **UI Components**: Shadcn/ui component library with Radix UI primitives for accessibility
- **Styling**: Tailwind CSS with custom design tokens for consistent theming
- **Build Tool**: Vite for fast development and optimized production builds

## Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript for type safety across the stack
- **API Design**: RESTful API with structured error handling and logging
- **Session Management**: Express sessions for cart persistence
- **Development**: Hot module replacement with Vite integration in development mode

## Data Storage Solutions
- **Database**: PostgreSQL configured via Drizzle ORM
- **Schema Management**: Drizzle Kit for migrations and schema management
- **Development Storage**: In-memory storage implementation for rapid prototyping
- **Database Provider**: Neon serverless PostgreSQL for production deployment

## External Dependencies

### Core Framework Dependencies
- **@tanstack/react-query**: Server state management and caching
- **wouter**: Lightweight React router
- **drizzle-orm**: Type-safe SQL ORM for PostgreSQL
- **@neondatabase/serverless**: Serverless PostgreSQL driver

### UI and Styling
- **@radix-ui/***: Comprehensive set of unstyled, accessible UI primitives
- **tailwindcss**: Utility-first CSS framework
- **shadcn/ui**: Pre-built component library built on Radix UI
- **lucide-react**: Modern icon library

### Form and Validation
- **react-hook-form**: Performant form library with validation
- **@hookform/resolvers**: Validation resolvers for react-hook-form
- **zod**: TypeScript-first schema validation
- **drizzle-zod**: Integration between Drizzle ORM and Zod validation

### Development Tools
- **vite**: Fast build tool and development server
- **tsx**: TypeScript execution for Node.js
- **esbuild**: Fast JavaScript bundler for production builds
- **@replit/vite-plugin-runtime-error-modal**: Development error overlay for Replit environment