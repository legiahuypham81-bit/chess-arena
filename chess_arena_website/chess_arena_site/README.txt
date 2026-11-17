3D CHESS ARENA - WEBSITE

Run locally:
1. Open index.html in Chrome or Edge.
2. Internet is required to load Chess.js from its CDN.

Publish free with GitHub Pages:
1. Sign in to https://github.com/ and create a new PUBLIC repository, e.g. chess-arena.
2. Upload index.html to the repository root (the top level, not inside another folder).
3. Open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select Branch: main and Folder: / (root), then Save.
6. Wait a minute or two. GitHub will show your website URL, usually:
   https://YOUR-USERNAME.github.io/chess-arena/
7. Open that URL and share it with friends.

Notes:
- The game uses Chess.js from a CDN, so visitors need an internet connection.
- The HTML refers to optional sound files in sounds/ (move.mp3, capture.mp3, check.mp3,
  checkmate.mp3, win.mp3, lose.mp3, draw.mp3). Those MP3 files were not included in
  the uploaded source, so the game itself works but those custom sounds will not play
  until you add the files in a folder named sounds.
- This version is a static website. It does not provide online multiplayer across
  different devices; the existing local mode is for two players sharing one device.
