# Project Guidelines & Rules

## 1. Project Overview & Tech Stack
- **Framework / Bundler:** Vite (Vanilla JS)
- **Deployment:** GitHub -> Netlify (Build command: `npm run build`, Publish directory: `dist`)

## 2. File Organization & Code Separation
- **Code Separation:** HTML, CSS, and JavaScript must be kept strictly in separate files.
- **Directory Structure:**
  - Root: [index.html](file:///c:/Users/user/Desktop/코딩/GitHub/test261027/index.html)
  - CSS files: Must be located in `src/` (e.g., `src/style.css` or component-specific CSS in `src/`)
  - JS files: Must be located in `src/` (e.g., `src/main.js`)
  - Static assets: Located in `public/` or `src/assets/`

## 3. Dependency Management
- **External Libraries:** All JavaScript libraries must be installed via `npm install <package-name>` (never loaded directly via external CDN `<script>` tags unless explicitly requested).

## 4. Build & Deployment Rules (Netlify)
- Ensure all asset paths and import paths are compatible with Vite's production build.
- Build artifacts output to `dist/`.
