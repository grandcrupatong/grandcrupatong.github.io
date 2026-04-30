# Grand Cru Apartment Patong — Landing Page

Boutique furnished one-bedroom rentals at 83/7 Phang Mueang Sai Kor Road, Patong, Phuket. Static landing page, designed to be hosted free on GitHub Pages.

## Files

- `index.html` — page markup
- `styles.css` — all styling (woody brown + off-white palette)
- `room-1.jpg` — hero photo
- `README.md` — this file

**All four files must sit in the same folder.** No subfolders. If `room-1.jpg` is missing or in a different folder, the photo won't show.

No build step. Just upload and go.

---

## Deploying to `grandcrupatong.github.io`

To get the URL **`https://grandcrupatong.github.io`**, follow these steps exactly:

### 1. Create a GitHub account named `grandcrupatong`

- Go to <https://github.com/signup>
- Username **must** be `grandcrupatong`
- If that username is taken, you'll need to pick another (e.g. `grandcru-patong`) — your URL will then become `https://grandcru-patong.github.io`

### 2. Create a new repository

- After signing in, click the **+** in the top-right → **New repository**
- Repository name: **`grandcrupatong.github.io`** (must match the username exactly, with `.github.io` at the end)
- Set it to **Public**
- Click **Create repository**

### 3. Upload these files

**Easiest way (via the web):**

1. On the empty repo page, click **"uploading an existing file"**
2. Drag in `index.html`, `styles.css`, and `README.md`
3. Add a commit message like `initial site`
4. Click **Commit changes**

**Or via Git on the command line:**

```bash
git clone https://github.com/grandcrupatong/grandcrupatong.github.io.git
cd grandcrupatong.github.io
# copy index.html, styles.css, README.md into this folder
git add .
git commit -m "initial site"
git push
```

### 4. Enable Pages

- Go to the repo → **Settings** → **Pages** (in the left sidebar)
- Under **Source**, select **Deploy from a branch**
- Branch: `main`, folder: `/ (root)` → **Save**
- Wait 1–2 minutes

### 5. Visit your site

It will be live at **<https://grandcrupatong.github.io>**

---

## Editing later

- Open `index.html` to change text, contact info, or sections
- Open `styles.css` to change colors, spacing, or fonts
- Replace the placeholder photo block (the brown gradient in the hero) by adding an `<img>` to `.hero-image` in `index.html`

### Adding more photos

The hero photo is `room-1.jpg`. To add more photos:

1. Save additional images in the same folder (e.g. `bathroom.jpg`, `building.jpg`)
2. To swap the hero image, just replace `room-1.jpg` with a new file of the same name
3. To add a gallery section, ask Claude to extend the page

Recommended: square or 4:5 vertical photos at ~1200px+ on the long edge work best.

---

## Adding Russian later

Russian translation will go in a separate `index.ru.html` file with a small language switcher in the nav. We'll do this after the English version is signed off.

## Notes on contact info

- Contact methods on the page: **Phone** (with 9 AM – 6 PM hours), **WhatsApp**, **Facebook**, and **Walk-in by appointment**
- The Facebook card links to: `https://www.facebook.com/profile.php?id=61566686698765`
- House rules notice: viewing by appointment before deposit, no pets allowed
