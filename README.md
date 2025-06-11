# Image Server

A simple static image server built with Vite and React, designed to be deployed on Netlify.

## Project Structure

```
image-server/
├── public/           # Place your images here
│   ├── image.0.png
│   ├── image.1.png
│   └── ...
├── src/             # Source code
└── package.json     # Project configuration
```

## How to Use

1. Place your images in the `public` folder with the naming convention `image.{number}.png`
2. Images will be accessible at `https://your-site.netlify.app/image.{number}.png`

## Development

```bash
npm install
npm run dev
```

## Deployment to Netlify

1. Push your code to a GitHub repository
2. Go to [Netlify](https://www.netlify.com/)
3. Click "New site from Git"
4. Choose your repository
5. Deploy settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
   - Node version: 18 (or latest LTS)

## Updating Images

1. Add new images to the `public` folder
2. Commit and push to GitHub
3. Netlify will automatically deploy the changes

## Accessing Images

Once deployed, your images will be available at:
- `https://your-site.netlify.app/image.0.png`
- `https://your-site.netlify.app/image.1.png`
- etc.
