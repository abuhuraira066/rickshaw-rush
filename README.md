# 🛺 Rickshaw Rush

A funny desi endless-runner where you drive a rickshaw through **Karachi, Lahore, Mumbai and Delhi**: pick up sawariyan, dodge potholes, open gutters, cows, goats, bikers, cars and decorated trucks, and drink chai for **CHAI TURBO**.

Built with HTML5 + [Three.js](https://threejs.org) (r128). Every sound effect and the music are synthesized in code with the Web Audio API, so there are no copyrighted audio files.

## ▶️ Play
Open `index.html` in any modern browser (an internet connection is needed for Three.js and Google Fonts).

With GitHub Pages turned on (Settings → Pages → Branch: `main`, folder `/root`), the game is live at:
`https://<your-username>.github.io/<repo-name>/`

## 🎮 Controls
| Action | Mobile | Keyboard |
|---|---|---|
| Change lane | Swipe left/right, or tap the left/right side | A / D or ← → |
| Jump (potholes, gutters, goats) | Swipe up, or tap the middle | Space / W / ↑ |
| Brake (stop in the green circle to pick up a sawari) | Hold **BRAKE** | S / ↓ |
| Horn (moves bikers, people, goats, wardens) | **HORN** | H |
| Pause / Mute | ⏸ 🔊 buttons | P / M |

## 📁 Files
- `index.html`: main game (Real 3D, with HD/Fast graphics toggle)
- `versions/rickshaw-rush-3d-simple.html`: lighter low-poly 3D version
- `versions/rickshaw-rush-2d.html`: 2D version (no 3D engine, works on any phone)

## 💰 Ads (Play Store build)
The "Ad dekho, 1 life wapas lo" button is a demo. In an Android (Capacitor + AdMob) build, set:
```js
window.RickshawRush.showRewardedAd = (done) => { /* show rewarded ad, then */ done(true); };
```

## 🗺️ Roadmap
- [ ] Bundle Three.js + fonts locally for offline play
- [ ] Capacitor Android build (.aab) + AdMob
- [ ] Google Play release
