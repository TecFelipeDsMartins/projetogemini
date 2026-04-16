# GEMINI.md

## Project Overview
This is a minimal base Next.js application designed as a starting point for further development. It uses the App Router, TypeScript, and Vanilla CSS (CSS Modules).

### Tech Stack
- **Framework**: Next.js 15+
- **Language**: TypeScript
- **Styling**: Vanilla CSS / CSS Modules
- **Directory Structure**: `src/` directory pattern
- **Repository**: [https://github.com/TecFelipeDsMartins/projetogemini.git](https://github.com/TecFelipeDsMartins/projetogemini.git)

## Building and Running
- **Development**: `npm run dev`
- **Build**: `npm run build`
- **Production Start**: `npm run start`
- **Linting**: `npm run lint`

## Project Structure
- `src/app/`: Contains the App Router routes and layouts.
- `src/app/globals.css`: Global styles and CSS variables.
- `public/`: Static assets.

## Development Conventions
- **Components**: Create reusable components in a `src/components/` directory (to be created as needed).
- **Styling**: Use CSS Modules (`*.module.css`) for component-specific styles.
- **Strict Types**: Maintain TypeScript strict mode for better code quality.
- **Git Flow**: All changes should be committed with clear, descriptive messages and pushed to the `main` branch.

## Usage
1. Install dependencies (if not already done): `npm install`
2. Start the development server: `npm run dev`
3. Begin building your application logic in `src/app/`.
