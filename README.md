# Tutor Dashboard (Standalone)

This folder is a standalone Next.js app containing only the Tutor Dashboard module.

## Local Run

1. `npm install`
2. `npm run dev`
3. Open `http://localhost:3000/tutor-dashboard`

## Deploy To Vercel

1. Push this project to GitHub/GitLab/Bitbucket.
2. Import the repository in Vercel.
3. Keep defaults:
   - Framework: `Next.js`
   - Build Command: `npm run build`
   - Output: auto-detected
4. Deploy.

Optional CLI deploy:

```bash
npm i -g vercel
vercel
vercel --prod
```

## Deploy With Docker

Build image:

```bash
docker build -t tutor-dashboard .
```

Run container:

```bash
docker run -p 3000:3000 tutor-dashboard
```

Then open `http://localhost:3000/tutor-dashboard`.

## Included Deployment Files

- `.gitignore`
- `.dockerignore`
- `Dockerfile`
- `vercel.json`
