# VR 3D Gallery

React + @react-three/fiber VR galerija su WebXR. Pirmasis įkeltas paveikslas dedamas ant įėjimo durų, kiti – ant sienų. Yra pavadinimai (naudojami failų vardai).

## Vystymas lokaliai
```bash
npm install
npm run dev
```

## Diegimas į Vercel
1. Sukelkite šį projektą į GitHub (New repository → upload files arba `git`).
2. Vercel: "New Project" → importuojate repo → "Framework Preset: Vite".
3. Build komandą palikite `vite build`, o Output dir: `dist`.
4. Deploy → gavę URL, atverkite – „Enter VR“ mygtukas atsiras apačioje.

## Diegimas į Netlify
- New site from Git → pasirinkite repo.
- Build command: `vite build`
- Publish directory: `dist`
- Deploy.

## Naudojimas
- Spauskite „📤 Įkelti paveikslus“ ir pasirinkite JPG/PNG/WEBP.
- Pirmasis failas – ant įėjimo durų. Likę – ant sienų.
- WASD + pelė judėjimui; „Esc“ – išeiti iš pointer lock.
- „Enter VR“ – įeiti į VR režimą (palaikomuose įrenginiuose).
