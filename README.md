# ARGUS × NRL 2026

> **Built to think. Engineered to compete.**

Official website for **ARGUS** (Team 012 / Delhi Regional #298), a school robotics team from Dr. B.R. Ambedkar School of Specialized Excellence (CM SHRI School, Sector 11, Rohini, Delhi). Delhi Regional Champions heading to the National Robotics League (NRL) National Finals in Mumbai, December 2026.

Live deployment: [argusnrl.vercel.app](https://argusnrl.vercel.app)

---

## Highlights

- **Scroll-driven 3D Robot Tour:** Powered by `<model-viewer>` for real CAD model (`assets/argus-robot.glb`) with 6 spec stops and viewpoint tweening.
- **Interactive Field Explorer:** 21:9 wide stage featuring the HYPERDRIVE 2026 arena (`assets/hyperdrive-field.glb`) with hotspots for High Poles, Star Poles, Drop Zone, Payload Bay, and LEVEL UP.
- **Recreated Finals Scoreboard:** Recreating the finals match at Thyagaraj Stadium (Blue Squad 106 vs Red Squad 25, 2-0 Finals sweep, Brand Builder Award).
- **Live Countdown Timer:** Ticking down to the National Finals on 12 December 2026 at VJTI, Mumbai.
- **Authentic Media Archive:** 15 high-res photos from the Regional Win at Thyagaraj Stadium, build room lab sessions, and CAD milestones with interactive lightbox.
- **Brutalist Editorial Design:** Strict brand system using Black (`#000000`), Violet (`#7D39EB`), Lime (`#C6FF33`), and White (`#FFFFFF`), with Big Shoulders Stencil Display and JetBrains Mono typography.

---

## Project Structure

```
.
├── index.html                           # Root site (fully responsive, standalone)
├── vercel.json                          # Vercel configuration (clean URLs & caching)
├── assets/
│   ├── argus-robot.glb                  # Real 3D CAD model (12.0 MB)
│   ├── hyperdrive-field.glb             # Real 3D Field model (48.8 MB)
│   ├── robot-poster.jpg                 # Robot viewer fallback poster
│   ├── field-poster.jpg                 # Field viewer fallback poster
│   └── images/
│       ├── argus_favicon.png
│       ├── argus_emblem.jpg
│       ├── argus_robot_clean.jpg
│       ├── argus_robot_cad.jpg
│       ├── argus_team_lab.jpg
│       ├── argus_programming.jpg
│       └── regional-win/                # 15 Thyagaraj Stadium win photos
└── argus/                               # Synchronized deployment mirror
    ├── index.html
    ├── vercel.json
    └── assets/
```

---

## License & Credits

National Robotics League 2026 © ARGUS 2026.
Team 012 // Delhi Regional #298 // CM SHRI Rohini.
