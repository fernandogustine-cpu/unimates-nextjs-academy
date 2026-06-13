# Uni-Mates Phase 5 Deployment Guide

1. Upload all files and folders to GitHub:
   - app/
   - components/
   - lib/
   - supabase/
   - docs/
   - package.json
   - next.config.js
   - .env.example
   - .gitignore
   - README.md

2. In Vercel, import the GitHub repository.

3. Add Environment Variables:
   - NEXT_PUBLIC_SUPABASE_URL
   - NEXT_PUBLIC_SUPABASE_ANON_KEY

4. Deploy.

5. Open:
   - /login
   - /dashboard
   - /courses
   - /puzzles
   - /videos
   - /pgn
   - /tournaments
