# Cursor UI Clone

A static **UI clone of the Cursor landing page**, built using **pure HTML and CSS**.  
This project focuses on recreating the visual layout, typography, spacing, and color system of Cursor’s marketing website.

> ⚠️ This is a **UI-only clone**. No JavaScript, no backend, and no functional product logic is included.

> ⚠️ Note : somethings will not be correctly visible, please resize your laptop screen because responsiveness wasn't said to add in prd

---

## 🔗 Live Preview
[preview_deployed_link](https://cursor-ui-clone-five.vercel.app/)

---
## 📸 Complete Page Screenshot

![Cursor UI Clone – Full Page Screenshot](./public/complete-screenshot.png)

## 📌 Sections Recreated

The following sections from the original Cursor website were recreated:

### Header
- SVG-based Cursor logo
- Navigation links: Product, Enterprise, Pricing, Resources
- Action buttons: **Sign In** and **Download**
- Sticky header layout

### Hero Section
- Primary headline and supporting text
- Main CTA button (Download for Windows)
- Product preview image

### Trusted By
- “Trusted every day…” heading
- Company logo grid:
  - Stripe
  - OpenAI
  - Linear
  - Datadog
  - NVIDIA
  - Figma
  - Ramp
  - Adobe

### Feature Sections
- **Agents turn ideas into code**
- **Magically accurate autocomplete**
- **In every tool, at every step**
- Two-column layout with text and imagery
- Accent links styled consistently

### Testimonials
- “The new way to build software” heading
- Testimonial cards with:
  - Quote text
  - Author image
  - Name and designation
- Responsive wrapping layout

### Frontier Section
- “Stay on frontier” heading
- Feature cards:
  - Model selection
  - Codebase understanding
  - Enterprise-grade development
- Card-based grid layout with visuals

### Changelog
- Version numbers and release dates
- Grid-based changelog cards
- CTA link to view full changelog

### Company Mission Section
- Applied research statement
- “Join now” call-to-action
- Side-by-side image and text layout

### Recent Highlights
- Blog-style highlight cards
- Metadata (category and date)
- Distinct background section

### Call To Action (CTA)
- Large headline: **“Try Cursor now.”**
- Download button
- Centered vertical layout

### Footer
- Multi-column navigation:
  - Product
  - Resources
  - Company
  - Legal
  - Connect
- Styled links and consistent typography

---

## 🎨 Fonts Used

### Primary Font
**Cursor Gothic**

Loaded locally using `@font-face`:

```css
@font-face {
  font-family: cursor-gothic;
  src: url('/fonts/CursorGothic-Regular.woff2');
}
