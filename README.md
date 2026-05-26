# Starpoint

Starpoint is a browser-based space trading game. Trade goods, hunt bounties, amass a fortune, buy a moon, and retire.

Developed by **Tribel**.

Play online at [https://xtribelx.github.io/starpoint/](https://xtribelx.github.io/starpoint/).

## Run locally

Starpoint is a static web app with no build step. Serve the repository root over HTTP:

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080/](http://localhost:8080/) in your browser.

## Features

- Full trading, combat, and exploration gameplay
- Save/load via browser localStorage
- Progressive Web App (PWA) support for offline play and home-screen install
- Cheat/debug build at `cheats.html`
- Unit tests at `unitTests.html`

## Upstream credit

Starpoint is based on the web port of the classic Palm OS trading game, originally created by Pieter Spronck. The JavaScript port and web UI were developed by [memalign](https://memalign.github.io/m/spacetrader/) and published in [memalign/memalign.github.io](https://github.com/memalign/memalign.github.io/tree/master/m/spacetrader).

This project adapts that upstream port with Tribel branding and hosting. The upstream repository does not include an explicit license file.
