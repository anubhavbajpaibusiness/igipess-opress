# IGIPESS Voicebox

Anonymous complaint & suggestion box for the Indira Gandhi Institute of
Physical Education & Sports Sciences (IGIPESS), University of Delhi —
Students' Union, 2026–27.

Static frontend in `public/`, three serverless API routes in `api/`, shared
auth helper in `lib/`, and data stored in Upstash Redis. Everything is
namespaced under `du:igipess:voicebox` so the same Upstash instance can be
shared safely with the Aditi Mahavidyalaya deployment.

---

## Deploy in 5 minutes

### 1. Push to GitHub

```bash
git init
git add .
git commit -m "igipess-voicebox"
git branch -M main
git remote add origin https://github.com/anubhavbajpaibusiness/igipess-opress.git
git push -u origin main
