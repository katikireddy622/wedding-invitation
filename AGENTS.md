# AGENTS.md

Act as an expert Creative Frontend Developer. 

Task: Build a single-page, mobile-optimized, highly aesthetic interactive Wedding Invitation web application inspired by luxury Indian print & digital invitation cards.

### Visual Aesthetic & Layout Requirements:
1. Palette & Atmosphere:
   - Background: Soft textured ivory/cream (`#FDFBF7`) with subtle Indian jali/mandala pattern overlays.
   - Accents: Rose gold, muted maroon, soft blush pink, leaf green, and warm gold filigree.
   - Main Container: A centered, mobile-first card framed inside a classic Indian Archway (Mughal/Rajasthani architectural arch outline) with smooth outer drop shadows.

2. Framing & Decorative Elements:
   - Header Decorations: Dual hanging vintage brass/rose-gold lanterns at the top corners with subtle glowing flame CSS animations. Lush watercolor tropical & botanical flora (anthuriums, eucalyptus leaves) framing the top and bottom borders.
   - Custom Monogram: Centered inside a double-lined arch/shield frame at the top (e.g., custom couple initials badge).

3. Illustration & Content Section:
   - Centerpiece Illustration: An illustrated couple in traditional wedding attire (Bridal Lehengha in magenta/red and Groom in Sherwani with Safa turban). Keep the minimalist/faceless vector aesthetic or provide an easily swappable `<img>` tag with proper aspect ratio styling.
   - Typography: Elegant calligraphic serif font for couple names (e.g., 'Cormorant Garamond' or 'Great Vibes') and clean sans-serif/serif mix for dates and times.

4. Interactive Bottom Action Bar (Pill Buttons):
   - Place 3 distinct, rounded pill buttons floating or fixed at the bottom:
     1. "GET DIRECTIONS" (opens Google Maps link in new tab)
     2. "ADD TO CALENDAR" (triggers .ics file download or Google Calendar link)
     3. "RSVP" (opens a clean modal form or scrolls down smoothly to the RSVP section)

5. Animations & Micro-Interactions:
   - Gentle floating petal/stardust animation overlay across the card background.
   - Smooth entrance animations (fade-in & slide-up) as the page loads.
   - Subtle tap/hover scaling on the action buttons.

### Technical Guidelines:
- Code Architecture: Clean single-file implementation (`index.html`) using HTML5, Tailwind CSS (via CDN) or CSS variables, and lightweight Vanilla JavaScript.
- Responsiveness: Designed mobile-first to fit perfectly on modern phone screens without awkward scrolling, while staying gracefully centered on desktop viewports.
- Editable Variables: Define all configuration variables (`BRIDE_GROOM_NAMES`, `WEDDING_DATE`, `MAP_LINK`, `INITIALS`) in a script block at the top for quick customization.