# 🚀 Sathiyamoorthy M — 3D Portfolio (React + TypeScript + Three.js)

A 3D developer portfolio, personalized for **Sathiyamoorthy M (Sathya)** — Aspiring AWS Cloud & DevOps Engineer.

---

## 🚀 Getting Started

### 1) Install
```
npm install
```

### 2) Run locally
```
npm run dev
```

### 3) Build for production
```
npm run build
```

---

## ✅ Already done for you
- Name, title, bio, experience, and contact info updated in `src/config.ts`
- 5 projects added: Thulir, AWS 3-Tier Web App, Terraform IaC, Serverless Backup, CI/CD Pipeline on EC2
- Skills reframed around AWS + DevOps tooling
- Page title, loading screen, navbar, and AI-chatbot persona updated
- Old developer's personal photo removed and replaced with a placeholder image

## 📝 Still to do before you launch this
1. **Add your own photo** — replace these two files with your real photo (same filenames, so no code changes needed):
   - `public/images/mypicnbg.png`
   - `public/images/mypic.jpeg`
2. **Project images** — each of the 5 projects now has a custom architecture diagram (SVG) instead of a blank placeholder. Feel free to replace them with real screenshots later:
   - `public/images/thulir.svg`
   - `public/images/aws-3tier.svg`
   - `public/images/terraform-iac.svg`
   - `public/images/serverless-backup.svg`
   - `public/images/cicd-pipeline.svg`
3. **Resume button** — the "RESUME" button in the navbar (`src/components/SocialIcons.tsx`) currently links to `#`. Point it to your resume PDF (e.g. host it in `public/` and link to `/resume.pdf`).
4. **AI chatbot (optional feature)** — the "Play" page has a chess game + AI chat that impersonates you, powered by Groq's API. It needs a `GROQ_API_KEY` environment variable (see `.env.example`) to work. If you don't want this feature, you can skip setting the key — the rest of the site works fine without it.
5. **Deploy** — this is a Vite + React app, ready for Vercel (a `vercel.json` is already included) or Netlify.

---

## 🧰 Tech Stack
React · TypeScript · Three.js / WebGL · GSAP · Vite

## 🪪 License
MIT License (inherited from the original template) — see [LICENSE](./LICENSE).
