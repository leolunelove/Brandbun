<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="brandbun-ink-white-v2.svg">
    <img src="brandbun-ink-v2.png" width="80" height="80" alt="brandbun ink-bun logo">
  </picture>
</p>

<h1 align="center">brandbun</h1>

<p align="center">A little home for everything your brand is.</p>

<p align="center">
  <a href="https://brandbun.ink/">Open brandbun</a> ·
  <a href="#get-started">Using brandbun</a> ·
  <a href="brandbun-brand-book.pdf">Visual brand book</a>
</p>

## Create, collect, share

- **Start small.** Create a brand guide with a name. No sign-in needed to start.
- **Bring it together.** Keep your story, logos, colours, typography, and assets in one quiet place.
- **Keep the useful links.** Add your website, YouTube channel, and other places your brand lives.
- **See the whole picture.** Read your guide as a curated, scrolling brand book.
- **Inspect and download.** View assets up close, try light, dark, and brand backgrounds, copy colour values, and download files.
- **Save with your email.** Keep your library across visits and devices through an emailed magic link. No password to remember.
- **Share with someone.** Create a single-recipient invitation. Accepted guides stay in the recipient’s **Shared with me** library with view and download access.
- **Keep a copy.** Download a library backup and restore guides as new copies.

## Get started

1. [Open brandbun](https://brandbun.ink/) and choose **Create a brand guide**.
2. Give it a name, then add a logo and your first colour. Make it yours as you go.
3. Sign in with your email and save your device library to keep it across devices.
4. Choose **View brand book** to see everything together, or invite someone to view your guide.

## Your library

Guest guides stay in the browser where you create them. Clearing that browser’s site data can remove the device copy; save your library to your email before relying on it across devices. Local guides do not transfer automatically between browsers or website addresses.

Cloud guides and uploaded files are stored privately. Owners can edit; accepted invitation recipients can view and download the guide shared with them. Supabase database and storage policies enforce those permissions.

A downloaded library backup is a separate recovery copy. Automatic cloud backups and Google Drive backup are not enabled.

## Support brandbun

Free libraries hold **5 brands and 20 MB**. Early supporter starts at **$2 USD, paid once**, for **25 brands and 100 MB**, tied to your signed-in account. Choose a higher amount if you like; every amount receives the same upgrade. The **5 MB file limit** stays the same.

Use **About & help** in the app if you need a hand or want to ask about more space.

## Repository guide

This repository contains the published web build served by GitHub Pages.

| Path | Purpose |
| --- | --- |
| [index.html](index.html) | App entry point |
| `index-*.js`, `index-*.css` | Compiled application and styles |
| [brandbun-ink-v2.png](brandbun-ink-v2.png) | Primary ink-bun mark |
| [brandbun-ink-white-v2.svg](brandbun-ink-white-v2.svg) | White mark for dark backgrounds |
| [brandbun-brand-book.pdf](brandbun-brand-book.pdf) | Visual identity and usage guide |
| [CNAME](CNAME) | Custom domain configuration |

GitHub Pages serves the repository root from `main` at [brandbun.ink](https://brandbun.ink/). The editable application source and database setup are maintained separately from this deployment repository. This repository is a published build, rather than a source checkout you can run with `npm install`.

## Built with

React, TypeScript, and Vite, with Supabase Auth, PostgreSQL, and private Storage. Database and storage policies enforce access. Sign-in emails are delivered by Resend through Supabase’s custom SMTP configuration; payments use Stripe.

Guest guides use browser storage. The browser uses a Supabase publishable key; service-role, payment, and email-provider secrets stay out of the app.

Made with care by [Leo Lune](https://leolune.com/).

[Feedback and issues →](https://github.com/leolunelove/brandbun/issues)
