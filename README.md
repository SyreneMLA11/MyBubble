# 🫧 Bubble

A calm, minimal emotional-dump app. Pour your feelings into a bubble that fills and changes color with your mood, then get a gentle reflection shaped by your love language.

Sometimes there's too much clutter in your head to put into words. Bubble gives you a quiet place to let it out.

## What it does

- **Love language quiz** on first launch (rate five statements 1-5) that shapes how Bubble talks to you
- **Animated bubble** that fills with water as you write, and shifts color with the sentiment of your words
- **A reflection** after you let it out: how you feel today, your energy level, how to feel better, and what from your own life can help
- **My Bubble Space:** save favorite things as icons with a memory note and optional link. Tap one to enlarge it, or open a song link to play it
- **Make me feel better** button that surfaces a random favorite
- Light and dark mode, mobile-friendly

## Run it

No build step and no dependencies. Open `index.html` in a browser.

## Host it free with GitHub Pages

1. Go to **Settings > Pages** in this repo
2. Under **Branch**, choose `main` and `/ (root)`, then Save
3. After a minute your app is live at `https://syrenemla11.github.io/MyBubble/`

## How it works

- Fill level follows `1 - e^(-characters / 260)`, so it rises quickly at first and slows as it nears full
- Sentiment is a keyword scan with simple negation handling ("not happy" counts as sad). It runs locally, so it can miss sarcasm
- Everything is saved in your browser's `localStorage`

## Privacy

Everything you write stays on your device. Nothing is sent anywhere.

## Roadmap

- Mood history and trends
- AI-written reflections
- Optional sync across devices
- Embedded music playback

## License

MIT
