# Blueprint for Juwon Tech Website

## Overview
This blueprint outlines the structure, design, and features of the Juwon Tech website, a specialist in streetlight pole manufacturing. The site is designed to be modern, responsive, and user-friendly, showcasing product offerings, technical documentation, and contact information.

## Project Details

### Initial Version (prior to modifications)
The initial website structure included:
- **HTML (index.html):** Main structure with navigation, hero section, product highlights, drawings, and contact form.
- **CSS (style.css):** Basic styling.
- **JavaScript (main.js):** (Implied, but no explicit content provided in initial context)
- **Firebase Studio Environment:** Indicated by `.idx/dev.nix` and `mcp.json`.

Key sections included:
- Top bar with contact info and certification.
- Navigation bar with logo "가로등테크" and menu items: 회사소개, 제품소개, 도면자료실, 온라인문의.
- Hero section with a background image and a call to action.
- Products section (`id="products"`) detailing different types of streetlight poles.
- Drawings section (`id="drawings"`) with a table for downloading specifications.
- Contact section (`id="contact"`) with a form and company contact details.
- Footer with company name "STREETLIGHT TECH" and copyright information.

### Implemented Features and Design (Current State)

#### Company Name Change (가로등테크 to 주원테크)
- **`index.html`:**
    - Replaced "가로등테크" with "주원테크" in the main navigation logo.
    - Updated the `<title>` tag from "Streetlight Tech | 가로등주 전문 제작 기업" to "Juwon Tech | 주원테크 가로등주 전문 제작 기업".
    - Changed the contact email address from `info@streetlight-tech.co.kr` to `info@juwon-tech.co.kr`.
    - Replaced "STREETLIGHT TECH" with "JUWON TECH" in the footer's main title.
    - Replaced "Streetlight Tech" with "Juwon Tech" in the copyright notice.

#### About Us Section
- **`index.html`:**
    - Added a new `<section id="about">` block after the hero section and before the products section.
    - The section includes:
        - A main heading "회사소개".
        - An image related to the company.
        - Two paragraphs introducing "주원테크", its history, commitment to quality, and customized solutions.
        - Two feature highlights: "품질 최우선" (Quality First) and "기술 혁신" (Technological Innovation) with corresponding icons and descriptions.

#### Product Image Insertion
- **`index.html`:**
    - Replaced the Font Awesome icon (`<i class="fas fa-sun">`) for "스마트 태양광 LED 가로등" (Solar Smart Type) product with an `<img>` tag.
    - The image source is `./Solar_Street_Light.jpeg` with appropriate `alt` text and styling (`max-h-full max-w-full object-contain`).

## Plan for Current Request: Add "회사소개" (About Us) Section

### Objective
Generate and insert content for the "회사소개" (About Us) section into `index.html`, making it accessible via the existing navigation link.

### Steps
1. **Locate Insertion Point:** Identified the ideal position within `index.html` for the new "About Us" section. This was before the existing `products` section.
2. **Generate Content:** Created compelling Korean text for the "회사소개" section that introduces "주원테크," highlights its values, expertise in streetlight pole manufacturing, commitment to quality, and vision.
3. **Insert Section:** Added a new `<section id="about">` block with the generated content into `index.html`. The content includes a main heading, a brief introduction, and details about the company's mission, vision, and values.
4. **Verify Styling and Responsiveness:** Ensuring the new section integrates seamlessly with the existing Tailwind CSS styling and maintains responsiveness. (This step is considered done as part of the implementation and visual check).
5. **Update blueprint.md:** Documented the added "About Us" section.