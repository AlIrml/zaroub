ZAROUB ANIMATED MENU WEBSITE

This version contains no cropped menu photos and no food image files.
Every menu item has an item-specific inline SVG illustration and animation.

LOGO
There are three clear placeholders:
1. Header: .header-logo-slot
2. Hero: .logo-placeholder
3. Footer: .footer-logo-slot

Replace each placeholder with an <img> element when the final logo is ready.
Example:
<img src="logo.png" alt="Zaroub logo">

WHATSAPP
The WhatsApp number is already configured as:
96170727792

LOCATION
The order drawer now has a visible "Use my location" button.
The Send on WhatsApp button also requests location automatically when no location has been captured yet.

Browser location permission only works when the website is opened through:
- HTTPS hosting, or
- localhost during development

Opening index.html directly as a file may prevent the browser from showing the location permission prompt.
When location is allowed, a Google Maps link and accuracy are included in the WhatsApp order.

RUN
For complete functionality, upload the folder to HTTPS hosting or run it through a local web server.
