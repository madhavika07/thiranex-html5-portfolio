# HTML5 Semantic Structure & Accessibility Portfolio

A high-performance, structurally sound, and fully accessible multi-page personal portfolio skeleton. This project is built following strict HTML5 semantic layout standards and WCAG 2.1 AA accessibility guidelines to achieve a perfect 100 score on Google Lighthouse audits.

## 🛠️ Core Features & Architecture

### 1. Semantic HTML5 Landmarks
Instead of generic wrappers, this layout implements specialized structural landmarks to allow assistive technologies to parse the document tree flawlessly:
- `<header role="banner">` - Houses the primary branding and global navigation.
- `<nav aria-label="Main Navigation">` - Wraps the structural links with clear context.
- `<main id="main-content">` - Isolates the unique content core of the document.
- `<section>` & `<article>` - Organizes content segments hierarchically, allowing automated page outlines.
- `<footer role="contentinfo">` - Declares copyright and structural metadata.

### 2. WCAG 2.1 Accessibility Implementation
- **Skip Navigation Link:** Includes an off-screen `"Skip to main content"` anchor tag to let keyboard-only and screen-reader users bypass the global navigation instantly.
- **Explicit ARIA Relationships:** Utilizes `aria-labelledby` to explicitly link descriptive section headings to their parents, and `aria-describedby` to provide deep context to dynamic action links.
- **Keyboard Optimization:** The contact form elements use explicit matching `for` and `id` label pairs, securing a logical, native Tab-key focus path.
- **Form Validation UI:** Implements `aria-required="true"` alongside native HTML validation to alert assistive screen readers of mandatory fields dynamically.

### 3. SEO Optimization & Open Graph Meta Tags
- Configured explicit `<meta name="description">` and keywords to maximize indexing parameters.
- Built-in Open Graph protocol properties (`og:type`, `og:title`, `og:description`) to structure data beautifully when shared across professional networks like LinkedIn.

## 📊 Evaluation Metrics Focus
- **Lighthouse Accessibility Audit:** 100/100 Target
- **Lighthouse SEO Audit:** 100/100 Target
- **W3C HTML5 Validator:** Pass (Zero Warnings / Zero Errors)
