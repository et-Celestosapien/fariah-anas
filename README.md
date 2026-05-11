# Wedding Invitation Site 💍

A premium, modern, and highly interactive wedding invitation web application built with React, Vite, and Framer Motion. This site features a minimalist aesthetic with a soft color palette (gold, tea pink), smooth animations, and a fully responsive design.

## ✨ Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop viewing.
- **Interactive Map**: Integrated Google Maps with a "Get Directions" button using precise coordinates.
- **Save the Date Calendar**: Visual calendar highlighting the big day.
- **Dynamic Animations**: Smooth scroll reveals and micro-interactions powered by Framer Motion.
- **RSVP & Contact**: Easy access to contact information for guests.
- **Premium Aesthetics**: Glassmorphism effects, custom typography, and a cohesive "Tea Pink & Gold" theme.
- **Meta Tags**: Pre-configured Open Graph tags for rich previews when shared on WhatsApp and social media.

## 🛠️ Tech Stack

- **Frontend**: React 19 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + Custom Vanilla CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Components**: Radix UI + Custom Glassmorphism components

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/et-celestosapien/fariah-anas.git
   cd fariah-anas
   ```

2. Navigate to the app directory:
   ```bash
   cd app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

## ⚙️ Configuration & Customization

The invitation data is centralized in a single configuration file, making it easy to customize for different events.

Edit **`app/src/config/invitation.ts`** to update:
- Groom & Bride details
- Event date (Gregorian & Hijri)
- Venue name, address, and coordinates
- RSVP contact information

```typescript
// Example configuration in invitation.ts
export const invitationData = {
  groom: { name: "...", fatherName: "..." },
  venue: {
    address: "C-551, main Allama Iqbal Rd, ...",
    lat: 24.872755,
    lng: 67.058163,
    // ...
  },
  // ...
};
```

## 🌐 Deployment

The project is designed to be deployed on static hosting services like GitHub Pages, Vercel, or Netlify. 

To deploy to GitHub Pages:
1. Run `npm run build`.
2. Push the contents of the `dist` folder to your `gh-pages` branch.

## 📄 License

This project is private and intended for personal use.

---
*Created with ❤️ for Anas & Fariah's special day.*
