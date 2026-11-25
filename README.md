# btkmediaproduction.github.io

Static website for BTK Media Production (ห้างหุ้นส่วนจำกัด บีทีเค มีเดีย โปรดักชั่น), served by GitHub Pages.

- `/` — company introduction and contact
- `/privacy/` — privacy policy (Thai + English)
- `/terms/` — terms of service (Thai + English)
- `/tiktok/callback/` — TikTok Login Kit redirect URI: forwards `code` + `state` to the BTK API on the
  same computer (`http://localhost:8000/auth/tiktok/callback`); stores and logs nothing
- `assets/logo.png` — 1024×1024 app icon (used for the TikTok developer app)

No build step: edit the HTML and push to `main`.
