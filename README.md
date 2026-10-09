# Day 3 - Reusable UI Components

## Overview
5 reusable, responsive UI components built with only HTML & CSS.
Focus: Code quality, responsiveness, interactivity, accessibility.

## Components List

### 1. Navigation Bar
- **Usage:** Site header for all pages
- **Tech:** Flexbox for layout, position: sticky
- **Responsive:** Hamburger hidden on desktop, flex wrap on mobile
- **Accessibility:** nav tag, aria-label on toggle, focus states

### 2. Hero Section
- **Usage:** Landing intro section
- **Tech:** Grid (2 columns -> 1 column), Flex for buttons
- **Hover:** Buttons with transform + background transition
- **Accessibility:** section with heading hierarchy

### 3. Feature Cards
- **Usage:** Services / features display
- **Tech:** CSS Grid: 3 cols desktop, 2 tablet, 1 mobile
- **Hover:** Lift effect translateY(-8px) + shadow
- **Reusable:** article tag, can duplicate card

### 4. Testimonial Cards
- **Usage:** Customer reviews
- **Tech:** Grid for layout, Flexbox for author info
- **Hover:** translateY + scale(1.01) + shadow
- **Accessibility:** blockquote, alt text on avatar, aria-label on rating

### 5. Footer
- **Usage:** Site footer with links and contact
- **Tech:** Grid 2fr 1fr 1fr -> 1fr on mobile, Flex for socials
- **Hover:** Link slide + color change, icon lift
- **Accessibility:** footer tag, aria-label on socials

## Responsiveness Strategy
- Breakpoints: 900px (tablet), 600px (mobile)
- Used Grid + Flexbox combination as required
- No fixed widths, max-width containers centered

## Interactivity
All interactive elements have:
- transition: all 0.3s ease
- hover: transform + box-shadow + color
- focus-visible for keyboard users

## GitHub
Repo: [your-repo-link]
Commits follow Conventional Commits (feat:)

## Screenshots
[Add desktop + mobile screenshots here in /screenshots folder]

Author: Afnan - Peshawar
Date: May 2026