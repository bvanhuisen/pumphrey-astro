Pumphrey Astro drop-in files

This ZIP is designed to be extracted into the root of the Astro project folder:
C:\Users\HP\pumphrey-astro

It contains:
- src/layouts/BaseLayout.astro
- src/components/*.astro
- src/pages/index.astro
- src/styles/global.css
- public/images/*.jpg
- reference/dark-index.html

After extracting with overwrite enabled, keep your existing Astro dev server running or run:
npm run dev

Then open:
http://localhost:4321/

To test production build:
npm run build
