# Les Toises - Project Documentation

**Project URL:** https://saheel-ahmed.github.io/lestoises/

---

## 📋 Table of Contents
1. [Symptoms & Icons](#symptoms--icons)
2. [Fonts (Typefaces)](#fonts-typefaces)
3. [Images](#images)
4. [Videos](#videos)
5. [Color Codes](#color-codes)

---

## 🏥 Symptoms & Icons

### Mental Health Symptoms with Associated Icons and Emojis

The project includes the following symptoms and their corresponding visual representations used in the wizard form:

| # | Symptom | Icon/Emoji | Color Background | Hex Color |
|---|---------|-----------|------------------|-----------|
| 1 | Depression / Sadness / Low mood | 🌧️ | Purple (100) | `#9333EA` |
| 2 | Anxiety / Social anxiety / Panic / OCD tendencies | 🌃 | Blue (100) | `#3B82F6` |
| 3 | Substance use / Addiction | 🧴 | Red (100) | `#DC2626` |
| 4 | Sleep problems | 🌙 | Green (100) | `#16A34A` |
| 5 | Anger issues | 🔥 | Orange (100) | `#EA580C` |
| 6 | Trauma / PTSD | 🛡️ | Teal (100) | `#14B8A6` |
| 7 | Self-discovery | 🔎 | Cyan (100) | `#06B6D4` |
| 8 | Eating problems / Eating disorders | 🍽️ | Pink (100) | `#EC4899` |

### Material Symbols Icons Used

- `health_and_safety` - Therapist indicator
- `person` - Patient/User indicator
- `mic` - Microphone/Audio feature
- `photo_library` - Photo gallery

---

## 🔤 Fonts (Typefaces)

### Primary Font Families

| Font Family | Weights | Used In | Source |
|-------------|---------|---------|--------|
| **Montserrat** | 400, 500, 700, 800 | `index.html`, `wizard.html` | Google Fonts |
| **Roobert** | 400, 500, 700, 800 | `list.html`, `profile.html` | Google Fonts |
| **Material Symbols Outlined** | Variable (100-700) | All pages | Google Fonts |
| **Sans-serif** | Default | Fallback font | System |

### Font Configuration (Tailwind)
```javascript
fontFamily: {
    "display": ["Montserrat", "sans-serif"]  // or ["Roobert", "sans-serif"]
}
```

### Google Fonts Import Links
```html
<!-- Montserrat -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700;800&display=swap" rel="stylesheet" />

<!-- Roobert -->
<link href="https://fonts.googleapis.com/css2?family=Roobert:wght@400;500;700;800&display=swap" rel="stylesheet" />

<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap" rel="stylesheet" />
```

---

## 🖼️ Images

### Image Assets Location
All images are located in: `/assets/img/`

### Complete Image List

| Filename | Type | Purpose | Dimensions |
|----------|------|---------|------------|
| `lestoises-logo.png` | PNG | Main logo (colored) | Default |
| `lestoises-logo-white.png` | PNG | Logo (white variant) | Default |
| `lestoises-logo.svg` | SVG | Logo (vector format) | Scalable |
| `lestoises-app-256x256.png` | PNG | App icon | 256x256px |
| `lestoises-app-screens.png` | PNG | App screenshot mockup | Default |
| `header-min.png` | PNG | Header/hero image | Optimized |
| `abstract-background.png` | PNG | Background decoration | Default |
| `robo.png` | PNG | Robotic AI assistant (Tamara) | Default |
| `secure-ssl.png` | PNG | SSL/Security badge | Default |
| `logo-1.png` to `logo-5.png` | PNG | Alternative logo variants | Default |
| `a1.jpg` | JPG | Profile gallery image 1 | Default |
| `a1.2.jpg` | JPG | Profile gallery image 1.2 | Default |
| `a2.jpg` | JPG | Profile gallery image 2 | Default |
| `a3.jpg` | JPG | Profile gallery image 3 | Default |
| `peakpx_1.jpg` | JPG | Stock/background image | Default |

---

## 🎬 Videos

### Video Assets Location
All videos are located in: `/assets/video/`

### Complete Video List

| Filename | Purpose | Format |
|----------|---------|--------|
| `header.mp4` | Header/Hero video section | MP4 |
| `intro.mp4` | Introduction/intro video | MP4 |
| `v1.mp4` | Promotional/feature video 1 | MP4 |
| `v2.mp4` | Promotional/feature video 2 | MP4 |

### Video Implementation
Videos are embedded using HTML5 `<video>` tag with autoplay, loop, and muted attributes:
```html
<video autoplay="" loop="" muted="" playsinline="">
    <source src="path/to/video.mp4" type="video/mp4" />
</video>
```

---

## 🎨 Color Codes

### Brand Colors

| Color Name | Hex Code | RGB | Usage |
|------------|----------|-----|-------|
| **Brand Primary** | `#9C804E` | rgb(156, 128, 78) | Main branding, buttons, links, headers |
| **Brand Secondary** | `#FAF8F3` | rgb(250, 248, 243) | Secondary background, light theme |
| **Background Light** | `#FFFFFF` | rgb(255, 255, 255) | Light mode background |
| **Background Dark** | `#101921` | rgb(16, 25, 33) | Dark mode background |

### AI-Themed Gradient Colors (Gemini Style)

| Color Name | Hex Code | RGB | Position | Usage |
|------------|----------|-----|----------|-------|
| **AI Start (Violet)** | `#8B5CF6` | rgb(139, 92, 246) | Start | Gradient beginning |
| **AI Middle (Pink)** | `#EC4899` | rgb(236, 72, 153) | Middle | Gradient middle |
| **AI End (Cyan)** | `#06B6D4` | rgb(6, 182, 212) | End | Gradient ending |

### Gemini Gradient Definition
```css
.gemini-gradient {
    background: linear-gradient(90deg, #4285F4, #9B72CB, #D96570, #F2A60C);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.gemini-icon-gradient {
    background: linear-gradient(135deg, #4285F4, #9B72CB, #D96570, #F2A60C);
}
```

### Google Brand Colors (Gemini reference)
| Color | Hex Code | RGB |
|-------|----------|-----|
| Google Blue | `#4285F4` | rgb(66, 133, 244) |
| Google Purple | `#9B72CB` | rgb(155, 114, 203) |
| Google Red/Pink | `#D96570` | rgb(217, 101, 112) |
| Google Yellow/Orange | `#F2A60C` | rgb(242, 166, 12) |

### Symptom Category Colors (Tailwind)

| Symptom | Tailwind Class | Hex Code |
|---------|---|---|
| Depression | `purple-600` / `purple-100` | `#9333EA` / `#F3E8FF` |
| Anxiety | `blue-600` / `blue-100` | `#2563EB` / `#DBEAFE` |
| Substance Use | `red-600` / `red-100` | `#DC2626` / `#FEE2E2` |
| Sleep Problems | `green-600` / `green-100` | `#16A34A` / `#DCFCE7` |
| Anger Issues | `orange-600` / `orange-100` | `#EA580C` / `#FFEDD5` |
| Trauma | `teal-600` / `teal-100` | `#14B8A6` / `#CCFBF1` |
| Self-discovery | `cyan-600` / `cyan-100` | `#06B6D4` / `#CFFAFE` |
| Eating Disorders | `pink-600` / `pink-100` | `#EC4899` / `#FCE7F3` |

### Neutral Colors

| Color | Hex Code | Usage |
|-------|----------|-------|
| White | `#FFFFFF` | Primary background, text background |
| Gray 100 | `#F3F4F6` | Light backgrounds |
| Gray 600 | `#4B5563` | Text, secondary content |
| Gray 800 | `#1F2937` | Primary text |
| Black | `#000000` | Dark mode backgrounds |

---

## 🎯 Additional Design Elements

### Border Radius
```javascript
borderRadius: {
    "DEFAULT": "0.25rem",
    "lg": "0.5rem",
    "xl": "0.75rem",
    "full": "9999px"
}
```

### Animations
- **fadeIn**: 1s, ease-out
- **slideInUp**: 0.8s, ease-out
- **slideInRight**: 0.8s, ease-out
- **zoomIn**: 0.8s, ease-out
- **float**: 4s, ease-in-out infinite
- **pulse**: 3s, cubic-bezier(0.4, 0, 0.6, 1) infinite

### Dark Mode
The project uses Tailwind's `dark` class mode with:
- Dark mode class: `"class"`
- Configuration: Both light and dark variants defined

---

## 📱 Pages Overview

| Page | Purpose | Font | Key Features |
|------|---------|------|--------------|
| `index.html` | Home page | Montserrat | Hero, features, CTAs |
| `list.html` | Services/listings | Roobert | Grid layouts, counters |
| `wizard.html` | Symptom questionnaire | Montserrat | Multi-step form, symptom selection |
| `profile.html` | Therapist profile | Roobert | Media gallery, profile details |
| `index-2.html` | Alternative home | Montserrat | Variant design |

---

**Last Updated:** January 13, 2026
**Repository:** https://github.com/saheel-ahmed/lestoises
