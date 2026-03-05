<p align="center"><img src="public/logo.png" height="200"></p>
<h1 align="center">Quantum Browser</h1>

<p align="center">A sleek, modern web browser built on top of the Ultraviolet proxy engine — browse freely with style.</p>

## Features

- 🥷 **Stealth Mode** — opens in an `about:blank` tab to hide your activity
- ⚡ **Ultraviolet Proxy** — bypasses site embedding restrictions and censorship
- 🎨 **Animated particle background** — beautiful UI with a space theme
- 🔒 **DuckDuckGo search** — private search by default, no reCAPTCHA
- 🗂️ **Multi-tab support** — open and manage multiple tabs
- ⬅️➡️ **Navigation history** — back and forward buttons per tab

## Deployment

[![Run on Replit](https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg)](https://github.com/titaniumnetwork-dev/Ultraviolet-App/wiki/Run-on-Replit)
[![Deploy on Railway](https://binbashbanana.github.io/deploy-buttons/buttons/remade/railway.svg)](https://github.com/titaniumnetwork-dev/Ultraviolet-App/wiki/Deploy-on-Railway)
[![Deploy to Koyeb](https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg)](https://github.com/titaniumnetwork-dev/Ultraviolet-App/wiki/Deploy-to-Koyeb)

If you are deploying to an alternative service or to a server, refer to [Deploy via terminal](https://github.com/titaniumnetwork-dev/Ultraviolet-App/wiki/Deploy-via-terminal).

To run locally:

```bash
npm install
npm start
```

Then open `http://localhost:8080` in your browser.

> [!IMPORTANT]  
> Until deployed on a domain with a valid SSL certificate, Firefox will not be able to load the site. Use Chromium for testing on localhost.

## Built With

- [Ultraviolet](https://github.com/titaniumnetwork-dev/Ultraviolet) — service worker proxy
- [BareMux](https://github.com/MercuryWorkshop/bare-mux) — transport layer
- [EpoxyTransport](https://github.com/MercuryWorkshop/EpoxyTransport) — encrypted transport
