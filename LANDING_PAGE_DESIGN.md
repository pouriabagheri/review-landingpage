# Toilet Review - Landing Page Design Specification

## Brand Identity & Purpose

**App Name:** Toilet Review
**Tagline:** "Find, Review, and Discover Clean Restrooms Nearby"
**Purpose:** Location-based toilet discovery platform where users can find nearby public restrooms, read reviews, view ratings, and contribute their own experiences.

---

## Color Palette

### Primary Colors
| Color Name | Hex Code | Usage |
|------------|----------|-------|
| Primary Green | `#10B981` | Main brand color - CTAs, highlights, icons |
| Secondary Blue | `#3B82F6` | Accent color - links, secondary actions |
| Warning Gold | `#F59E0B` | Ratings, stars, important notices |
| Error Red | `#EF4444` | Errors, alerts |

### Background Colors
| Color Name | Hex Code | Usage |
|------------|----------|-------|
| Pure White | `#FFFFFF` | Main background |
| Light Surface | `#F9FAFB` | Card backgrounds, alternating sections |

### Text Colors
| Color Name | Hex Code | Usage |
|------------|----------|-------|
| Primary Text | `#111827` | Headings, main content |
| Secondary Text | `#6B7280` | Descriptions, captions |
| Inverse Text | `#FFFFFF` | Text on dark backgrounds |

### Gray Scale
For borders, dividers, and subtle elements:

| Color | Hex Code |
|-------|----------|
| Gray 50 | `#F9FAFB` |
| Gray 100 | `#F3F4F6` |
| Gray 200 | `#E5E7EB` |
| Gray 300 | `#D1D5DB` |
| Gray 400 | `#9CA3AF` |
| Gray 500 | `#6B7280` |
| Gray 600 | `#4B5563` |
| Gray 700 | `#374151` |
| Gray 800 | `#1F2937` |
| Gray 900 | `#111827` |

### Example Color Usage
- **Hero CTA button:** Green background (`#10B981`), white text
- **Section backgrounds:** Alternate between white (`#FFFFFF`) and light gray (`#F9FAFB`)
- **Feature icons:** Green (`#10B981`) or Blue (`#3B82F6`)
- **Ratings:** Gold stars (`#F59E0B`)
- **Links:** Blue (`#3B82F6`)
- **Headings:** Dark gray (`#111827`)
- **Body text:** Medium gray (`#6B7280`)

---

## Typography

### Font Family
System fonts for optimal native appearance:
```css
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
```

### Font Sizes
| Element | Desktop | Mobile |
|---------|---------|--------|
| Heading 1 (Hero) | 36px | 30px |
| Heading 2 (Section) | 24px | 20px |
| Heading 3 (Subsection) | 20px | 18px |
| Body Text | 16px | 16px |
| Caption Text | 14px | 14px |
| Small Text | 12px | 12px |
| Button Text | 16px | 16px |

### Font Weights
| Weight | Value |
|--------|-------|
| Normal | 400 |
| Medium | 500 |
| Semibold | 600 |
| Bold | 700 |

### Line Heights
| Type | Value | Usage |
|------|-------|-------|
| Tight | 1.25 | Headings |
| Normal | 1.5 | Body text |
| Relaxed | 1.625 | Long-form content |

---

## Spacing System

Based on a consistent 4px base unit:

| Size | Value | Name |
|------|-------|------|
| xs | 4px | Extra small |
| sm | 8px | Small |
| base | 12px | Base |
| md | 16px | Medium |
| lg | 20px | Large |
| xl | 24px | Extra large |
| 2xl | 32px | 2X large |
| 3xl | 40px | 3X large |
| 4xl | 48px | 4X large |
| 5xl | 64px | 5X large |
| 6xl | 80px | 6X large |
| 7xl | 96px | 7X large |

### Common Spacing
- **Section padding:** 16px (mobile), 24px (desktop)
- **Card padding:** 16px
- **Section spacing:** 24px between major sections
- **Element spacing:** 8-12px between related elements

---

## Border Radius

| Size | Value | Usage |
|------|-------|-------|
| Small | 4px | Tags, small elements |
| Base | 8px | Cards, inputs |
| Medium | 12px | Larger cards |
| Large | 16px | Prominent cards, images |
| XL | 24px | Hero sections, large images |
| Full | 9999px | Circular buttons, avatars, pills |

---

## Component Specifications

### Buttons
- **Height:** 48px
- **Padding:** 16px horizontal
- **Border radius:** 8px
- **Font:** 16px, weight 600
- **Primary:** Green background (`#10B981`), white text
- **Secondary:** White background, green border, green text
- **Hover states:** Slightly darker shades

### Cards
- **Background:** White (`#FFFFFF`) or Light Surface (`#F9FAFB`)
- **Border radius:** 8px or 12px
- **Padding:** 16px
- **Box shadow:** Subtle (0 1px 3px rgba(0,0,0,0.1))

### Input Fields
- **Height:** 48px
- **Border radius:** 8px
- **Border:** 1px solid Gray 300 (`#D1D5DB`)
- **Focus:** Blue border (`#3B82F6`), slight shadow

### Rating Stars
- **Filled:** Gold (`#F59E0B`)
- **Empty:** Gray 200 (`#E5E7EB`)
- **Size:** 16-20px typically

---

## Page Sections

### 1. Hero Section
- Compelling headline about finding clean restrooms
- Brief description (1-2 sentences)
- Download buttons (App Store + Google Play)
- Hero image or app screenshots
- Use green accent strategically

### 2. Features Section
Display 4-6 key features with icons:

