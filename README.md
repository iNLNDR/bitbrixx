<p align="center">
  <img src="icons/icon-192.png" width="96" alt="Bitbrixx icon">
</p>

<h1 align="center">BITBRIXX</h1>

<p align="center">
  <b>A pocket brick-game console with 10 games, 6 shell themes, an 8-bit soundtrack and a worldwide Top 20, playable right in your phone's browser.</b><br>
  No download, no account, no ads. It works offline once you've opened it.
</p>

<p align="center">
  <a href="https://YOUR-USERNAME.github.io/bitbrixx/"><b>▶ Play now</b></a> ·
  <a href="docs/MANUAL.md">How to play</a> ·
  <a href="#install-it-like-an-app">Install on your phone</a> ·
  <a href="#turn-on-the-top-20-leaderboard">Leaderboard setup</a>
</p>

<p align="center">
  <img src="docs/screenshots/themes.png" alt="Bitbrixx in all six shell themes" width="820">
</p>

---

## What's inside

Bitbrixx recreates the feel of the classic handheld brick games: a dot-matrix LCD with a score panel, chunky buttons and blocky sound effects. It's built to be played with your thumbs on a phone.

- **10 games in one console.** Switch between them from the menu.
- **A Top 20 leaderboard shared by everyone who plays.** No login: you just enter a name of up to 5 letters, like an arcade machine.
- **6 shell themes.** Clear, Ocean, Bubblegum, Lemon, Graphite (with a green backlight) and Mint.
- **An original 8-bit soundtrack.** It has a calm menu tune, a game tune that speeds up as you level up, and a mocking song when you lose.
- **A separate high score for each game,** saved on your device.
- **Speed and starting level** settings from 1 to 9, like the original consoles.
- **Offline play** after you install it to your Home Screen.

## The games

| # | Game | What you do |
|---|------|-------------|
| 1 | **Tetra** | Stack falling blocks and clear full lines. Shows a ghost preview of where the piece will land. |
| 2 | **Snake** | Eat the blinking dot, grow longer, and don't bite yourself. |
| 3 | **Breaker** | Bounce the ball and smash the brick wall. |
| 4 | **Racer** | Switch lanes to dodge oncoming cars. Hold **A** to go faster. |
| 5 | **Shooter** | Shoot down the brick rows before they reach you. |
| 6 | **Tennis** | Rally the ball past the computer's paddle. |
| 7 | **Flappy** | Tap to flap through the gaps in the pipes. |
| 8 | **Runner** | An endless runner: hop or double-jump over cacti, and duck under birds. |
| 9 | **Cross** | Move the frog across 14 lanes of traffic. |
| 10 | **Dodge** | Dodge the falling rocks for as long as you can. |

The full rules and controls for every game are in the **[Play Manual](docs/MANUAL.md)**.

## Top 20 leaderboard

| Got a top score? | Everyone's best |
|:---:|:---:|
| <img src="docs/screenshots/entry.png" width="240" alt="Entering a name for the leaderboard"> | <img src="docs/screenshots/board.png" width="240" alt="The Top 20 leaderboard"> |

- There's **one board for all 10 games**. Each entry shows the player's name, the game and the score.
- **To get on the board:** you need at least **500 points**. Once the board has 20 names, you have to **beat the lowest score on it**, so the bar keeps rising as people play.
- When a game ends with a qualifying score, you get to enter a name of up to **5 letters**. Use ▲▼ to pick each letter, ◀▶ to move, and **A** to save.
- Tap **TOP 20** on the menu to see the board at any time.
- If you play offline, your score is saved and uploads automatically the next time you're online.

*The leaderboard screenshot shows example names.*

## Controls at a glance

| Button | On the menu | In a game |
|--------|-------------|-----------|
| ◀ ▶ | Choose a game | Move |
| ▲ | Change speed (1–9) | Jump, flap, fire, or hard-drop (depends on the game) |
| ▼ | Change starting level (1–9) | Move down, soft-drop or duck |
| **A** | Start | Rotate, fire, jump or launch |
| START | Start | Pause or resume |
| SOUND | Switch between Music, SFX and Mute | Same |
| THEME | Change the shell colour | Same |
| TOP 20 | Show the leaderboard | – |
| EXIT | – | Back to the menu |
| **i** | About Bitbrixx | – |

You can also play on a computer keyboard: arrow keys, **Space** or **X** for A, **Enter** for START, **Esc** for EXIT, **S** for SOUND, **T** for THEME, **R** for TOP 20 and **I** for About.

## Themes

