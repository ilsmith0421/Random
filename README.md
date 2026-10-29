# Ultimate · Bonus Scrimmage

A standalone, mobile-first scoreboard for a JV Ultimate practice. All styles and JavaScript are included in `index.html`. No installation, accounts, or backend required.

## Use it

Download `index.html` to use on a computer, or host it for the best iPhone experience. Edit either team name, select the scoring team, toggle bonuses, and tap **Add Points**. The base goal always adds 1 point. Hand Block buttons immediately award 2 points. Turnover buttons immediately subtract 2 points from that team; scores can go below zero. Penalties are saved in history and can be undone. **Undo last** reverses the latest scoring action. **New Game** asks before clearing names and history.

Scores and history save automatically in this browser's localStorage. Each device/browser has its own game; sharing the URL does not share scores. Private browsing, clearing website data, or unavailable storage can remove/prevent persistence. A warning appears if saving fails.

## Publish free with GitHub Pages

1. Commit and push `index.html` and this README to the `main` branch of `ilsmith0421/Random`.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main**, **/ (root)**, then **Save**.
5. Wait for deployment and open the URL GitHub displays (normally `https://ilsmith0421.github.io/Random/`). Share that URL with the team.

On iPhone, open the published URL in Safari, tap **Share → Add to Home Screen**, and tap **Add**. Home screen mode uses the app title and dark status bar. Internet is needed to load the website; offline launch is not guaranteed. No real-time synchronization is provided.

## Local preview

From the repository directory run `python3 -m http.server 8000`, then open the local server in a browser. No build step is needed.
