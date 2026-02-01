# 💍 Nithish & Rajalakshmi Wedding Invitation

A premium, elegant, and interactive digital wedding invitation built with modern web technologies.

## ✨ Features

- **Interactive Welcome Page**: A beautiful landing page with an animated envelope reveal.
- **Premium Aesthetics**: Carefully curated color palette featuring Royal Maroon, Gold, and Deep Espresso Brown.
- **Smooth Animations**:
  - Slide-in effects for the Groom & Bride cards.
  - Floating hearts and rose petals animations.
  - Staggered reveal for section contents.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop viewing.
- **Background Music**: Integrated audio player with a custom-themed toggle.
- **Interactive Gallery**: A "Happy Moments" section with a sleek lightbox for high-resolution photo viewing.
- **Countdown Timer**: Real-time wedding countdown.
- **Venue Details**: Vertical layout with integrated Google Maps links.

## 🛠️ Technology Stack

- **HTML5**: Semantic structure.
- **CSS3**: Custom styling with Flexbox, CSS Grid, and Keyframe animations.
- **JavaScript (Vanilla)**: Interaction logic, countdown timer, and Intersection Observer for scroll animations.
- **Font Awesome**: Elegant iconography.
- **Google Fonts**: Cinzel, Tangerine, Cormorant Garamond, and Poppins.

## 🚀 Deployment Instructions (Cloudflare Pages)

To host this invitation on Cloudflare Pages:

1. **Connect Repository**: Link your GitHub/GitLab repo to Cloudflare Pages.
2. **Build Settings**:
   - **Framework Preset**: None
   - **Build Command**: (Leave Blank)
   - **Build Output Directory**: `/` (or `.` to indicate the root directory)
3. **Environment**: Ensure all assets (images/audio) are in the root or correctly referenced.

### ⚠️ Common 404 Fix
If your site shows a "404 Not Found" after a successful build:
- Go to **Settings > Build & deployments** in Cloudflare.
- Ensure the **Build output directory** is set to the root (where your `index.html` is). 
- If you see a `/` or `./`, that is usually correct. If it says `dist` or `public`, change it to `/`.

## 📁 File Structure

```text
├── index.html          # Main application structure
├── style.css           # Custom styling and animations
├── script.js           # Interactive logic and timers
├── ganesha.png         # Traditional intro image
├── bride.jpg           # Bride's profile photo
├── groom.jpg           # Groom's profile photo
├── gallery-1.jpg       # Gallery placeholder 1
├── gallery-2.jpg       # Gallery placeholder 2
├── floral-left.png     # Decorative elements
├── floral-right.png    # Decorative elements
├── vector-1.png        # Wedding ceremony illustration 1
├── vector-2.png        # Wedding ceremony illustration 2
└── wedding-music1.mp3  # Background music track
```

## 💖 Credits
Designed for the celebration of Nithish S & Rajalakshmi N.
