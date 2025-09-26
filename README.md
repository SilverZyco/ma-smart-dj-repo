# Smart DJ Add-ons

This repository contains the **MA Smart DJ** add-on for Home Assistant / Music Assistant.

## Install
In Home Assistant → Settings → Add-ons → Add-on store → top right ⋮ → **Repositories** → add the URL of **this GitHub repository**.

Then install **MA Smart DJ** from the new repository card.

## Add-on: MA Smart DJ
- Auto-playlists (Daily Mix, Artist Radio, Discover, Mood)
- **Autoplay/Radio**: When a playlist ends or the player is idle, the add-on automatically fills the queue with similar tracks (YouTube Music supported; Spotify optional)
- Exposes a REST API: `/playlist`, `/radio/start`, `/radio/tick`
- Stores history in `/data/history.db`
- Writes `.m3u8` files to `/share/ma_playlists` (Filesystem provider in Music Assistant)

See `ma-smart-dj/README.md` for full docs.
