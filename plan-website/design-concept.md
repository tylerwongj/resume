# Tyler Wong Portfolio Website - Design Concept

## Overview
A modern, professional portfolio website inspired by the Squarespace Tepito template but adapted for a Unity Game Engineer. The design emphasizes visual impact through a full-screen hero image while maintaining clean, readable typography and professional presentation.

## Design Inspiration
**Primary Reference:** Squarespace Tepito Template
- **Key Elements Borrowed:**
  - Clean, minimal aesthetic
  - Professional portrait photography as focal point
  - Elegant typography hierarchy
  - Subtle color palette
  - Simple navigation structure

**Tyler's Modifications:**
- **Full-screen hero image** instead of contained portrait
- **Semi-transparent black overlay** for text visibility
- **Two-column portfolio layout** below hero section
- **Your eye-friendly dark color scheme** integration

## Section-by-Section Breakdown

### 1. Hero Section (Full Viewport Height)
```
Layout: Full-screen background image with overlay
Content Positioning: Center-aligned text over image
```

**Visual Elements:**
- **Background:** High-quality professional photo of Tyler
- **Overlay:** Semi-transparent black (#000000 at 50% opacity)
- **Typography:**
  - **Name:** "Tyler Wong" - Large, bold, white text
  - **Title:** "Unity Game Engineer" - Medium weight, subtitle
  - **Tagline:** "Creating engaging games with solid architecture and innovative mechanics"
- **Call-to-Action:** Subtle scroll indicator (↓) at bottom

**Color Scheme (Over Dark Overlay):**
- **Text Primary:** #ffffff (pure white for maximum contrast over dark photo)
- **Text Secondary:** #e8e8e8 (for subtitle/tagline)
- **Accent:** #4a9eff (for scroll indicator)

### 2. Portfolio Section (Two-Column Layout)
```
Layout: Left content, Right visuals
Responsive: Stacks on mobile
```

**Left Column - Project Details:**
- **Project title** with metrics
- **Brief description** (2-3 sentences)
- **Key technologies** used
- **Results/Impact** (downloads, retention, etc.)
- **"View Project" button** linking to detailed case study

**Right Column - Visual Assets:**
- **Screenshots carousel** or single hero image
- **GIF demonstrations** where available
- **Logo/branding** elements

**Featured Projects (Top 4):**
1. **Car Fall 3D** - "1,000+ Downloads, 3.3/5 Stars"
2. **Puzzle Split** - "22.4% D7 Retention Rate"
3. **Burn - Destructible Art** - "Simple Art Tool"
4. **TruPlay Games Platform** - "Professional Unity Development"

### 3. About Section (Single Column)
```
Layout: Centered content with professional photo
Max-width: 800px for readability
```

**Content:**
- **Professional photo** (different from hero - more approachable/casual)
- **Brief bio** highlighting Unity expertise
- **Key skills** visualization
- **Professional experience** timeline
- **Contact CTA** button

### 4. Contact Section
```
Layout: Simple, centered form
Background: Subtle gradient or solid color
```

**Elements:**
- **Contact form** (name, email, message)
- **Social links** (LinkedIn, GitHub)
- **Email:** tylerwong.j@gmail.com
- **Location:** Walnut, CA

## Technical Specifications

### Color Palette (Tyler's Eye-Friendly Scheme)
```css
/* Backgrounds */
--bg-primary: #1e1e1e;
--bg-secondary: #2d2d2d;
--bg-card: #252525;

/* Text */
--txt-primary: #e8e8e8;
--txt-secondary: #c0c0c0;

/* Accents */
--acc-blue: #4a9eff;
--acc-green: #5cb85c;

/* Overlays */
--overlay-dark: rgba(0, 0, 0, 0.5);
```

### Typography
```css
/* Primary Font: Modern, clean sans-serif */
font-family: 'Inter', 'Helvetica Neue', Arial, sans-serif;

/* Hero Typography */
--hero-name: 4rem / 64px
--hero-title: 1.5rem / 24px
--hero-tagline: 1.125rem / 18px

/* Body Typography */
--heading-large: 2.5rem / 40px
--heading-medium: 2rem / 32px
--body-large: 1.125rem / 18px
--body-regular: 1rem / 16px
```

### Layout Structure
```css
/* Hero Section */
height: 100vh
background-size: cover
background-position: center

/* Portfolio Section */
max-width: 1200px
margin: 0 auto
padding: 4rem 2rem
grid-template-columns: 1fr 1fr
gap: 3rem

/* Responsive Breakpoints */
mobile: < 768px (stack columns)
tablet: 768px - 1024px
desktop: > 1024px
```

## Development Approach

### Phase 1: Structure & Content
1. **HTML5 semantic structure**
2. **Content hierarchy** planning
3. **Image optimization** and preparation
4. **Responsive grid** system setup

### Phase 2: Styling & Visual Design
1. **CSS Grid/Flexbox** layouts
2. **Typography** implementation
3. **Color scheme** application
4. **Interactive elements** (hover states, animations)

### Phase 3: Enhancement & Polish
1. **Smooth scrolling** implementation
2. **Image lazy loading**
3. **Performance optimization**
4. **Cross-browser testing**

## Success Metrics
- **Visual Impact:** Professional, memorable first impression
- **User Experience:** Intuitive navigation and clear information hierarchy
- **Performance:** Fast loading times (< 3 seconds)
- **Conversion:** Clear path to contact/hire Tyler
- **Mobile Experience:** Fully responsive across all devices

## Next Steps
1. **Professional photoshoot** for hero image
2. **Content writing** for all sections
3. **Technical implementation** following this design system
4. **Testing and refinement** based on feedback

---

*This design concept balances professional presentation with Tyler's personal brand as a Unity Game Engineer, emphasizing both technical competence and creative vision.*