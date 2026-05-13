# ChromaLens

ChromaLens is a camera-based color recognition web app that helps users identify real-world colors from a live camera feed. It uses the Image Capture API and Canvas API to sample pixel data, convert RGB values to hex colors, and fetch human-readable color names.

## Live Demo

Demo: [https://chroma-lens-iota.vercel.app/](https://chroma-lens-iota.vercel.app/)

## Features

- Live camera capture using the browser Image Capture API
- Pixel-level color extraction with Canvas `getImageData`
- RGB-to-hex conversion and color-name lookup
- Cached color-name results to reduce repeated API calls
- Reusable Vue components with Storybook stories
- Clipboard support for copied hex values

## Tech Stack

- Vue 3
- TypeScript
- Vite
- Tailwind CSS
- Canvas API
- Image Capture API
- Storybook

## Local Installation

Install dependencies:

```bash
yarn install
```

Run the development server:

```bash
yarn dev
```

Run Storybook locally:

```bash
yarn storybook
```

## References

- [Take photos and control camera settings](https://developer.chrome.com/blog/imagecapture)
- [CanvasRenderingContext2D: getImageData() method](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/getImageData)
