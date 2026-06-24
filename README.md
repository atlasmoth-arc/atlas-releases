# Atlas

### Your notes, with a mind of their own — running entirely on your phone.

Atlas is an offline-first note app with a real AI built in. Write things down the way you always
do, then *ask* — in plain language — and Atlas answers from your own notes, showing you exactly
which ones it drew from. No cloud. No account. Your notes never leave your phone.

**Free. No ads. No tracking. Android.**

<!-- screenshots: add 2–3 PNGs here before publishing — e.g. Chat with source cards, the Graph, the Dashboard -->

---

## What Atlas does

**✍️ Write.** Fast Markdown notes with typed tags (people, projects, ideas), full-text search,
reminders, pinning, and a daily journal. Two home-screen widgets keep capture instant — **Quick
Capture** (a new note in one tap) and **Journal** (jump straight to today's entry).

**💬 Ask.** A built-in chat reads across all your notes and answers your questions in plain
language — then cites the exact notes behind each answer. It's like having a private ChatGPT over
your own knowledge, except it runs locally and keeps working in airplane mode.

**🕸️ See the connections.** Atlas builds a live **knowledge graph** of your notes — linking them
through shared tags and references — so you can *see* how your ideas relate instead of scrolling a
flat list. Pan, zoom, and follow a thread of thought across weeks of notes.

**🌤️ Stay oriented.** A calm daily dashboard pulls your day together: a greeting, local weather,
today's journal, reminders, open tasks, and "on this day" memories from past notes.

---

## Why it lives on your phone

Atlas runs a genuine AI model — language understanding **and** semantic search — directly on your
device. That's a deliberate choice, not a limitation: your notes are your thinking — your ideas,
plans, and half-formed connections — and that knowledge should stay yours. So Atlas brings the
intelligence *to* your notes instead of sending your notes off to someone's server. No sign-up, no
tracking of what you write, and the whole app works with the internet switched off.

The one trade-off is a little patience up front:

> **On first launch, Atlas downloads its AI models (~1.9 GB) over Wi-Fi.**

Those models *are* the brain. Because the AI runs on your phone rather than in a data center, the
brain has to live on your phone too. They download once — after that, chat, semantic search, and
auto-tagging all work fully offline, forever, with zero server round-trips. The models are stored
alongside your notes, so future app updates stay small and never re-download them.

And your notes are never locked in: back up your **whole notebook** to a single file you control —
optionally password-encrypted — and restore it on any device (restoring merges, so nothing is ever
overwritten), or export any individual note as plain Markdown. Whenever you like.

---

## Before you install — what your phone needs

Because the AI runs locally, Atlas needs a reasonably capable phone:

| | Requirement |
|---|---|
| **Android** | 7.0 or newer |
| **RAM** | 4 GB minimum · 6 GB+ recommended (the model loads into memory while you chat) |
| **Free storage** | ~3 GB (the app plus its ~1.65 GB language model and ~274 MB search model; your notes are tiny) |
| **Connection** | Wi-Fi for the one-time model download on first launch |

On older or low-memory phones the AI may load slowly — but notes, search, and the graph still work
fine regardless.

---

## Install on Android

Atlas isn't on the Play Store, so you install the APK yourself — a two-minute, one-time setup:

1. **Download the latest version:**
   **[⬇️ app-release.apk](https://github.com/atlasmoth-arc/atlas-releases/releases/latest/download/app-release.apk)**
2. Open the downloaded file. Android will ask permission to install from your browser or file
   manager — turn on **"Install unknown apps"** for that app, then tap Install.
3. If Play Protect warns that the developer is unknown, choose **Install anyway**. Atlas is simply
   *unlisted*, not unsafe.
4. Open Atlas and let it finish the one-time model download on Wi-Fi. You're set.

---

## Updates

Once installed, Atlas keeps itself current. Open **Settings → Check for updates** and it downloads
and installs new versions in place — your notes and AI models stay exactly where they are.

---

## Feedback

Hit a bug or have an idea? **[Open an issue](https://github.com/atlasmoth-arc/atlas-releases/issues)** —
all feedback is welcome. Atlas is a personal, indie project, and real-world reports genuinely shape
what comes next.

---

## Changelog

A quick glance at what each update brings. Newest first — update in-app via **Settings → Check for updates**.

### v1.3.0

**New**
- **Spending tracker.** Log expenses in seconds — from your daily note, a new home-screen widget, or
  straight from chat. A dedicated **Spending** screen shows your week and month totals with a
  per-category breakdown and recent entries, and the daily Dashboard now has an at-a-glance spending card.
- **Ask about your money.** Chat answers spending questions in plain language — by date *and* by
  category ("how much did I spend yesterday?", "how much on food this month?").

**Improved**
- **Smarter semantic search.** Question-matching is more accurate, and the on-device search model now
  warms up at launch — so your first question finds the right notes right away instead of falling back
  to a keyword search.
- **Unified home-screen widgets.** Quick Capture, Journal, and Log Expense now share one consistent,
  playful look.

### v1.2.0

**New**
- **Backup & restore** your entire notebook to a single portable file. Restoring *merges* — your
  existing notes are never deleted, and the newer copy wins where they overlap.
- **Optional password encryption** for backups, so a backup file is safe to keep in Drive, Files, or
  anywhere else.
- **Auto-check for updates on launch** (opt-in), with the **download size and speed** shown while an
  update downloads.

**Improved**
- **Much lower memory use** — Atlas now frees the AI model whenever it's in the background, so the
  system no longer kills the app. No more "it restarted when I came back"; it reloads on its own.
- **Faster, smoother chat** and a more reliable AI loading state.

**Fixed**
- No more force-close after a backup or restore.
- Background search indexing no longer slows down an in-progress chat answer.
- Assorted stability fixes around loading and removing the on-device models.

### v1.1.0

- Reliable in-app updates: signed in-place updates that keep your notes and models intact, plus a
  faster, repeatable release process behind the scenes.

### v1.0.x

- First release: on-device AI chat over your own notes, Markdown notes with typed tags, semantic
  search, the knowledge graph, reminders, home-screen widgets, and light/dark themes.
