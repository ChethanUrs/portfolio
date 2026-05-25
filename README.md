# 🍃 Handcrafted Sketchbook & Travel-Journal Portfolio

Welcome to the digital sketchbook of **Chethan Raje Urs K**, a BCA student at Amrita Vishwa Vidyapeetham, Mysuru Campus.

This repository contains a stunning, one-of-a-kind, handcrafted portfolio website designed to feel like a beautifully hand-bound travel journal or artist's diary—warm, earthy, story-driven, and deeply human.

---

## 🎨 Design System & Aesthetics

*   **Google Fonts**: `Fraunces` (an expressive, organic serif used for elegant headings and italic accents) and `Lora` (a soft, literary serif for body text).
*   **Warm Earthy Color Palette**:
    *   `#fbf8f3` (Parchment background)
    *   `#f5eedc` (Tactile scrap cards)
    *   `#2c1e15` (Deep ink brown text and outlines)
    *   `#c96547` (Warm Terracotta accent)
    *   `#708a76` (Sage Green nature accent)
    *   `#c9a84c` (Saffron Gold cultural accent)
*   **Tactile Textures**:
    *   **SVG Noise**: An inline SVG `feTurbulence` fractal noise filter fixed as a body overlay to give the page physical paper grain texture.
    *   **Torn Edges**: Inline SVGs that mask section borders to create a rough, hand-cut paper look.
    *   **Ink Strokes**: Hand-drawn brush strokes acting as transition dividers between pages.
    *   **Vignette Shadow**: A soft inset radial shadow framing the entire screen to evoke a bounded sketchbook.

---

## ✦ Interactive Micro-interactions

1.  **Physics-Based Leaf Cursor**: A custom leaf (`🍃`) trailing behind the pointer on a full-screen canvas with spring forces, inertia, and a trail of gold and green sparkles.
2.  **watercolor Gradient Mesh**: Soft, blending watercolor blobs on the hero section background that shift and react dynamically to mouse movement using spring-damped interpolation.
3.  **Mechanical Typewriter Tagline**: Types out `"Designing thoughtful web applications and interactive experiences."` on load with organic variable pauses mimicking a physical typewriter.
4.  **Tilted Project Cards**: Scrapbook-style cards that lift, tilt by `±1.8°`, and expand their shadows when hovered.
5.  **Collector's Stamp Passport**: An achievements grid displaying vintage scalloped postage stamps that rotate dynamically. Hovering over a stamp triggers a wax-seal "crack" animation and expands a detailed description drawer.
6.  **Smudging Postcard Socials**: Interactive round social ink-stamps on a vintage letter postcard that depress and wobble as if stamping physical ink onto paper.

---

## ⚙️ Technical Highlights

*   **Single File Structure**: All HTML, CSS design styles, and interactive JavaScript are self-contained inside a single `index.html` file for portability and speed.
*   **100% Inline SVGs**: Zero broken links or external assets; every illustration (from the compass to the Mysuru Palace starry landscape, to project illustrations) is drawn with native SVG vectors.
*   **Scroll-Triggered Reveals**: Uses the highly efficient `IntersectionObserver` API in vanilla JavaScript to fade in sections smoothly as you turn the pages.
*   **Fully Responsive**: Built mobile-first, maintaining paper texture integrity and stacking gracefully down to 320px screen width.

---

## 🚀 How to Run Locally

Since the codebase is completely self-contained in a single static file, you can run it instantly:

1.  Clone this repository:
    ```bash
    git clone https://github.com/ChethanUrs/portfolio.git
    cd portfolio
    ```
2.  Open `index.html` directly in your default web browser, or launch a local development server:
    ```bash
    # Using Python
    python -m http.server 8000
    
    # Or using Node static server
    npx http-server -p 8000
    ```
3.  Navigate to `http://localhost:8000` to interact with the design.

---

## 🛠️ Personalization

To modify the descriptions, platforms, or links of the items in the **Collector's Stamp** passport section, open `index.html` and search for the `⚠️ VERIFY` comments (lines `~715` to `~965`) to tailor them to your credentials.
