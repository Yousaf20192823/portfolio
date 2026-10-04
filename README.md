# Yousaf Khan | Lights Out

Portfolio of Yousaf Khan, full-stack engineer (Angular, .NET, IoT) in Bahrain.

Visitors drive an F1 car around a night-race circuit at Sakhir. Each of the 13 sector gates opens a chapter of my career: education, Optimum ERP at Amthal Group, case studies, side projects and skills. Crossing the line with every sector collected shows contact details and a commit heatmap. A plain scrolling view is one click away for anyone who just wants to read.

## Run locally

It is a single static page, no build step:

```
npx serve .
```

Then open the printed URL. Opening `index.html` directly from disk also works in Chrome and Edge.

## Controls

| Key | Action |
| --- | --- |
| W A S D / arrows | Drive |
| Shift / Space | DRS boost (uses ERS) |
| C | Camera (chase, T-cam, helicopter) |
| P | Autopilot |
| M | Engine sound |
| R | Back on track |

On phones, on-screen pedals and steering appear automatically.

## Stack

Three.js (WebGL, bloom post-processing), vanilla JS and CSS, Phosphor icons, Anton and Geist fonts. Deploys as a static site (Vercel, Netlify, GitHub Pages).
