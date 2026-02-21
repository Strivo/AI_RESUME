## AI Resume Builder

A React + Vite project for building AI-assisted resumes. Maintained by kcee tech (https://kceetech.com).

Prerequisites:

- Node.js 18+ and `npm` installed

Environment variables (create a `.env` file in the project root):

- `VITE_GOOGLE_AI_API_KEY` — (optional) Google Generative AI key for advanced features
- `VITE_API_BASE_URL` — (optional) API base URL for saving/loading resumes (e.g., Strapi)
- `VITE_STRAPI_API_KEY` — (optional) API key for Strapi if used

Install dependencies:

```
npm install
```

Run in development:

```
npm run dev
```

Build for production:

```
npm run build
```

Preview the production build locally:

```
npm run preview
```

How to use locally:

1. Clone or download the project into a local folder.
2. Create a `.env` file with the environment variables above (optional features will be disabled without keys).
3. Run `npm install` to install dependencies.
4. Run `npm run dev` and open the URL shown in the terminal (typically `http://localhost:5173`).
5. Use the UI to create, edit, and export resumes. If you want persistence, point `VITE_API_BASE_URL` at a Strapi or similar backend and supply `VITE_STRAPI_API_KEY`.

Notes:

- All external links in this repository have been replaced with `https://kceetech.com` per project attribution.
- If you rely on third-party APIs (Google Generative AI), ensure you add the correct API keys to `.env`.

Maintained by kcee tech — https://kceetech.com
