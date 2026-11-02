# Taimoor Mateen Portfolio

Complete source export of the published portfolio, including the restored mint background and hover effects.

## Project structure
- dist/index.html: complete page markup, styles, animations, and JavaScript.
- dist/assets/: workflow screenshots, hotel demo video, and downloadable CV.
- .openai/hosting.json: original Sites hosting configuration, retained unchanged.
- vercel.json: Vercel static deployment configuration.

This is a buildless static HTML/CSS/JavaScript project. There are no separate framework components, package dependencies, or build commands. Fonts are loaded from Google Fonts as in the live website, requiring an internet connection.

## Upload manually to GitHub
1. Extract this ZIP.
2. Create a GitHub repository.
3. Select Add file > Upload files.
4. Upload the extracted contents, including the dist folder and vercel.json, then commit. Do not upload the ZIP itself.

## Deploy on Vercel
1. Add New > Project, then import the GitHub repository.
2. Select Other as the framework preset.
3. Keep the repository root as the Root Directory.
4. Leave Build Command empty and set Output Directory to dist.
5. Deploy. No environment variables or install command are required.

## Preview locally
Run python -m http.server 8000 --directory dist from the project folder, then open http://localhost:8000.

All original tracked project files are included byte-for-byte unchanged. Only this README and vercel.json were added to the export. Exported source commit: 29aa64d21347f1d0b39c0e572a5ef0b0086114ef.
