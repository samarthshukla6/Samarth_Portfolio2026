# Samarth Shukla

Personal portfolio of [Samarth Shukla](https://www.linkedin.com/in/samarthshuklacmu), Software and AI Engineer and Master's student in Software Engineering (Scalable Systems) at Carnegie Mellon University, School of Computer Science.

**Live site:** [https://samarth-portfolio2026.vercel.app/](https://samarth-portfolio2026.vercel.app/)

The site keeps the original Samnics 3D look: Three.js scenes, GSAP and ScrollMagic scroll, audio, and Blender models. Copy, sections, and layout are the portfolio.

**Live stack:** Vite, Three.js, GSAP, ScrollMagic, Draco-compressed GLB models.

## What's on the page

- **Home** — 3D bot, name, CMU SCS, resume
- **About** — software systems, AI/ML pipelines, research
- **Major Projects** — WebGPU Studio, Robo Claw, HealthX, DisasterX, SOLO Export
- **Experience** — Solo Tech, GMADP, Youngovator, plus the stack I work with
- **Publications** — SOLO-Export, HealthX(AI), SMOTE × XGBoost (IEEE / TechRxiv)
- **Honors** — hackathons, industry recognition, early academic
- **FAQ** and **footer** — email, phone, Pittsburgh, GitHub, LinkedIn, resume

## Run locally

```bash
npm install
npm run dev
```

Then open the URL Vite prints (usually `http://localhost:5173/`).

```bash
npm run build
npm run preview
```

`npm run host` exposes the dev server on the local network.

## Layout

| Path | Role |
| --- | --- |
| `index.html` | Page structure and copy |
| `main.js` | Three.js scenes, loaders, scroll camera, audio |
| `styles/style1.css`–`style8.css` | Original Samnics visual language |
| `styles/style9.css` | Portfolio layout on top of that language |
| `public/models/` | `Bot.glb`, `trinity-anim.glb`, `pad9.glb` |
| `public/assets/` | Images, logos, audio |

Do not rename click-sound IDs (`click-1` …) or drop the loading manager. Those are wired in `main.js`.

## 3D experience

The original interactive pass is unchanged. Click the equalizer for audio. Hold Shift to fire the bot's weapons. Scroll to move the camera.

https://github.com/user-attachments/assets/220064e6-995d-4855-926d-e670460cd2fc

Models are compressed with [Draco](https://google.github.io/draco/).

## Contact

- Site: [samarth-portfolio2026.vercel.app](https://samarth-portfolio2026.vercel.app/)
- Email: [sshukla3@andrew.cmu.edu](mailto:sshukla3@andrew.cmu.edu)
- Phone: [+1 412-496-1208](tel:+14124961208)
- GitHub: [samarthshukla6](https://github.com/samarthshukla6)
- LinkedIn: [samarthshuklacmu](https://www.linkedin.com/in/samarthshuklacmu)
- Resume: [Google Doc](https://docs.google.com/document/d/1ZBS85Y52l5arwUwD2i-pHaReOGmp8wI58LFkM5EtHxg/edit?usp=drive_link)
