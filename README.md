# Aakara Icons

<p align="center">
  <img src="https://img.shields.io/badge/icons-100%2B-blue" alt="100+ Icons">
  <img src="https://img.shields.io/badge/CSS-only-green" alt="CSS Only">
  <img src="https://img.shields.io/badge/no_dependencies-✓-brightgreen" alt="No Dependencies">
  <img src="https://img.shields.io/badge/license-MIT-purple" alt="MIT License">
</p>

A pure CSS icon library using the `mask-image` technique. **100+ scalable icons** that inherit color from `currentColor`. No JavaScript, no font files, just CSS.

## ✨ Features

- 🎨 **Color Inheritance** — Icons automatically use `currentColor`, matching your text
- 📐 **Scalable** — Resize with simple HTML attributes or CSS
- ⚡ **Zero JavaScript** — Pure CSS solution, no runtime overhead
- 🔤 **No Font Files** — Uses inline SVG data URIs
- 🏷️ **Custom HTML Tags** — Semantic icon elements like `<heart-icon>`
- 🎯 **Attribute Modifiers** — Style with attributes: `<star-icon red large>`
- 🌈 **Gradient Icons** — Beautiful multicolor gradient variants
- 🌙 **Theme Ready** — Works perfectly with dark/light themes

## 📦 Installation

Simply include the CSS file in your HTML:

```html
<!-- Core icons (required) -->
<link rel="stylesheet" href="css/svg.css">

<!-- Gradient icons (optional) -->
<link rel="stylesheet" href="css/svg-color.css">
```

## 🚀 Quick Start

Use any icon as a custom HTML element:

```html
<menu-icon></menu-icon>
<search-icon></search-icon>
<heart-icon></heart-icon>
<star-icon></star-icon>
```

## 📏 Sizes

Control icon size with simple attributes:

```html
<heart-icon tiny></heart-icon>    <!-- 12px -->
<heart-icon xs></heart-icon>      <!-- 14px -->
<heart-icon small></heart-icon>   <!-- 16px -->
<heart-icon medium></heart-icon>  <!-- 20px -->
<heart-icon large></heart-icon>   <!-- 28px -->
<heart-icon xl></heart-icon>      <!-- 32px -->
<heart-icon xxl></heart-icon>     <!-- 40px -->
<heart-icon huge></heart-icon>    <!-- 64px -->
```

Aliases: `sm`, `md`, `lg`, `xl-2`, `xl-3`, `xl-4`, `xl-5`, `xl-6`, `xl-7`

## 🎨 Colors

### Basic Colors
```html
<star-icon red></star-icon>
<star-icon orange></star-icon>
<star-icon yellow></star-icon>
<star-icon green></star-icon>
<star-icon cyan></star-icon>
<star-icon blue></star-icon>
<star-icon purple></star-icon>
<star-icon pink></star-icon>
```

### Semantic Colors
```html
<check-icon success></check-icon>
<warning-icon warning></warning-icon>
<error-icon danger></error-icon>
<info-icon info></info-icon>
<star-icon primary></star-icon>
```

### Brand Colors
```html
<facebook-icon facebook></facebook-icon>
<twitter-icon twitter></twitter-icon>
<instagram-icon instagram></instagram-icon>
<youtube-icon youtube></youtube-icon>
<whatsapp-icon whatsapp></whatsapp-icon>
<discord-icon discord></discord-icon>
<github-icon github></github-icon>
<spotify-icon spotify></spotify-icon>
```

## 🎬 Animations

```html
<refresh-icon spin></refresh-icon>      <!-- Continuous rotation -->
<heart-icon pulse></heart-icon>         <!-- Pulsing effect -->
<bell-icon bounce></bell-icon>          <!-- Bouncing -->
<warning-icon shake></warning-icon>     <!-- Shaking -->
```

## 🔄 Transforms

```html
<chevron-right flip-h></chevron-right>  <!-- Horizontal flip -->
<chevron-right flip-v></chevron-right>  <!-- Vertical flip -->
<arrow-up rotate-90></arrow-up>         <!-- 90° rotation -->
<arrow-up rotate-180></arrow-up>        <!-- 180° rotation -->
```

## 👆 Hover Effects

```html
<heart-icon hover-grow></heart-icon>       <!-- Grows on hover -->
<settings-icon hover-spin></settings-icon> <!-- Spins on hover -->
<star-icon faded></star-icon>              <!-- 50% opacity -->
<star-icon semi></star-icon>               <!-- 75% opacity -->
```

## 🌈 Gradient Icons

Include `svg-color.css` for beautiful gradient variants:

```html
<heart-gradient></heart-gradient>
<star-gradient></star-gradient>
<sparkle-gradient></sparkle-gradient>
<instagram-gradient></instagram-gradient>
```