| Feature | Icon | Description |
|---------|------|-------------|
| Location-based discovery | Map icon | Find nearby restrooms instantly |
| Real user reviews | Star icon | Read authentic community feedback |
| Photo uploads | Camera icon | See real photos before you go |
| Favorites management | Heart icon | Save your go-to locations |
| Search & filters | Search icon | Filter by cleanliness, accessibility |
| Offline support | Download icon | Access saved locations anywhere |

**Layout:** Each feature includes icon, title, and description

### 3. How It Works
- 3-step process with numbered steps
- Simple, clean layout
- Use app screenshots if possible
- Clear, actionable language

### 4. Social Proof (Optional)
- User testimonials or statistics
- Number of users, reviews, locations
- Use star ratings with gold color (`#F59E0B`)
- Build trust and credibility

### 5. Call to Action
- Repeated download section
- App Store & Google Play badges
- QR code option for easy download
- Strong, action-oriented copy

### 6. Footer
- Links: Privacy, Terms, Support, About
- Social media icons
- Copyright notice
- Contact information

---

## Design Principles

### Visual Style
- Clean, minimalist, modern
- Generous white space
- Card-based layouts
- Subtle shadows (never harsh)
- Rounded corners throughout
- Mobile-first responsive design

### Imagery
- Use clean, modern UI screenshots from the app
- Icons should be simple, outline-style or solid
- Photos should be bright, clean, welcoming
- Avoid cluttered or busy images

### Interactions
- Smooth hover effects on buttons (slight color darkening)
- Subtle transitions (200-300ms)
- Clear active/focus states
- Touch-friendly targets (48px minimum)

### Accessibility
- High contrast text (WCAG AA minimum)
- Semantic HTML structure
- Alt text for images
- Keyboard navigation support

---

## Tone & Messaging

- Friendly, helpful, approachable
- Focus on convenience and community
- Emphasize cleanliness and reliability
- Avoid crude or juvenile language
- Highlight user empowerment

---

## Technical Requirements

- Fully responsive (mobile, tablet, desktop)
- Fast loading (optimized images)
- SEO-friendly markup
- Clean, semantic HTML
- Modern CSS (Flexbox/Grid)
- Works on all modern browsers

---

## Brand Consistency

This landing page should feel like a natural extension of the mobile app. If a user visits the website and then opens the app, they should immediately recognize the same brand identity through:

- Consistent colors
- Typography
- Spacing
- Visual style
- Component design
- Overall user experience

The web presence is an introduction to the app experience, maintaining strict adherence to the established design system ensures a seamless brand journey.

---

## CSS Variables Reference

```css
:root {
  /* Primary Colors */
  --color-primary-green: #10B981;
  --color-secondary-blue: #3B82F6;
  --color-warning-gold: #F59E0B;
  --color-error-red: #EF4444;

  /* Background Colors */
  --color-bg-white: #FFFFFF;
  --color-bg-light: #F9FAFB;

  /* Text Colors */
  --color-text-primary: #111827;
  --color-text-secondary: #6B7280;
  --color-text-inverse: #FFFFFF;

  /* Gray Scale */
  --color-gray-50: #F9FAFB;
  --color-gray-100: #F3F4F6;
  --color-gray-200: #E5E7EB;
  --color-gray-300: #D1D5DB;
  --color-gray-400: #9CA3AF;
  --color-gray-500: #6B7280;
  --color-gray-600: #4B5563;
  --color-gray-700: #374151;
  --color-gray-800: #1F2937;
  --color-gray-900: #111827;

  /* Spacing */
  --spacing-xs: 4px;
  --spacing-sm: 8px;
  --spacing-base: 12px;
  --spacing-md: 16px;
  --spacing-lg: 20px;
  --spacing-xl: 24px;
  --spacing-2xl: 32px;
  --spacing-3xl: 40px;
  --spacing-4xl: 48px;
  --spacing-5xl: 64px;
  --spacing-6xl: 80px;
  --spacing-7xl: 96px;

  /* Border Radius */
  --radius-sm: 4px;
  --radius-base: 8px;
  --radius-md: 12px;
  --radius-lg: 16px;
  --radius-xl: 24px;
  --radius-full: 9999px;

  /* Typography */
  --font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;

  /* Font Sizes */
  --font-size-h1: 36px;
  --font-size-h1-mobile: 30px;
  --font-size-h2: 24px;
  --font-size-h2-mobile: 20px;
  --font-size-h3: 20px;
  --font-size-h3-mobile: 18px;
  --font-size-body: 16px;
  --font-size-caption: 14px;
  --font-size-small: 12px;

  /* Font Weights */
  --font-weight-normal: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Line Heights */
  --line-height-tight: 1.25;
  --line-height-normal: 1.5;
  --line-height-relaxed: 1.625;
}
```

---

## Implementation Checklist

- [ ] Set up color variables in CSS
- [ ] Configure typography system
- [ ] Implement spacing system
- [ ] Create button components (primary, secondary)
- [ ] Design card components
- [ ] Build hero section
- [ ] Create features section with icons
- [ ] Implement "How It Works" section
- [ ] Add social proof section
- [ ] Design CTA section with download buttons
- [ ] Build footer with links
- [ ] Ensure full mobile responsiveness
- [ ] Test accessibility (keyboard navigation, screen readers)
- [ ] Optimize images and assets
- [ ] Test cross-browser compatibility
- [ ] Implement smooth transitions and hover effects
- [ ] Add meta tags for SEO
- [ ] Set up analytics tracking

---

**Document Version:** 1.0
**Last Updated:** 2025-10-22
**Status:** Ready for Implementation
