<div align="center">

```
╔═╗ ╔═╗ ╔═╗ ╔   ╔═╗
╚═╗ ╠═╝ ╠═╣ ║   ╚═╗
╚═╝ ╚═╝ ╩ ╩ ╚═╝ ╚═╝
   one conversation in · one living seal out
```

### 🦭 One conversation in. One living seal out.

![One file](https://img.shields.io/badge/One_file-One_seal-007808)
![Offline](https://img.shields.io/badge/Works-Offline-007808)
![No server](https://img.shields.io/badge/No_account-No_server-000000)
![Same words](https://img.shields.io/badge/Same_words-Same_seal-3776AB)

**A living portrait, grown from a conversation. It builds itself in front of you, keeps breathing when it is done, and answers your hand.**

</div>

---

## How to open your seal

Open the link you were sent. That is all. It plays on any phone, no app, no account, no sign in.

It takes about four and a half minutes to build. Watch it. The words arrive as it grows. When the build finishes, the finished face stays.

---

## Touch it

Your seal is alive under your hand.

- 👆 Move your finger across it and it looks toward you.
- 📱 Tilt your phone and it leans with you.
- ✋ Hold your finger down and it breathes in with you.
- 👆👆 Double tap and it builds itself again.

---

## Keep it

Add it to your home screen and it works offline, like an app that is only yours. Your seal lives on your phone, not on a server somewhere.

---

## What a seal is

A seal is built from a conversation. The words in the ring are the words from that conversation, kept word for word. The face is grown from the same conversation, so no two seals are alike. The link you hold opens one seal and only that seal. Every folder in this repo holds one seal, and nothing else.

---

## How a seal is built

A seal is not drawn. It is not a photo, and it is not a filter. It is grown from a conversation.

A person answers questions in their own words. Those words decide everything: the shape of the face, the colors, the way it moves, the words that ride in the ring. Nothing is added from outside the conversation, and nothing the conversation said is changed.

That is why a seal can be trusted. The same conversation always grows the same seal, on any phone, every time. The link you hold names one seal and only that seal, because the name comes from the conversation itself.

And a seal carries everything it needs inside one file. No account, no server, no one watching. Once it is yours, it is yours. It opens on any phone, works without a connection, and keeps breathing as long as you keep it.

---

## Why it matters

> Most portraits sit still. A seal remembers how it became itself, and shows you. It is a moment that keeps happening, every time you open it.

---

## Under the hood

Seals are baked by PsychArch (`seal.py`, `build_capture`) from a saved genome, on one fixed 4:30 clock: beat stages get 30 seconds, gaps get 10. Each folder in this repo is one seal, baked as a self-contained page:

- `index.html`, the whole seal: 541 baked frames covering the 4:30 build, plus the live layer that answers your hand.
- `manifest.webmanifest` and `sw.js`, which make it installable and let it work offline.
- `icon-192.png` and `icon-512.png`, the home screen icons, drawn in the seal's own colors.
- `Dockerfile`, for serving the seal from a container instead of a static host.

The folder name is the seal's fingerprint, a hash of the conversation it grew from: the pool, the blend, the archetype, the seed, and the beats, word for word. The same conversation always bakes the same seal, and the same fingerprint always opens the same seal. That is what makes the link proof, not just an address.

The page is served as plain static files. `.nojekyll` keeps GitHub Pages from processing it, so what is baked is exactly what is served.

---

*If this is yours, it was built for you and no one else. Open it slowly, let it finish, and touch it. It will be here, breathing, whenever you come back.*
