# 🇦🇪 Arabic Word Builder Tool

A lightweight, mobile-responsive web tool designed to build Arabic words using four customizable letter sets. This tool is optimized for GitHub Pages and bypasses the script restrictions of basic website builders.

## 📁 Project Structure

To ensure the script functions correctly, maintain the following directory structure:

* `index.html` - The main application code.
* 📁 `set0/` - Images for the **Starter** position (Far Right).
* 📁 `set1/` - Images for the **Original** position.
* 📁 `set2/` - Images for the **Outcome** position.
* 📁 `set3/` - Images for the **Pre-Outcome** position (Far Left).

## 🖼️ Image Requirements

Each folder (`set0` through `set3`) must contain 28 images.
- **Format:** SVG (recommended) or PNG/JPG.
- **Naming:** Files must be named according to their index in the Arabic alphabet (0 to 27).
  - `0.svg` (أ)
  - `1.svg` (ب)
  - ...and so on.
- **Dimensions:** The tool displays images at a maximum of **3cm x 3cm**. For best results, use square assets with transparent backgrounds.

## 🚀 How to Host (Free)

### GitHub Pages (Recommended)
1.  Create a new repository on GitHub.
2.  Upload `index.html` and the four `set` folders.
3.  Go to **Settings > Pages**.
4.  Select the **main** branch and click **Save**.
5.  Your site will be live at `https://[your-username].github.io/[repo-name]/`.

### Tiiny.host
1.  Zip `index.html` and the image folders together.
2.  Upload the `.zip` file to [tiiny.host](https://tiiny.host).
3.  Set your link name and launch.

## 📱 Features
- **RTL Support:** The layout and word preview follow standard Arabic Right-to-Left flow.
- **Mobile Optimized:** Uses CSS Grid to force a 4-column layout that never stacks, even on small screens.
- **No Dependencies:** Written in pure HTML/CSS and Vanilla JavaScript.
