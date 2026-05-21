# DISC — One Worded by Miniscripter

A single-track music player. Spinning CD, minimal design, deploys to Vercel in seconds.

## Repo structure

```
/
├── index.html   ← the entire site
├── vercel.json  ← deploy config
├── track.mp3    ← YOUR audio file (add this yourself)
└── README.md
```

## Setup

1. **Add your audio** — rename your file to `track.mp3` and drop it in the repo root.  
   *(FLAC? Change `src="track.mp3"` and the vercel.json Content-Type to `audio/flac`)*

2. **Deploy** — connect this repo on [vercel.com/new](https://vercel.com/new) and hit Deploy.

## Controls

| Input | Action |
|-------|--------|
| Click ▶ | Play / Pause |
| Click ⏮ | Restart track |
| Click progress bar | Seek |
| `Space` | Play / Pause |
| `↑` / `↓` | Volume |
