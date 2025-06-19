# Wix Custom Preloader Script for India Day Website

A full-screen custom preloader for Wix websites featuring a zoom-in logo animation with colorful particle explosion effects. This preloader overlays the entire viewport — including header, footer, and all page content — and fades out smoothly after the animation completes.

---

## 🎬 Demo

Here is a demo of what the preloader animation looks like:

![Custom Preloader Animation](./preloader.gif)

---

## Features

- Covers the entire viewport (header, footer, and page content)
- Zoom-in animation on your custom logo or image
- Colorful particle explosion effects
- Smooth fade-out after 6 seconds (configurable)
- Responsive design for mobile devices

---

## Prerequisites

- A Wix website with access to the **Wix Editor** and **Wix Dashboard**
- Your preloader image uploaded to Wix Media Manager
- Basic familiarity with Wix Editor and Wix Dashboard

---

## Setup Instructions

### 1. Upload Your Preloader Image to Wix Media Manager

1. Open your Wix site in the **Wix Editor**.
2. Click **Media** (left panel).
3. Click **Upload Media** → **Upload from Computer**.
4. Select your preloader image file (PNG, GIF, etc.).
5. After upload, click the image → **File Info** → copy the **direct URL**.

### 2. Update the Preloader Code with Your Image URL

1. Open the code snippet file (`preloader.html` or your custom code file).
2. Find the placeholder `YOUR_IMAGE_URL_HERE`.
3. Replace it with your copied image URL, for example:

   ```
   
   ```

### 3. Add the Custom Code to Wix Dashboard

1. Go to your **Wix Dashboard** (not the Editor).
2. Navigate to **Settings** → **Custom Code**.
3. Click **+ New Custom Code**.
4. Paste the entire updated code snippet (HTML, CSS, and JavaScript) into the code box.
5. Under **Add Code to Pages**, select **All Pages** (or specific pages if preferred).
6. Under **Place Code In**, select **Head**.
7. Save and **Publish** your site.

### 4. Test Your Preloader

1. Open your published Wix website in a new browser tab.
2. The preloader overlay with your custom image should appear, zoom in, and trigger particle explosions.
3. After approximately 6 seconds, the preloader fades out smoothly, revealing your site content.

---

## Customization

- **Background Color:** Change the `background-color` in the CSS `#preloader` selector.
- **Animation Timing:** Adjust the durations in the JavaScript `setTimeout` calls.
- **Particle Colors:** Modify the `colors` array in the JavaScript.
- **Responsive Settings:** Tweak CSS media queries for different screen sizes.

---

## Troubleshooting

- If the preloader does not appear, verify that the custom code is added to the **Head** section and published.
- Confirm your image URL is correct and publicly accessible.
- Wix Preview mode may not fully support custom code; always test on the **live published site**.
- Clear browser cache if changes do not show immediately.

\