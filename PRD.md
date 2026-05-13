# Product Requirements Document (PRD)
# Landmark Family Restaurant Website

## 1. Project Overview

**Project Name:** Landmark Family Restaurant Website
**Project Type:** Single-page restaurant website with multiple sections
**Core Functionality:** A professional, mobile-responsive website showcasing Landmark Family Restaurant in Armur, Telangana. The website will help local customers discover the restaurant, view the menu, and place orders for home delivery or takeout.
**Target Users:** Local customers in Armoor and nearby villages seeking quality Indian and Biryani dining options.

---

## 2. Restaurant Profile

### Basic Information
- **Restaurant Name:** Landmark Family Restaurant
- **Type:** Family Restaurant
- **Cuisine:** Indian, Biryani, Multi-cuisine
- **Services:** Home Delivery, Takeout
- **Location:** PERKIT ARMOOR, Karimnagar Nizamabad Rd, Armur, Kothaarmur, Telangana 503223
- **Phone/WhatsApp:** +91 63037 96368

### Target Audience
- Primary: Local customers in Armur town
- Secondary:Nearby villages (Kothaarmur,.Perkit, etc.)
- Customer type: Families, groups, individuals seeking quality dining

---

## 3. UI/UX Specification

### Color Palette
Based on warm, appetizing colors suitable for an Indian restaurant:

| Role | Color | Hex Code |
|------|-------|----------|
| Primary | Burnt Orange | #E65100 |
| Primary Light | Saffron | #FF9800 |
| Secondary | Deep Brown | #3E2723 |
| Accent | Golden Yellow | #FFC107 |
| Background | Warm White | #FFF8E1 |
| Text Primary | Dark Brown | #3E2723 |
| Text Secondary | Medium Brown | #5D4037 |
| White | Pure White | #FFFFFF |

### Typography
- **Headings:** 'Playfair Display' (elegant, traditional Indian feel)
- **Body:** 'Poppins' (clean, modern readability)
- **Accent:** 'Noto Sans Devanagari' (for Hindi/Telugu text support)

### Font Sizes
- H1: 48px (hero)
- H2: 36px (section titles)
- H3: 24px (card titles)
- Body: 16px
- Small: 14px

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

---

## 4. Page Structure (Single Page Application)

### 4.1 Navigation Bar (Fixed)
- Restaurant Logo/Name (left)
- Navigation Links: Home, Menu, About, Contact
- CTA Button: "Order Now" (links to ordering section)
- Mobile: Hamburger menu

### 4.2 Hero Section
- Full-width background image (restaurant ambiance)
- Overlay with gradient for text readability
- Headline: "Authentic Indian & Biryani"
- Subheadline: "Traditional Flavors, Family Memories"
- Two CTAs: "Order Now" | "View Menu"
- Operating hours badge

### 4.3 Features Section
- 4 feature cards with icons:
  1. 🍛 Fresh Ingredients
  2. 🚚 Fast Delivery
  3. 👨‍👩‍👧‍👦 Family Friendly
  4. ⭐ Quality Taste

### 4.4 Menu Preview Section
- Section title: "Our Specialties"
- Category tabs: Biryani, Indian Curries, Tandoor, Drinks
- Food cards grid (6 featured items)
- Each card shows: Image, Name, Description, Price
- "View Full Menu" button

### 4.5 About Section
- Two-column layout (image + text)
- Restaurant story and heritage
- Chef's special notes
- Traditional cooking methods

### 4.6 Gallery Section
- Photo grid showing restaurant ambiance, food, and staff
- 6 images in responsive grid
- Lightbox on click

### 4.7 Ordering Section
- Clear service options:
  - 🏠 Home Delivery
  - 📦 Takeout
- Delivery area badge: "Armur & Nearby Villages"
- WhatsApp order button with direct link
- Phone call button

### 4.8 Contact Section
- Map embed (Google Maps)
- Address with copy button
- Phone/WhatsApp with click-to-call
- Operating hours table
- Contact form (optional, submits via email)

### 4.9 Footer
- Restaurant name and logo
- Quick links
- Social media icons (if available)
- Copyright text

