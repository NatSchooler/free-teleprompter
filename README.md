# Free Teleprompter

**A free teleprompter that runs in your web browser from one HTML file.** No install, no account, no sign-up and no tracking. Download it, open it, and start reading your script on camera.

It works on Windows, macOS, Linux, Chromebook, iPad and Android tablets, in Chrome, Edge, Firefox and Safari. Once the file is on your computer it also works offline.

Made by [Nat Schooler](https://natschooler.com) for the [Influential Visions](https://influentialvisions.com) podcast, and given away free under the MIT Licence.

---

## ⚠️ No support is provided

This software is free and given as it is. I do not offer help installing it, fixing it or answering questions about it. If something breaks, it is yours to fix. Use it at your own risk, and always keep a copy of your scripts.

---

## Want to say thank you? Get my book.

**CATAPULT PROTOCOL™ — The Career Playbook for the AI and Superintelligence Shift**
$7.99 launch price for the first 1,000 copies only.
👉 [GET THE BOOK](https://natschooler.com/cat/)

Feeling rich and want to support another creator? [DONATE HERE](https://buy.stripe.com/fZudR896FfExeje8IWfAc0b)


Subscribe to [Influential Visions on YouTube](https://www.youtube.com/@influentialvisions?sub_confirmation=1) and follow the podcast.

---

## Features

- Smooth auto-scrolling with an adjustable speed
- Adjustable text size, with a reading line marker
- Mirror mode for teleprompter glass and beam-splitter rigs, plus an upside-down flip
- Optional camera view behind the text, so you can check your framing while you read
- Three-second countdown before scrolling starts
- Full screen mode, with the controls fading out while you read
- Progress bar showing how far through the script you are
- Open a .txt or .md script file, or save your script as a .txt file
- Your script and settings are kept in your browser automatically
- Keyboard shortcuts for hands-free control

## How to use it

### Option 1: on your own computer (the quickest way)

1. Download **index.html** from this repository (click the file, then the download button), or click the green **Code** button and choose **Download ZIP**.
2. Double-click **index.html**. It opens in your web browser.
3. Click **Edit Script**, paste in your script, then click **Save & Open Prompter**.
4. Press **Space** or click **Start** to begin scrolling.

That is all. Nothing is installed and nothing is sent anywhere.

### Option 2: use it online with GitHub Pages

You can host your own copy for free so it opens from a web address on any device:

1. Click **Fork** at the top of this page to copy the repository to your own GitHub account.
2. In your copy, go to **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the **main** branch and the **/ (root)** folder, then click **Save**.
4. After a minute or two your teleprompter is live at `https://YOUR-USERNAME.github.io/free-teleprompter/`.

### Option 3: put it on your own website

Upload **index.html** to any folder on your web server, for example `yoursite.com/teleprompter/`. It is a single static file, so it needs no PHP, database or server setup.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| Space | Start or pause |
| Up / Down arrows | Faster / slower |
| Left / Right arrows | Nudge the text back or forward |
| + / − | Bigger / smaller text |
| Home | Back to the top |
| M | Mirror the text |
| V | Flip the text upside down |
| C | Camera on or off |
| F | Full screen |
| E | Switch between the editor and the prompter |
| Esc | Leave the editor |

You can also click or tap the text to start and pause.

## Tips for a natural read

- Keep your eyes on the line beside the arrow marker, and let the text come to you.
- Start slower than you think you need, then raise the speed with the up arrow as you settle in.
- Place the browser window as close to the camera lens as you can, so your eyes stay near the lens.
- Write short lines and leave a blank line between paragraphs. It gives you natural places to breathe.

## The camera view

The camera button shows your webcam faintly behind the text. Your browser will ask for permission the first time. The video stays on your device: it is not recorded or uploaded anywhere. If the camera does not appear, check that the browser has camera permission for this page. Some browsers only allow the camera on pages served over https, so if it is blocked when opened as a local file, use the GitHub Pages option above.

## Privacy

Everything happens inside your browser. The script and your settings are stored in your browser's local storage on your own device. There are no analytics, no cookies, no external fonts and no third-party scripts.

## Customising

Everything lives in **index.html**: the styles at the top, the layout in the middle and the script at the bottom. To change the colours, edit the values at the start of the style section (for example `--accent` for the highlight colour).

## Licence

Released under the MIT Licence. See [LICENSE](LICENSE). You are free to use, change and share it, including for commercial work.

