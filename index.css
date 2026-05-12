@import "tailwindcss";
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100..900;1,100..900&family=Outfit:wght@100..900&display=swap');

@theme {
  --font-sans: "Inter", ui-sans-serif, system-ui, sans-serif;
  --font-display: "Outfit", sans-serif;
  
  --color-brand-red: #CC0000;
  --color-brand-black: #050505;
  --color-brand-grey: #262626;
}

@layer base {
  body {
    @apply bg-brand-black text-white selection:bg-brand-red selection:text-white overflow-hidden;
    font-family: var(--font-sans);
  }
}

@layer components {
  .brush-stroke {
    mask-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="20" viewBox="0 0 100 20"><path d="M0 10 Q 25 0 50 10 T 100 10 L 100 20 L 0 20 Z" fill="black"/></svg>');
    mask-size: 100% 100%;
  }
  
  .text-outline {
    -webkit-text-stroke: 1px rgba(255, 255, 255, 0.2);
  }

  .shadow-red {
    box-shadow: 0 0 30px rgba(204, 0, 0, 0.4);
  }
}

/* Custom brush slash for the diagonal background */
.brush-slash {
  position: absolute;
  background: var(--color-brand-black);
  clip-path: polygon(0% 20%, 100% 0%, 100% 100%, 0% 100%);
  filter: drop-shadow(0 -10px 10px rgba(0,0,0,0.5));
}

/* Gritty texture overlay */
.gritty-overlay {
  position: fixed;
  inset: 0;
  pointer-events: none;
  opacity: 0.05;
  background-image: url('data:image/svg+xml;utf8,<svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"><filter id="noiseFilter"><feTurbulence type="fractalNoise" baseFrequency="0.65" numOctaves="3" stitchTiles="stitch" /></filter><rect width="100%" height="100%" filter="url(%23noiseFilter)" /></svg>');
}