---

## 5. Functionality Specification

### 5.1 Core Features
1. **Responsive Navigation** - Smooth scroll to sections, sticky navbar
2. **Menu Display** - Category filtering, food cards with hover effects
3. **WhatsApp Ordering** - Pre-filled message with order details
4. **Click-to-Call** - Phone and WhatsApp direct dial
5. **Google Maps Integration** - Embedded map with location
6. **Operating Hours Display** - Clear weekly schedule
7. **Image Lightbox** - Gallery image viewing

### 5.2 User Interactions
- Smooth scroll navigation
- Menu category tab switching
- Food item hover animations
- Image gallery lightbox
- Mobile hamburger menu toggle
- WhatsApp order button (opens WA with pre-filled message)

### 5.3 Data Handling
- All content is static (no backend required)
- WhatsApp integration uses `wa.me` API
- Phone links use `tel:` protocol

---

## 6. Menu Items (Sample)

### Biryani Specialties
| Item | Description | Price |
|------|-------------|-------|
| Chicken Biryani | Aromatic basmati rice with spicy chicken | ₹250 |
| Mutton Biryani | Tender mutton pieces with royal spices | ₹350 |
| Veg Biryani | Mixed vegetables with fragrant rice | ₹200 |
| Egg Biryani | Boiled eggs with seasoned rice | ₹180 |

### Indian Curries
| Item | Description | Price |
|------|-------------|-------|
| Chicken Curry | Traditional chicken in onion-tomato gravy | ₹220 |
| Paneer Tikka Masala | Cottage cheese in creamy tomato sauce | ₹200 |
| Dal Tadka | Yellow lentils tempered with garlic & spices | ₹150 |
| Veg Kolhapuri | Mixed vegetables in spicy Kolhapuri style | ₹180 |

### Tandoor Items
| Item | Description | Price |
|------|-------------|-------|
| Chicken Tikka | Tandoor-roasted marinated chicken | ₹280 |
| Seekh Kebab | Minced meat skewers with spices | ₹300 |
| Naan | Soft bread from tandoor | ₹40 |
| Butter Roti | Whole wheat bread with butter | ₹30 |

---

## 7. Operating Hours

| Day | Hours |
|-----|-------|
| Monday | 11:00 AM - 10:00 PM |
| Tuesday | 11:00 AM - 10:00 PM |
| Wednesday | 11:00 AM - 10:00 PM |
| Thursday | 11:00 AM - 10:00 PM |
| Friday | 11:00 AM - 10:00 PM |
| Saturday | 11:00 AM - 10:00 PM |
| Sunday | 11:00 AM - 10:00 PM |

---

## 8. Technical Requirements

### Technology Stack
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript** - Interactivity (vanilla, no framework needed)
- **Deployment:** Netlify (free hosting)

### Performance Targets
- First Contentful Paint: < 1.5s
- Mobile-first responsive design
- Optimized images (WebP format where possible)
- Minified CSS/JS for production

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## 9. Acceptance Criteria

### Visual Checkpoints
- [ ] Navigation is fixed and responsive
- [ ] Hero section displays with background image and readable text
- [ ] Feature cards are visible with icons
- [ ] Menu items display in grid with images
- [ ] About section has two-column layout
- [ ] Gallery shows 6 images in lightbox
- [ ] Contact section has embedded Google Map
- [ ] Footer is complete with all info

### Functionality Checkpoints
- [ ] All navigation links scroll to correct sections
- [ ] Mobile menu hamburger works
- [ ] WhatsApp button opens with pre-filled message
- [ ] Phone number is clickable
- [ ] Map is interactive
- [ ] All external links open in new tabs

### Deployment Checkpoints
- [ ] Site builds without errors
- [ ] All assets load correctly
- [ ] Site is accessible via Netlify URL
- [ ] Mobile responsive on all breakpoints

---

## 10. Deliverables

1. Complete source code (HTML, CSS, JS)
2. Netlify deployment with live URL
3. This PRD document

---

**Document Version:** 1.0
**Created:** May 7, 2026
**Author:** Hermes AI Agent