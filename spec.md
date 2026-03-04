# EduZone Website Specification

## Project Overview
- **Project Name:** EduZone Website
- **Type:** Single-page professional educational services website
- **Core Functionality:** Showcase EduZone's tutoring services, courses, and contact information with an interactive animated logo
- **Target Users:** Students (Class 1-12), parents, and anyone seeking online education services

---

## UI/UX Specification

### Layout Structure

**Sections:**
1. **Header/Navigation** - Fixed top navigation with logo and menu links
2. **Hero Section** - Main landing area with animated logo and tagline
3. **About Section** - Company introduction and year started (2025)
4. **Services Section** - Detailed listing of all educational services
5. **Why Choose Us** - Key benefits/features
6. **Contact Section** - All contact information with social media links
7. **Footer** - Copyright and quick links

**Responsive Breakpoints:**
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

**Color Palette:**
- Primary: #6366F1 (Indigo - trust, education)
- Secondary: #EC4899 (Pink - energy, creativity)
- Accent: #10B981 (Emerald - growth, success)
- Background Gradient: Linear gradient from #0F172A (dark) to #1E1B4B (deep purple)
- Card Background: rgba(255, 255, 255, 0.05) with glassmorphism
- Text Primary: #F8FAFC
- Text Secondary: #94A3B8

**Typography:**
- Headings: 'Playfair Display' (elegant, professional)
- Body: 'Poppins' (modern, readable)
- Font Sizes:
  - H1: 4rem (hero title)
  - H2: 2.5rem (section titles)
  - H3: 1.5rem (card titles)
  - Body: 1rem
  - Small: 0.875rem

**Spacing System:**
- Section padding: 100px vertical
- Container max-width: 1200px
- Card gap: 30px
- Element spacing: 16px base unit

**Visual Effects:**
- Glassmorphism cards with backdrop-filter
- Smooth scroll behavior
- Parallax floating background elements
- Gradient text effects on headings
- Box shadows with color glow
- Animated gradient borders

### Components

**1. Animated Logo:**
- Position: Floating above hero section
- Initial state: Gentle floating animation (up/down)
- On click: Spiral rotation animation (3 full rotations)
- Size: 120px diameter
- Source: Will use a placeholder representing Instagram DP style

**2. Navigation Bar:**
- Transparent initially, solid on scroll
- Logo on left, menu items on right
- Mobile: Hamburger menu

**3. Service Cards:**
- Glassmorphism effect
- Icon + title + description
- Hover: Scale up + glow effect
- Categories color-coded

**4. Contact Cards:**
- Each contact method as separate card
- Icons for email, phone, WhatsApp, Facebook, Instagram
- Hover animation

**5. Buttons:**
- Gradient background
- Rounded corners (50px)
- Hover: Scale + brightness

---

## Functionality Specification

### Core Features

1. **Animated Logo Interaction:**
   - Continuous floating animation (CSS keyframes)
   - Click triggers spiral rotation (CSS + JS)
   - Returns to floating state after animation

2. **Smooth Scrolling:**
   - All anchor links scroll smoothly
   - Navigation highlights current section

3. **Responsive Design:**
   - Fully responsive on all devices
   - Mobile menu toggle

4. **Contact Actions:**
   - Email: mailto link
   - Phone: tel link
   - WhatsApp: wa.me link
   - Facebook: Opens in new tab
   - Instagram: Opens in new tab

5. **Scroll Animations:**
   - Elements fade in on scroll
   - Staggered animation for service cards

### Services to Display

1. **School Tuition (Class 1-10):**
   - All subjects
   - State, ICSE, CBSE syllabus
   - English & Malayalam medium

2. **Higher Secondary (Class 11-12):**
   - State syllabus
   - Specialization: Mathematics, Physics

3. **Programming Courses:**
   - Python
   - C Programming
   - C++
   - Java

4. **Stock Marketing:**
   - Malayalam medium
   - Limited time batch

5. **Project Services:**
   - CS/IT Projects
   - Project Reports
   - PPT Making

---

## Acceptance Criteria

1. ✅ Website loads without errors
2. ✅ Logo floats continuously and spirals on click
3. ✅ All sections are visible and properly styled
4. ✅ All contact links work correctly
5. ✅ Responsive on mobile, tablet, desktop
6. ✅ Smooth scrolling works
7. ✅ Animations are smooth (60fps)
8. ✅ Professional EduTech appearance
9. ✅ All services are listed accurately
10. ✅ Year 2025 is displayed

---

## File Structure
```
EduZone/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # Interactive functionality
└── SPEC.md         # This specification
```

