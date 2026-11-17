# Newsletter Template Guidelines

## 1. Hero Banner & Carter News Card
- **Touching / Zero Gap ("lagano thakbe")**: The Hero Banner ("The Carter Courier") and "Carter News" teal card must be directly connected with ZERO gap.
  - Section 2 `<td>`: `padding: 0 30px 0 30px; font-size: 0; line-height: 0; mso-line-height-rule: exactly;`
  - Section 3 `<td>`: `padding: 0 30px 20px 30px;` (no top padding).
- **Banner Size ("banner ektu choto hobe")**: The banner must be slightly smaller/narrower than the Carter News card:
  - Desktop: `width="490" style="display: block; border: 0; width: 100%; max-width: 490px; height: auto; margin: 0 auto;"`
  - Mobile: `width: 86% !important; max-width: 350px !important; margin: 0 auto !important;`
- **Banner Bottom Radius ("banner er bottom e kono border radius hobe na")**:
  - Top corners: Rounded `16px 16px 0 0`.
  - Bottom corners: NO border radius (`0 0`, flat horizontal line touching the card).
- **Carter News Card Radius**:
  - Full card rounded: `border-radius: 20px;` (the rounded top corners remain visible on left and right since the banner is narrower).

## 2. Mobile View Logo Size
- The top header logo (`.logo-img`) in mobile view must always be **180px**:
  ```css
  .logo-img {
    width: 180px !important;
    max-width: 180px !important;
    height: auto !important;
  }
  ```

## 3. Footer Links
- Footer links and text must remain white `#ffffff !important;` across all webmail clients (Namecheap, Roundcube, iOS Mail, Gmail).
