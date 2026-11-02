<h1 align="center">AceTheWords</h1>

<p align="center"><b>Learn vocabulary for good — before the test.</b><br>
A free, single-file web app that looks up your words, quizzes you, and schedules reviews right before you'd forget.</p>

<p align="center">
  <a href="docs/AceTheWords-User-Manual.pdf"><img alt="Read the User Manual (PDF)" src="https://img.shields.io/badge/%F0%9F%93%98%20READ%20THE%20USER%20MANUAL-PDF-5b5bd6?style=for-the-badge"></a>
  &nbsp;
  <a href="https://itsyuranwei.github.io/acethewords/"><img alt="Use it online" src="https://img.shields.io/badge/%E2%96%B6%20USE%20IT%20ONLINE-no%20download-16955a?style=for-the-badge"></a>
</p>

> ### 📘 New here? Start with the [**User Manual (PDF)**](docs/AceTheWords-User-Manual.pdf)
> It walks you through downloading AceTheWords from this page, opening it, and using every feature step by step.

---

## Quick start

**Fastest:** open **https://itsyuranwei.github.io/acethewords/** — the app runs right in your browser.

**Or download your own copy:**

1. Click the green **Code** button near the top of this page, then **Download ZIP**.
2. Unzip the downloaded file.
3. Double-click **`acethewords.html`**. It opens in your web browser — no install, no account.

Prefer the command line?

```bash
git clone https://github.com/itsyuranwei/acethewords.git
```

Then open `acethewords/acethewords.html` in Chrome, Edge, Safari or Firefox.

> Progress is saved per browser *and* per location, so the online version and a downloaded copy each keep their own progress. Use **Settings → Export / Import backup** to move between them.

## What it does

- **Word lists per test or class** — paste words (or import them from a photo) and the app looks up meanings, pronunciation and examples automatically.
- **Learn → Practice → Review** — meet new words in small batches, practice with questions that get harder as each word gets stronger, and review memorized words just before they fade.
- **Test-date planning** — set a test date and the app spreads new words out so everything is learned and reviewed in time.
- **Smart scheduling** — uses FSRS-5, the spaced-repetition model behind Anki's modern scheduler, plus a hidden answer-speed signal.
- **Optional AI** — add a DeepSeek API key for student-friendly definitions, fill-in-the-blank and correct-usage questions, and photo import.
- **Private by default** — everything is saved in your own browser. Export a backup file any time.

## Files

| File | What it is |
| --- | --- |
| `acethewords.html` | The whole app. Open it in a browser. |
| `index.html` | Sends the online version's home page to the app. |
| `docs/AceTheWords-User-Manual.pdf` | The illustrated user manual. |

## Privacy

Your words and progress stay in your browser's local storage on your device. Word lookups go to the free [Dictionary API](https://dictionaryapi.dev/). If you add a DeepSeek key, words (and any photos you import) are sent to DeepSeek to write questions; the key itself is stored only in your browser and is never included in backup exports.
