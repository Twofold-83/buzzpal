# 📣 BuzzPal

Big, fun buttons on your kid's iPad → instant notifications on your phone.
You can answer with animated replies (confetti, heart rain, balloons…) and sounds.

## Files
- `index.html` – the whole app (kid mode + parent mode)
- `icon-*.png` – home-screen icons

## 1. Put it online (once, free, ~3 minutes)
The app needs to live at an `https://` address. Easiest options:

**GitHub Pages:** create a public repo, upload these files, then Settings → Pages →
"Deploy from branch" → `main` / root. Your app is at `https://<you>.github.io/<repo>/`.

**Netlify Drop:** go to https://app.netlify.com/drop, sign in, drag this folder onto the page.

## 2. Set up your phone
1. Install the free **ntfy** app (iPhone App Store / Google Play). This is what makes your phone buzz.
2. Open your BuzzPal address on your phone → **I'm the parent** → enter names + a 4-digit PIN.
3. Follow the **⚙️ Setup** tab: subscribe to the topic shown (in ntfy: ＋ → paste topic → Subscribe),
   then press **🔔 Send test notification**.
4. Add the page to your home screen (Share → Add to Home Screen) so you can send fancy replies.

## 3. Set up the iPad
1. Scan the QR code from the Setup tab with the iPad camera → opens in Safari.
2. Share ⬆️ → **Add to Home Screen**. Done – it's an app now.

## Using it
- **Kid:** pick a mood sticker (😡 angry, 😢 sad, 🚨 urgent, 🤪 silly, ❓ question) → press a button.
  Urgent messages are sent with max priority. A short "recharging" wait stops button spam.
- **You:** the notification has 3 quick-reply buttons (Yes/No/Maybe or OK/Love you/Wait) –
  tap one and it pops up on the iPad with an animation + sound. Open the app for 14 preset replies
  or make your own (any emoji + text + animation + sound, with preview).
- **Edit buttons:** 🎨 Buttons tab on your phone → Save, and the iPad updates by itself.
  On the iPad itself: press and hold the ⚙️ in the corner for 2 seconds → PIN.

## Good to know
- Messages go through the free public service ntfy.sh. Your random family code (like `bz-k7m2-x9qp-4hz8`)
  is the "password" – don't share it. Reset and re-pair if it leaks.
- iPads only play sounds after a first tap; if a reply arrives before that it shows "🔊 Tap to hear it!".
- If the iPad was offline, the latest replies/button changes from the last ~12 hours arrive when it opens.