| Clear | Ocean | Bubblegum |
|:---:|:---:|:---:|
| <img src="docs/screenshots/theme-clear.png" width="240" alt="Clear theme"> | <img src="docs/screenshots/theme-ocean.png" width="240" alt="Ocean theme"> | <img src="docs/screenshots/theme-bubblegum.png" width="240" alt="Bubblegum theme"> |
| **Lemon** | **Graphite** | **Mint** |
| <img src="docs/screenshots/theme-lemon.png" width="240" alt="Lemon theme"> | <img src="docs/screenshots/theme-graphite.png" width="240" alt="Graphite theme"> | <img src="docs/screenshots/theme-mint.png" width="240" alt="Mint theme"> |

Tap **THEME**, or tap the little theme window next to the logo, to switch themes. The game remembers your choice.

## Install it like an app

### iPhone / iPad
1. Open the **Play now** link in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**.
3. Open Bitbrixx from your Home Screen. It runs full screen, and after the first launch it works offline.

### Android
1. Open the link in **Chrome**.
2. Tap **⋮**, then **Add to Home screen** or **Install app**.

> 🔊 **No sound on iPhone?** Tap any button once, because phones only allow sound after a touch. Then turn up the media volume. The bottom-right corner of the screen shows **MUSIC**, **SFX** or **MUTE**.

## Put it on GitHub Pages

1. Create a new **public** repository called `bitbrixx`.
2. Upload all the files from this folder to the root of the repository.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, then pick the **main** branch and the **/ (root)** folder, and save.
4. After a minute your game is live at `https://YOUR-USERNAME.github.io/bitbrixx/`.
5. Edit this README and replace `YOUR-USERNAME` with your GitHub username, so the **Play now** link works.

## Turn on the Top 20 leaderboard

The game runs without this. Until you set it up, the TOP 20 screen says the leaderboard is off. Turning it on takes about 10 minutes, using a free [Firebase](https://firebase.google.com/) database. The free plan has no time limit and is far bigger than this game needs.

1. Go to the **[Firebase console](https://console.firebase.google.com/)** and sign in with a Google account.
2. Click **Create a project** and name it `bitbrixx`. You can turn off Google Analytics, because the game doesn't need it.
3. In the left menu, open **Build → Firestore Database**, then click **Create database**. Pick a location near your players (for Indonesia, choose **asia-southeast2 (Jakarta)**). Start in **production mode**.
4. Open the **Rules** tab, delete everything there, paste in the contents of [`firebase/firestore.rules`](firebase/firestore.rules), and click **Publish**.
5. Click the **⚙ gear → Project settings**. Under **Your apps**, click the **web icon `</>`**, give the app any nickname, and register it. You don't need Firebase Hosting.
6. Firebase shows a block of code called `firebaseConfig`. Copy two values from it: **`apiKey`** and **`projectId`**.
7. On GitHub, open `index.html`, click the ✏️ edit button, and search for this line:
   ```js
   const LEADERBOARD = { projectId: '', apiKey: '' };
   ```
   Fill in your two values, for example:
   ```js
   const LEADERBOARD = { projectId: 'bitbrixx-1a2b3', apiKey: 'AIzaSy...' };
   ```
   Then **commit** the change. After a minute, the leaderboard is live for everyone.

**Is it safe to put the apiKey in a public repository?** Yes. A Firebase web key isn't a password: it only says which project to talk to. What players can do is controlled by `firestore.rules`, which only lets people **add** a score of 500 or more, with a 1–5 character name. Nobody can edit or delete scores except you, from the Firebase console.

**A note on cheating:** there's no login, so a determined person could send a fake score. The rules block obviously broken entries, and the game filters out rude names, but no free setup can stop cheating completely. If a fake score shows up, delete it in **Firestore Database → Data → scores**.

## Project files

```
bitbrixx/
├── index.html              ← the whole game (graphics, games, music, leaderboard)
├── manifest.webmanifest    ← app name, icon and colours for "Add to Home Screen"
├── sw.js                   ← saves the game on your phone for offline play
├── README.md               ← this page
├── icons/                  ← app icons (180, 192 and 512 px)
├── docs/
│   ├── MANUAL.md           ← the play manual
│   └── screenshots/        ← pictures used on this page
└── firebase/
    └── firestore.rules     ← security rules to paste into Firebase
```

`index.html`, `manifest.webmanifest` and `sw.js` must stay in the top folder, or the game and offline mode stop working.

It's plain HTML, CSS and JavaScript, with no build step and no libraries. The graphics are drawn on a canvas, and every sound is generated live with the Web Audio API, so there are no audio files.

## Credits

Created by **inlndr @ 2026**.

The music and game graphics are original and not copied from any existing game.
