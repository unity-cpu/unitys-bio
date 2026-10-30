# unity profile (halo.rip clone)

Static recreation of [halo.rip/unity](https://halo.rip/unity) ready for Vercel.

## Deploy to Vercel

### Option 1 – CLI
```bash
cd unity-profile
npx vercel
```

### Option 2 – Drag & drop
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag the entire `unity-profile` folder
3. Deploy

### Option 3 – Git
```bash
git init
git add .
git commit -m "unity profile"
# push to GitHub then import on Vercel
```

## Local preview
Just open `index.html` in a browser, or:
```bash
npx serve .
```

## Customize
- Replace `avatar.png`, `decoration.png`, `cover.jpg`, `bg.mp4`
- Edit bio / username in `index.html`
- Add a real audio file and set `<audio src="track.mp3">` if you want actual music
