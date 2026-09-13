<div align="center">

# hey, i'm antoine 👋

**full-stack dev and photographer in auckland, new zealand. kiwi and french.**

i like building small, fast, self-hostable things — mostly rust and typescript — and i have a soft spot for desktop apps that don't ship a whole browser just to draw a window.

[rossi.nz](https://rossi.nz) · [antoinerossi.nz](https://antoinerossi.nz) · [instagram](https://instagram.com/antoinenzfr) · [linkedin](https://linkedin.com/in/antoinenzfr)

</div>

## about me

my grandfather registered `rossi.nz` when i was a kid and got me into coding. i picked up python at around 10, moved on to html and css, and eventually ended up in rust, go and whatever else the project needed. i spent a couple of years in france (2023–2025), came back fluent, and kept coding and shooting the whole time.

none of this is my job (yet). everything here is a hobby, a way to get better, or a tool i wanted and couldn't find. i'm studying electrical engineering, and once that's done i'll probably put all this to use in a job or start something of my own.

i never really set out to have a philosophy, but looking back most of what i build ends up the same way: one binary, one folder to back up, runs on your own machine, doesn't phone home. no electron, no telemetry, nothing you can't just delete.

when i'm not coding i'm behind a camera, running events, or behind a mixing desk — not quite professionally, but not quite casually either.

## stuff i've built

| project | what it is | built with |
|---|---|---|
| [**OpenAir**](https://github.com/Antoinenz/OpenAir) | open-source, cross-platform **airplay 2 transmitter**. streams your pc's audio to homepods, apple tvs and shairport sync — multi-room, lossless alac, and the whole protocol stack (discovery, homekit pairing, encrypted rtsp, ptp timing) written from scratch. | rust |
| [**Vitrine**](https://github.com/Antoinenz/Vitrine) | a **self-hosted photo gallery** for photographers and artists. collections shown as 3d-tilting stacks of prints, a proper deep-linkable viewer, per-collection visibility and passwords, exif stripped on serve. one node process, one sqlite file. | sveltekit, svelte 5, sqlite |
| [**Claudeometer**](https://github.com/Antoinenz/Claudeometer) | desktop app for **tracking claude.ai usage limits** live from the system tray, with notifications and a local http api so coding agents can check their own usage and stop cleanly before hitting a limit. also runs headless. | tauri v2, rust, react |
| [**mcplug**](https://github.com/Antoinenz/mcplug) & [**mcbackup**](https://github.com/Antoinenz/mcbackup) | a pair of **minecraft server tools**: a terminal plugin manager that identifies jars by hash, updates transactionally with rollback and restarts when nobody's on; and versioned, deduplicated, player-aware backups to cloudflare r2. | rust, python, restic |
| [**OpenWhatsApp**](https://github.com/Antoinenz/OpenWhatsApp) | a native whatsapp client for windows on webview2 — ~70 mb of ram instead of ~350, and it actually stays logged in. | tauri, rust |
| [**spotify-videos**](https://github.com/Antoinenz/spotify-videos) | a web app that plays the **music video for whatever's playing on spotify**, via a self-hosted invidious instance. made for parties — plug a laptop into a projector and let it run. | html, js |

there's a bunch of other smaller things scattered around my repos, and a few bigger ones that aren't public (yet).

## things i host

i own more domains than i probably should. some of what's on them:

- [**podesentar.com**](https://podesentar.com) — everyone in the room opens it on their phone and the same video plays in perfect sync. a joke that got wildly overengineered: per-device ids, drift telemetry, an admin dashboard, ios safari workarounds. worth it.
- [**shortlink.nz**](https://shortlink.nz) — a url shortener, and my first proper website with a backend. i've modernised it a bit since (cloudflare pages + supabase) but honestly it still doesn't work that well. it's here for the nostalgia.
- [**hostanything.app**](https://hostanything.app) — host any file, paste one link, and it embeds inline wherever you drop it. built to get around discord's 10 mb cap. abandoned-ish.
- [**downloadanything.nz**](https://downloadanything.nz) — invite-only media downloader running on a raspberry pi at home, with a chain-of-trust invite system so it stays under the radar. abandoned-ish too.
- [**tachyon-studios.com**](https://tachyon-studios.com) — a "company" i made up for a school project and kept as a brand because i like the name.

## tech i reach for

`rust` `typescript` `tauri` `sveltekit` `react` `go` `python` `sqlite` `supabase` `docker` `cloudflare`

## say hi

📫 [contact@rossi.nz](mailto:contact@rossi.nz) · 🌐 [rossi.nz](https://rossi.nz)
