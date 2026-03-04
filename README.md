# Next.js Application

This is a modern web application built with Next.js, featuring the latest technologies and best practices.

## Technologies Used

- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Geist Font** - Modern font optimization

## Features

- Server-side rendering (SSR) and static site generation (SSG)
- File-based routing system
- API routes
- Built-in CSS support
- Image optimization
- Font optimization
- Fast Refresh development experience

## Project Structure

```
├── app/                    # Next.js App Router pages
│   ├── favicon.ico         # Favicon
│   ├── globals.css         # Global styles
│   ├── layout.tsx          # Root layout
│   └── page.tsx            # Home page
├── public/                 # Static assets
│   ├── file.svg
│   ├── globe.svg
│   ├── next.svg
│   ├── vercel.svg
│   └── window.svg
├── package.json            # Dependencies and scripts
├── next.config.ts          # Next.js configuration
├── tsconfig.json           # TypeScript configuration
├── postcss.config.mjs      # PostCSS configuration
└── eslint.config.mjs       # ESLint configuration
```

## Getting Started

### Prerequisites

- Node.js (v18.17 or newer)
- npm, yarn, pnpm, or bun

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

### Development Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Environment Variables

Create a `.env.local` file in the root directory to define environment variables:

```
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

## Deployment

### Vercel

The easiest way to deploy this application is with [Vercel](https://vercel.com), the creators of Next.js:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/your-repo)

### Other Platforms

This application can also be deployed to other platforms that support Next.js, such as Netlify, AWS, or any hosting provider that supports Node.js applications.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.
