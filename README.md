# emberTheme

<p align="center">
  <img src="assets/Funds%20and%20Surfaces.png" alt="emberTheme Preview">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Theme-emberTheme-a64b5f?style=for-the-badge" alt="Theme Badge">
  <img src="https://img.shields.io/badge/Palette-Warm%20Dark-181311?style=for-the-badge" alt="Palette Badge">
  <img src="https://img.shields.io/badge/Contrast-Soft%20Muted-c7b8ae?style=for-the-badge" alt="Contrast Badge">
  <img src="https://img.shields.io/badge/Syntax-Cinematic-d27a4a?style=for-the-badge" alt="Syntax Badge">
</p>

A warm dark theme focused on low visual fatigue, muted contrast, and cinematic color balance.
Inspired by the structural consistency of themes such as Dracula and Monokai, while maintaining its own earthy and restrained visual identity.

---

# Color Philosophy

`emberTheme` combines deep brown-black surfaces with dry wine accents and warm ember highlights.
The palette prioritizes:

* Reduced eye strain in long coding sessions
* Clear visual hierarchy
* Controlled saturation
* Balanced warm and cold accents
* Readable syntax contrast without excessive brightness

---

# Funds and Surfaces

Core background layers used across the editor interface, panels, overlays, and elevated components.

| Token    | Color     | Usage                      |
| -------- | --------- | -------------------------- |
| `bg-0`   | `#120e0c` | Absolute background        |
| `bg-1`   | `#181311` | Main editor surface        |
| `bg-2`   | `#211a17` | Sidebars and panels        |
| `bg-3`   | `#2a221e` | Hover and selection states |
| `bg-4`   | `#342b26` | Elevated UI elements       |
| `border` | `#3f3530` | Borders and separators     |

![Funds And Surfaces](assets/Funds%20and%20Surfaces.png)

---

# Typography and Text

Text colors are designed to preserve readability while avoiding aggressive white contrast.

| Token            | Color     | Usage                   |
| ---------------- | --------- | ----------------------- |
| `text-primary`   | `#f2e7df` | Primary content         |
| `text-secondary` | `#c7b8ae` | Secondary content       |
| `text-muted`     | `#8f7f75` | Comments and subdued UI |
| `text-disabled`  | `#655852` | Disabled states         |

![Texts](assets/Texts.png)

---

# Primary Accent — Dry Wine

The primary accent palette defines interaction states and editor emphasis.

| Token            | Color     | Usage                     |
| ---------------- | --------- | ------------------------- |
| `accent-primary` | `#a64b5f` | Primary accent            |
| `accent-hover`   | `#bb5d72` | Hover states              |
| `accent-active`  | `#8d3e50` | Active and pressed states |
| `accent-soft`    | `#4b2a31` | Soft accent backgrounds   |

![Primary Accent](assets/Primary%20Accent.png)

---

# Warm Secondary Accents

Warm complementary tones used for highlights, constants, and supporting interactions.

| Token        | Color     | Usage                   |
| ------------ | --------- | ----------------------- |
| `ember`      | `#d27a4a` | Highlights              |
| `amber-soft` | `#b86b43` | Warm interaction states |
| `gold-muted` | `#c29a5f` | Numbers and constants   |

![Warm Secondary Accents](assets/Warm%20Secondary%20Accents.png)

---

# Cold Contrast Accents

Cool-toned accents provide separation and improve syntax readability.

| Token        | Color     | Usage                            |
| ------------ | --------- | -------------------------------- |
| `teal`       | `#5fa38f` | Constants                        |
| `cyan-muted` | `#6f9caa` | Links and informational elements |
| `blue-steel` | `#58718a` | Technical UI elements            |

![Cold Contrast Accents](assets/Cold%20Contrast%20Accents.png)

---

# Semantic Colors

Semantic colors preserve consistency across validation, feedback, and alert states.

| Token     | Color     | Usage                          |
| --------- | --------- | ------------------------------ |
| `success` | `#6caa7a` | Success states                 |
| `warning` | `#d39a54` | Warning states                 |
| `danger`  | `#c15b58` | Errors and destructive actions |

![Semantic Colors](assets/Semantic%20Colors.png)

---

# Syntax Highlighting

Syntax colors are intentionally restrained to maintain focus and reduce visual noise.

| Token             | Color     | Usage             |
| ----------------- | --------- | ----------------- |
| `syntax-keyword`  | `#a64b5f` | Keywords          |
| `syntax-string`   | `#d27a4a` | Strings           |
| `syntax-function` | `#e6c1a8` | Functions         |
| `syntax-type`     | `#c78b6b` | Types and classes |
| `syntax-constant` | `#5fa38f` | Constants         |
| `syntax-number`   | `#c29a5f` | Numbers           |
| `syntax-comment`  | `#6f5e57` | Comments          |

![Syntax Highlighting](assets/Syntax%20Highlighting.png)

---

# Cursor and Selection

Selection and cursor colors are tuned for visibility without disrupting the overall palette balance.

| Token       | Color     | Usage          |
| ----------- | --------- | -------------- |
| `selection` | `#4b2f35` | Text selection |
| `cursor`    | `#f2d2ba` | Cursor         |

![Cursor And Selection](assets/Cursor%20and%20Selection.png)

---

# Design Characteristics

| Property            | Description                               |
| ------------------- | ----------------------------------------- |
| Contrast Model      | Soft contrast                             |
| Palette Temperature | Warm dominant with cold balancing accents |
| Saturation          | Muted                                     |
| UI Style            | Cinematic dark                            |
| Readability Target  | Long-duration coding sessions             |
| Accent Strategy     | Wine-red primary with ember highlights    |

---

# Recommended Usage

`emberTheme` works particularly well for:

* Terminal-focused workflows
* Backend development
* Reverse engineering environments
* Long reading sessions
* Low-light setups
* Minimal and distraction-reduced interfaces
