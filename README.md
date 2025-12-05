# Nimbus-Arc

A Next.js 3D keyboard customization experience built with React Three Fiber, Prismic CMS, and Three.js.

## Features

- 🎨 Interactive 3D keyboard visualization
- ⌨️ Customizable keycaps with multiple textures
- 🎵 Mechanical keyboard sound effects
- 🌐 Content managed via Prismic CMS
- ⚡ Built with Next.js 16 and React 18

## Tech Stack

- **Framework**: Next.js 16 (App Router)
- **3D Graphics**: Three.js, React Three Fiber, React Three Drei
- **CMS**: Prismic
- **Styling**: Tailwind CSS
- **Language**: TypeScript

## Getting Started

First, install dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
src/
├── app/              # Next.js app router pages
├── components/       # React components (Keycap, Keyboard, etc.)
├── slices/          # Prismic slice components
└── prismicio.ts     # Prismic configuration
```

## 3D Assets

The project includes custom 3D models:
- Keyboard base (`keyboard.gltf`)
- Individual keycaps (`keycap.gltf`)
- Mechanical switches (`switch.gltf`)

## Sound Effects

Multiple mechanical keyboard switch sounds are included for different switch types:
- Cherry MX Black
- Cherry MX Blue
- Cherry MX Brown
- Cherry MX Red

## Development

To work with Prismic CMS:

```bash
npm run slicemachine
```

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [React Three Fiber](https://docs.pmnd.rs/react-three-fiber)
- [Prismic Documentation](https://prismic.io/docs)

## License

MIT