### Gradient Presets
```html
<heart-gradient sunset></heart-gradient>
<heart-gradient ocean></heart-gradient>
<heart-gradient aurora></heart-gradient>
<heart-gradient candy></heart-gradient>
<heart-gradient neon></heart-gradient>
<heart-gradient rainbow></heart-gradient>
<star-gradient gold></star-gradient>
<star-gradient holo></star-gradient>
```

### Glow Effect
```html
<heart-gradient glow></heart-gradient>
<star-gradient glow xl></star-gradient>
```

## 🔗 Combining Attributes

Mix and match any attributes:

```html
<send-icon red large></send-icon>
<heart-icon pink xl pulse></heart-icon>
<refresh-icon blue xxl spin></refresh-icon>
<settings-icon gray large hover-spin></settings-icon>
<star-gradient gold huge glow></star-gradient>
```

## 📚 Available Icons

### Navigation & Actions
`menu-icon`, `search-icon`, `home-icon`, `settings-icon`, `close-icon`, `download`, `upload-icon`, `edit-icon`, `delete-icon`, `share-icon`, `link-icon`, `external-link`, `refresh-icon`, `plus-icon`, `minus-icon`, `copy-icon`, `save-icon`, `print-icon`

### Status & Indicators
`check-icon`, `error-icon`, `warning-icon`, `info-icon`, `heart-icon`, `star-icon`, `bookmark-icon`, `bell-icon`, `eye-icon`, `eye-off-icon`, `lock-icon`, `unlock-icon`, `user-icon`, `mail-icon`, `phone-icon`, `sun-icon`, `moon-icon`

### Arrows & Chevrons
`arrow-up`, `arrow-down`, `arrow-left`, `arrow-right`, `chevron-up`, `chevron-down`, `chevron-left`, `chevron-right`, `expand-icon`, `collapse-icon`, `double-arrow-left`, `double-arrow-right`

### AI & Technology
`brain-icon`, `robot-icon`, `chip-icon`, `sparkle-icon`, `chat-bot-icon`, `lightbulb-icon`, `code-icon`, `wand-icon`, `data-icon`, `terminal-icon`, `workflow-icon`, `layers-icon`, `cpu-icon`, `network-icon`, `bolt-icon`

### Chat & Interface
`new-chat-icon`, `new-file-icon`, `new-note-icon`, `sidebar-icon`, `sidebar-left-icon`, `sidebar-right-icon`, `chat-icon`, `message-icon`, `comment-icon`, `history-icon`

### Social Media
`facebook-icon`, `twitter-icon`, `x-icon`, `instagram-icon`, `linkedin-icon`, `youtube-icon`, `tiktok-icon`, `github-icon`, `discord-icon`, `slack-icon`, `whatsapp-icon`, `telegram-icon`, `messenger-icon`, `snapchat-icon`, `reddit-icon`, `pinterest-icon`, `dribbble-icon`, `twitch-icon`, `spotify-icon`, `medium-icon`

### Email & Communication
`gmail-icon`, `outlook-icon`, `send-icon`, `at-icon`, `inbox-icon`

### Gradient Variants
`heart-gradient`, `star-gradient`, `sparkle-gradient`, `bolt-gradient`, `brain-gradient`, `robot-gradient`, `wand-gradient`, `lightbulb-gradient`, `instagram-gradient`, `tiktok-gradient`, `messenger-gradient`, `fire-gradient`, `diamond-gradient`, `crown-gradient`, `rocket-gradient`, `music-gradient`, `camera-gradient`, `palette-gradient`, `globe-gradient`

## 🎯 Use Cases

### Buttons
```html
<button>
    <download></download>
    Download
</button>
```

### Navigation
```html
<nav>
    <a href="#"><home-icon></home-icon> Home</a>
    <a href="#"><search-icon></search-icon> Search</a>
    <a href="#"><user-icon></user-icon> Profile</a>
</nav>
```

### Status Indicators
```html
<span><check-icon success></check-icon> Completed</span>
<span><warning-icon warning></warning-icon> Pending</span>
<span><error-icon danger></error-icon> Failed</span>
```

## 🛠️ How It Works

Aakara Icons uses the CSS `mask-image` property with inline SVG data URIs:

```css
heart-icon {
    display: inline-block;
    width: 24px;
    height: 24px;
    background-color: currentColor;
    mask-image: url("data:image/svg+xml,...");
    mask-repeat: no-repeat;
    mask-size: 100% 100%;
}
```

This approach allows icons to:
- Inherit color from parent elements
- Scale without quality loss
- Work without external requests
- Be styled with CSS

## 📄 License

MIT License - feel free to use in personal and commercial projects.

---

<p align="center">
  Made with ❤️ by the Aakara team
</p>
