# SMART AUTOTRONICS — Official Website & Landing Page

Welcome to your production-ready, single-page website for **SMART AUTOTRONICS** (`Vehicle Meter Services & Automotive Electronics`).

## 📁 File Structure
- `index.html`: Contains the complete, single-page **HTML, CSS, and JavaScript** built to ultra-modern, high-performance automotive aesthetics.

---

## 🚀 How to Host Immediately for Free on GitHub Pages

1. **Create a GitHub Repository**:
   - Go to [github.com](https://github.com) and click **New Repository**.
   - Name your repository (e.g., `smart-autotronics-website` or `yourusername.github.io`).
   - Make sure it is set to **Public**.

2. **Upload `index.html`**:
   - Upload `index.html` directly to the root of your repository (and commit the change).

3. **Enable GitHub Pages**:
   - In your GitHub repository, go to **Settings** > **Pages** (in the left sidebar).
   - Under **Branch**, select `main` (or `master`) and folder `/ (root)`.
   - Click **Save**.
   - Within 1–2 minutes, your website will be live at `https://yourusername.github.io/smart-autotronics-website/`!

---

## 🎨 Customizing Your Logo & Engine Sound

### 1. Adding Your Custom Logo
In `index.html` around **line 295**, locate the logo container:
```html
<div class="brand-logo-container">
    <i class="fa-solid fa-gauge-high brand-logo-placeholder-icon"></i>
    <img src="logo-placeholder.png" alt="SMART AUTOTRONICS Logo" class="brand-logo" id="brandLogo">
</div>
```
- Replace `src="logo-placeholder.png"` with your uploaded logo file name (for example, `src="smart-autotronics-logo.png"` after uploading your logo image file into the same folder).
- The page will automatically detect the image and display it cleanly alongside your **SMAR<span style="color: #ff0000;">T</span> AUTOTRONICS** header text!

### 2. Adding Your Engine Rev Sound
Around **line 267**, locate the audio tag:
```html
<audio id="revAudio" preload="auto">
    <source src="rev-sound.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
```
- Upload your engine sound file (`rev-sound.mp3`) into the exact same directory as `index.html`.
- When visitors click the **"START ENGINE"** button upon entering the site, the high-performance car revving sound will play automatically as the dashboard HUD tachometer revs up to 6,800 RPM and smoothly reveals your website!

---

## 📱 Core Features Built-In
- **Crucial Audio Entry Screen**: Bypasses browser auto-play restrictions using a sleek, stylized "Start Engine" overlay.
- **Brand Identity & Accent Styling**: Prominent **SMAR<span style="color: #ff0000;">T</span> AUTOTRONICS** styling with deep black backgrounds (`#08080c`) and bold red neon accents (`#ff0000`).
- **Niche Focus**: Highlights **Vehicle Meter Services** front and center, alongside **ECM Repairing**, **Key Programming**, and **Car Scanning / Diagnosis**.
- **Interactive WhatsApp Diagnostics Estimator**: Visitors can select their vehicle type, issue description, and model to generate an instant, pre-filled WhatsApp lead sent directly to `+917736284122`.
- **100% Responsive Grid**: Optimized for mobile phones, tablets, and wide desktop displays with a custom responsive mobile drawer menu.
