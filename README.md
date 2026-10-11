# Vayani Accessories Store

React + Vite frontend, Firebase (Auth + Firestore) backend, Cloudinary for images.

## Run locally
    npm install
    npm run dev

## Build
    npm run build

## Deploy (Vercel)
1. Push this folder to GitHub (make sure the `src` folder is included).
2. Vercel -> Add New Project -> import the repo (Framework: Vite, Build: `npm run build`, Output: `dist`).
3. Firebase Console -> Authentication -> Settings -> Authorized domains -> add your `*.vercel.app` domain.
4. Firebase Console -> Firestore -> Rules -> paste `firestore.rules` and Publish.
5. Make your own account admin: Firestore -> `users/<your uid>` -> set `role` = `admin`, `status` = `active`.
