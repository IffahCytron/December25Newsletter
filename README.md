# Cytron Year-End Newsletter Email

ActiveCampaign-ready HTML email template for Cytron Technologies' 2025 year-end newsletter.

## Overview

This email is designed for B2B industrial professionals (engineers, system integrators, OEMs) with a customer-centric, professional tone.

## Features

- **Table-based layout** for maximum email client compatibility
- **Fully responsive** design optimized for mobile devices
- **Subtle animations** with hover effects on buttons and links
- **ActiveCampaign compatible** with unsubscribe token integration
- **Email client tested** for Outlook, Gmail, Apple Mail

## Technical Specifications

- Container width: 600px (centered)
- Background: #F5F7FB (light gray)
- Primary accent: #0B3C5D (deep blue)
- Fonts: Arial, Helvetica, sans-serif
- All CSS inline with minimal `<style>` block for mobile media queries

## File Structure

```
.
├── year-end-email.html    # Main email template
└── README.md              # This file
```

## Usage

1. Open `year-end-email.html` in your code editor
2. Replace placeholder content:
   - Logo image URL
   - Company address and contact information
   - Signature name and title
   - All example.com links with actual URLs
3. Upload hero image to your hosting/CDN and update the image URL
4. Import the HTML into ActiveCampaign

## Placeholders to Replace

- `[Name]` - Signatory name
- `[Title]` - Signatory title
- `[Company Address]` - Full company address
- `[City, State ZIP]` - City and postal information
- `[Phone Number]` - Contact phone
- `[Email Address]` - Contact email
- Logo placeholder image
- All `https://example.com/*` links

## Hero Image

The email uses a hero image hosted on GitHub:
```
https://raw.githubusercontent.com/IffahCytron/newsletter-assets/main/newsletter%20hero.jpg
```

Ensure this image is accessible or replace with your own hosted image.

## ActiveCampaign Integration

The email includes the ActiveCampaign unsubscribe token:
```
%UNSUBSCRIBELINK%
```

This token will be automatically replaced by ActiveCampaign when sending.

## Browser & Email Client Support

- ✅ Gmail (desktop & mobile)
- ✅ Outlook (2016, 2019, 365)
- ✅ Apple Mail (iOS & macOS)
- ✅ Yahoo Mail
- ✅ Mobile email clients

## Customization

### Colors
All colors are defined inline. Search and replace:
- Primary blue: `#0B3C5D`
- Background: `#F5F7FB`
- Text: `#2E2E2E`
- Secondary text: `#6B7280`

### Animations
Hover effects are defined in the `<style>` block:
- `.button-hover` - Button hover state
- `.link-hover` - Link hover state
- `.card-hover` - Card hover state

## License

© 2025 Cytron Technologies. All rights reserved.

