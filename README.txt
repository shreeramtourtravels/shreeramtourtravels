SHREE RAM TOUR & TRAVELS - ANIMATED STATIC WEBSITE
==================================================

A fast, animated, single-page website for Shree Ram Tour & Travels.
No build step and no dependencies. It works on any static host (GitHub Pages, Netlify, cPanel, etc.).
To view it, double-click index.html.

FILES
-----
index.html     Main page: header, hero, destinations strip, about, vehicles, trip ideas, how to book, enquiry form, contact, footer
privacy.html   Privacy Policy
terms.html     Terms & Conditions
styles.css     All styling and animations (colours are CSS variables at the top; they come from your logo)
assets/
  logo.svg          Your logo (hero, about and footer). It wraps the same image as logo.jpg,
                    so it is not a true vector file.
  logo.jpg          Same logo as a plain image (also used for link previews)
  favicon.png       Browser tab icon and header logo (the Shri Ram figure with bow from the logo)
  swift-dzire.jpg   Swift Dzire photo
  ertiga.jpg        Maruti Ertiga photo
  innova.jpg        Toyota Innova photo
  tempo-traveller.jpg  Tempo Traveller photo
  bus.jpg           Bus - this is an ILLUSTRATION, not a real photo

IMPORTANT ABOUT IMAGES
----------------------
The Dzire, Ertiga, Innova and Tempo Traveller images are generic vehicle images, and the bus is a drawn
illustration. Your own vehicle photos will look better. To replace any of them, save your photo with the
same file name inside assets/ (JPG, any size; it is always shown in full, never cropped).
The four trip pictures in the Trip ideas section are drawn illustrations inside index.html.

DETAILS USED ON THE SITE
------------------------
Business   : Shree Ram Tour & Travels, 10+ years of experience
Phone      : +91 95997 63796 (call and WhatsApp buttons)
Vehicles   : Swift Dzire, Maruti Ertiga, Toyota Innova, Tempo Traveller, Bus (and "more" on request)
Trips      : Delhi - Khatu Shyam - Salasar Balaji - Delhi; Manali and other hill stations;
             Mathura and Vrindavan; Customize your trip
Privacy and Terms are dated 10 October 2026 and say disputes go to the competent courts in India.

THE ENQUIRY FORM
----------------
Fields: Name, Phone number, Trip, Vehicle, Travel date.
On submit the form checks the fields, then opens WhatsApp with a ready message to 919599763796
(India code 91 + 9599763796). The visitor presses Send in WhatsApp and the lead arrives on +91 95997 63796.
Note: this works without any server, but the lead is only delivered if the visitor presses Send.
To change the number, replace 919599763796 in index.html (in the script near the end and in the WhatsApp buttons).

ANIMATIONS
----------
Fade-up hero, rotating sun rays, floating logo card with mouse tilt, a car driving along a road, scrolling
destinations strip, "10+ years" counter, scroll progress bar, cards that rise as you scroll, hover effects,
waving temple flag and glowing sun in the trip pictures. All animation stops automatically for visitors whose
device is set to "reduce motion".

CHOICES MADE FOR YOU (change in the HTML if needed)
---------------------------------------------------
- No address, business hours or prices are shown, because none were given. Trips say "Price on call".
- Seating: Dzire up to 4, Ertiga up to 6, Innova up to 7. Tempo Traveller and Bus say seating is confirmed on booking.
- Hill stations listed as examples: Manali, Shimla, Nainital, Mussoorie. Edit the text if you serve other places.
- Trip stops (for example Krishna Janmabhoomi, Banke Bihari, Prem Mandir, Govardhan) are examples, not promises.

PUBLISHING ON GITHUB PAGES
--------------------------
1. Create a repository and upload all files, keeping the assets folder.
2. In Settings > Pages, choose the main branch and the root folder.
3. Your site will be live at https://USERNAME.github.io/REPOSITORY/
