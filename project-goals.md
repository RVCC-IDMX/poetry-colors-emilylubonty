# Main Goals for the Poetry Website Project

1. Create a visually appealing and accessible poetry website that thoughtfully interprets and presents "The Soul selects her own Society" by Emily Dickinson.
2. Express the poem’s themes of individuality, choice, and quiet strength through a minimalist, "less is more" design aesthetic—using soft pastel blues/greens and gentle accent colors to evoke a contemplative, somber mood.
3. Use only semantic HTML5 and modern CSS3 (no JavaScript), prioritizing clean structure and meaningful markup to mirror the poem’s clarity and order.
4. Ensure a mobile-first, responsive design so the poem and site content are easy to read and navigate on any device.
5. Meet or exceed WCAG AA accessibility standards, with careful attention to color contrast, heading hierarchy, and screen reader support.
6. Present the poem with clear, readable typography—choosing classic, literary fonts and generous spacing to give each stanza and line room to breathe, reflecting the poem’s introspective nature.
7. Incorporate personal reflections and design choices that connect the site’s look and feel to your own interpretation of the poem’s message about self-selection and societal boundaries.
8. Deploy the finished site to Netlify for public access, ensuring fast load times and professional presentation.
9. Document the design and coding process, including key decisions, challenges, and how AI collaboration contributed to the project.

# Project Goals: Poetry Interpretation

## Overview

- **Project Type:** Poetry interpretation website for Web Dev II
- **Target Audience:** Instructors, peers, and potential employers evaluating web development skills
- **Timeline:** TBD

## Learning Goals

I want to create a website that will demonstrate the ambiance of "The Soul selects her own Society" by Emily Dickinson. I want the website to follow a somber mood board while following WCAG AA standards.
I also do not want the website to be cluttered, but also have some features that enhance the experience while visiting the website. I want to learn how to incorporate the use of AI while building the structure, while also learning how to advance my own personal skill set. I want the website to follow a minimalist/introspective theme, while also being professional and following best accessibility guidelines.

## Professional Tooling Setup

- Use Prettier to ensure code is consistent and properly formatted
- Use Github Copilot's different modes, including Ask, Agent, and Edit
- Keep project files organized and up to date
- Update documentation regarding experiences with Copilot's different modes and progress
- Follow WCAG AA accessibility standards

## Technical Constraints

- HTML5 and CSS3 only (no JavaScript)
- Must be responsive (mobile-first approach)
- WCAG AA accessibility compliance
- Deploy to Netlify

## Semantic HTML Structure

### Planned Page Structure

- `<header>` - Site title and navigation
- `<main>` - Primary content container
  - `<section>` - Poem presentation area
    - `<article>` - The actual poem text with proper stanza structure
  - `<section>` - Personal interpretation and reflection
  - `<aside>` - Additional context or author information (if needed)
- `<footer>` - Copyright and deployment information

### Accessibility-First Markup

- Proper heading hierarchy (h1 → h2 → h3) for screen readers
- `<blockquote>` for poem citation with proper attribution
- Semantic list elements for stanzas or key points
- `alt` attributes for any decorative elements
- `lang` attribute for proper language identification
- Skip links for keyboard navigation

### Content Organization

- Logical reading order that flows naturally
- Clear section breaks between poem and interpretation
- Meaningful link text and button labels
- Form labels properly associated (if contact elements are added)
- Focus indicators for keyboard users

## CSS Typography & Layout

### Typography Goals

- **Font Selection**: Use elegant serif fonts (like Crimson Text or Libre Baskerville) for the poem text to evoke classical literary tradition
- **Font Hierarchy**: Establish clear visual hierarchy with varying font sizes and weights for headings vs. body text
- **Line Height**: Generous line spacing (1.6-1.8) to give each line of poetry room to breathe
- **Letter Spacing**: Subtle letter-spacing adjustments for improved readability
- **Font Loading**: Ensure web-safe font fallbacks for consistent display across devices

### Layout & Spacing

- **Mobile-First Approach**: Start with mobile layout, then enhance for larger screens
- **Responsive Breakpoints**: Design for mobile (320px+), tablet (768px+), and desktop (1024px+)
- **Container Width**: Maximum content width to maintain readability on large screens
- **Vertical Rhythm**: Consistent spacing between sections using CSS custom properties
- **Grid/Flexbox**: Use modern CSS layout techniques for responsive design

### Visual Design System

- **Color Palette**: Soft pastels (blues/greens) with high contrast ratios for accessibility
- **White Space**: Embrace minimalism with generous margins and padding
- **Focus States**: Clear, accessible focus indicators for keyboard navigation
- **Print Styles**: Basic print stylesheet for poem printing

## Success Criteria

- [ ] Successfully interpret and present Emily Dickinson's "The Soul selects her own Society"
- [ ] Achieve WCAG AA accessibility compliance
- [ ] Create responsive design that works on all devices
- [ ] Deploy successfully to Netlify
- [ ] Demonstrate effective use of semantic HTML5 and CSS3
- [ ] Complete professional tooling setup with Prettier and proper documentation

## Key Features Needed

- Clean, readable presentation of the poem text
- Minimalist design reflecting the poem's introspective themes
- Responsive typography and layout
- Accessibility features (proper heading hierarchy, alt text, color contrast)
- Personal interpretation and reflection content
- Navigation between poem and interpretation sections

## Documentation & Deployment

### Development Process Documentation

- **Design Decisions Log**: Record key choices about color palette, typography, layout, and how they connect to the poem's themes
- **AI Collaboration Journal**: Document experiences using GitHub Copilot's Ask, Agent, and Edit modes - what worked well, challenges faced, and how AI helped solve problems
- **Accessibility Testing Results**: Document WCAG AA compliance testing, including:
  - Color contrast ratios and testing tools used
  - Screen reader testing results
  - Keyboard navigation verification
  - Mobile accessibility checks
- **Responsive Design Process**: Screenshots and notes about mobile-first development approach and breakpoint decisions

### Technical Documentation

- **Code Structure Overview**: Brief explanation of HTML semantic structure and CSS organization
- **Performance Metrics**: Load time measurements and optimization techniques used
- **Browser Compatibility**: Testing results across different browsers and devices
- **Deployment Process**: Step-by-step Netlify deployment documentation with any configuration notes

### Reflection & Learning Outcomes

- **Personal Interpretation Connection**: How design choices reflect your understanding of the poem's themes
- **Challenges & Solutions**: Technical problems encountered and how they were resolved
- **Skills Development**: New techniques learned and areas for future improvement
- **AI Tool Effectiveness**: Evaluation of how GitHub Copilot enhanced or changed your development process

### Project Deliverables

- **Live Site URL**: Final deployed Netlify link
- **Repository Link**: GitHub repository with clean commit history
- **README.md**: Project overview, setup instructions, and key features
- **Final Presentation Materials**: Screenshots, process documentation, and key learnings summary

## Current Status

Setting up professional tooling and project structure
