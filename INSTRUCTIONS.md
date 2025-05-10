You are a professional front-end developer.  
Generate a complete, mobile-responsive HTML landing page in Hebrew for a teen tech academy (ages 13–16) using Tailwind CSS. The page must be a single landing page, RTL and include:

1. **Basic HTML boilerplate & SEO**  
   - `<!DOCTYPE html>`, `<html lang="he" dir="rtl">`  
   - `<head>` with `<meta charset="UTF-8">`, viewport tag, `<title>` and a brief `<meta name="description">` in Hebrew.  
   - Link to the latest Tailwind CSS via CDN.

2. **Semantic, accessible structure**  
   - Use `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.  
   - Ensure headings follow hierarchy (`<h1>` for academy name, `<h2>` for main sections, etc.).  
   - All images have meaningful `alt` text in Hebrew.

3. **Navigation bar**  
   - Academy logo/text on the right (“אקדמיית מתכנתים לעתיד”).  
   - A primary “הרשמו עכשיו” button linking to `#enroll`.  
   - Sticky or fixed shadow style, responsive collapse into a hamburger menu on narrow screens.

4. **Hero (above-the-fold)**  
   - Full-width background color or image (gradient or simple color).  
   - Prominent headline (`<h2>`) in large, bold Hebrew font: “הצטרפו למסע הטכנולוגי שלכם”.  
   - Subheading text: “קורסים מעשיים בתכנות, לינוקס ובינה מלאכותית לנוער בגילאי 13–16.”  
   - Primary CTA button “גלו את התכניות” linking to `#programs`.

5. **“Why Choose Us?” section**  
   - Three columns (stacked on mobile), each with:  
     1. Icon or small image  
     2. Subtitle (`<h3>`): “למידה מעשית”, “מנחים מומחים”, “מיומנויות העתיד”  
     3. One-sentence description in Hebrew.  
   - Cards styled with Tailwind shadows, rounded corners, hover lift effect.

6. **Programs overview**  
   - Three vertical tracks:  
     - **תכנות בסיסי**: Python & JavaScript projects (games, web apps, scripts).  
     - **יסודות לינוקס**: Terminal, filesystem, shell scripting, server basics.  
     - **בינה מלאכותית ולמידת מכונה**: ML concepts, neural nets, simple Python AI demos.  
   - Each track: image placeholder (200×200), heading, paragraph text.  
   - Alternating layout: image left/text right, then image right/text left, etc.

7. **Call-to-Action section**  
   - Centered text: “מוכנים להתחיל?” + short inviter sentence.  
   - Large button “הבטיחו את מקומכם” linking to `/signup`.  
   - Subtle background accent or pattern.

8. **Footer**  
   - © 2025 notice in Hebrew.  
   - Links: “צור קשר” and “מדיניות פרטיות.”  
   - Light gray background, small text, RTL ordering.

9. **Styling details**  
   - Use Tailwind utility classes only—no custom CSS files.  
   - Color palette:  
     - Primary: `blue-600` / `blue-700` on hover  
     - Backgrounds: `gray-50` for body, `gray-100` for sections  
     - Text: `gray-800` for body, `white` on colored backgrounds  
   - Spacing: generous `py-16`, `px-4` containers.

10. **Accessibility & best practices**  
    - Ensure color contrast meets WCAG AA.  
    - Include `aria-label` on nav toggle if implementing mobile menu.  
    - Optimize for fast load: no heavy scripts, defer any JS.

11. **Comments & organization**  
    - Add HTML comments marking each major section.  
    - Keep indentation consistent (2 spaces).

Output the full HTML document as a single code block.  
