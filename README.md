# ClipFree

A mobile-friendly starter website for creating vertical clips from uploaded videos.

## Run locally
Requires Docker. In this folder run:
`docker compose up --build`
Then open http://localhost:8000

## Deploy
Push this folder to a GitHub repository, then create a Render Web Service from that repository using the included Dockerfile. Set the health check path to `/api/health`.

## Current limits
- Social links are recognized but videos are not downloaded from YouTube, TikTok, Facebook, or Instagram. Upload an original video file you own or have permission to edit.
- Clips are evenly spaced segments, not AI-selected highlights.
- This is a starter project, not production-ready. It has no accounts, database, persistent storage setup, job queue, upload quotas, rate limits, automatic file cleanup, or abuse protection. Configure persistent storage and security before public use.
