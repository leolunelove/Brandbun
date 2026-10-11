<p align="center">
  <img src="brandbun-ink.png" width="80" height="80" alt="">
</p>

<h1 align="center">brandbun</h1>

<p align="center">A little home for everything your brand is.</p>

<p align="center">
  <a href="https://brandbun.ink/">Open brandbun</a> ·
  <a href="#get-started">Get started</a> ·
  <a href="https://github.com/leolunelove/brandbun/issues">Feedback</a>
</p>

---

## Create, collect, share

- **Create a brand guide.** Bring your story, logos, colours, typography, and assets together in one quiet place.
- **Keep the useful links.** Add your website, YouTube channel, and other places your brand lives.
- **See the whole picture.** Read your guide as a curated, scrolling brand book.
- **Inspect and download.** View assets up close, try logo backgrounds, copy colour values, and download originals.
- **Save with your email.** Sign in through a secure magic link to keep your library across visits and devices. No password needed.
- **Share with someone.** Create a single-recipient invitation. Accepted guides stay in the recipient’s **Shared with me** library with view and download access.
- **Keep a copy.** Download a library backup and restore guides as new copies.

## Get started

1. [Open brandbun](https://brandbun.ink/) and create your first brand.
2. Add a name, a short introduction, and the essentials that make it yours.
3. Sign in with your email to save your device library to the cloud.
4. Open **View brand book** to see everything together, or invite someone to your guide.

You can try brandbun before signing in.

## Your library

Before sign-in, guides are saved in this browser. Clearing browser data can remove that device copy.

After signing in and saving your device library to your email, guides and uploaded files are stored privately in the cloud. Access is enforced through Supabase database and storage policies. Invite recipients receive access to the guide you share; they cannot edit it.

A downloaded backup is a separate recovery copy. Automatic Google Drive backups are not available yet.

## Repository guide

This repository contains the published web build served by GitHub Pages.

| Path | Purpose |
| --- | --- |
| [`index.html`](index.html) | App entry point |
| `index-*.js`, `index-*.css` | Compiled application and styles |
| [`brandbun-ink.png`](brandbun-ink.png) | brandbun’s ink-bun mark |
| [`CNAME`](CNAME) | Custom domain configuration |

GitHub Pages serves the repository root from `main` at [brandbun.ink](https://brandbun.ink/). The editable application source and database setup are maintained separately from this deployment repository.

## Built with

React, TypeScript, and Vite, with Supabase Auth, Postgres, and private Storage. Sign-in emails are delivered by Resend through Supabase’s custom SMTP configuration.

