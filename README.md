# Clickable Subtitles – Besintu Episode 1

This project demonstrates how to add **clickable subtitles** to a video using a structured JSON file. When a subtitle line is clicked, it seeks the YouTube video to the corresponding timestamp and plays from there.

## 🔗 Live Demo
[https://nadirkiyaro.github.io/Clickable-subtitles/](https://nadirkiyaro.github.io/Clickable-subtitles/)

## 📁 Files Included

- `index.html` – Main webpage that embeds the YouTube video and subtitles.
- `besintu_ep1_subtitles.json` – Subtitles file containing timestamps and word-level tooltips.
- `clickable_subtitles_site.zip` – A packaged version of the project ready to upload.

## ▶️ YouTube Integration

The embedded video is hosted on YouTube. Subtitles are synced with it using the YouTube IFrame API.

## 🛠️ How to Use

1. Upload `index.html` and `besintu_ep1_subtitles.json` to your GitHub repository (e.g., `main` branch).
2. Go to **Settings → Pages** and set the GitHub Pages source to `/ (root)` of `main`.
3. Your site will be live at `https://<your-username>.github.io/Clickable-subtitles/`.

## 📦 Development Notes

- Subtitles are loaded from JSON and rendered dynamically.
- Each subtitle line is clickable and jumps to the relevant time in the video.
- Word-level tooltips display translations or notes on hover.

## 📷 Screenshot

*(Optional: Include a screenshot of the interface here)*

## ✅ License

This project is open-source and free to use for educational or personal projects.
