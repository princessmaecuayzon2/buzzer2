# 🇵🇭 PH History Buzzer — Sprint Retro Icebreaker

## Setup Steps

### 1. Enable Pusher Client Events
1. Go to pusher.com → your app → **App Settings**
2. Enable **"Enable client events"** → Save

### 2. Deploy to Vercel
Option A — Drag & drop (easiest):
- Go to vercel.com → New Project → drag this folder

Option B — CLI:
```
npm i -g vercel
vercel deploy
```

### 3. How to Play
1. **Host** opens `your-url.vercel.app/host.html`
2. Host enters session name → clicks **Create Session**
3. Share the **Player Link** shown on screen to teammates (via Teams chat)
4. Players open the link → enter name → Join Game
5. Host clicks **Start Game** when everyone is in
6. Players see a big 🔔 **BUZZ** button — first to buzz appears on host screen
7. Host calls the 1st buzzer by name → they say their answer
8. Host clicks **Reveal Answer**
9. Repeat for all 10 questions!

### Files
- `host.html` — Host view (share your screen)
- `player.html` — Player view (everyone opens this on their phone/laptop)
- `vercel.json` — Vercel routing config
# buzzer2
