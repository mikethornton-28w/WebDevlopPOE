# Web Development POE #

# 2025-11-03 #

[1.2.0] 

3.1 Interactive Elements

Tabs Section:

Added fully functional tabs on index.html (Groceries, Electronics, etc.).

Implemented smooth transition animations between tabs.

Enhanced user experience by allowing users to switch content seamlessly without reloading the page.

Accordions (About Us Page):

Added collapsible accordion panels to display company information in sections.

Users can expand or collapse details for a cleaner and more interactive layout.

Modal Window (Pop-up Ad):

Created a promotional modal that appears on page load with a special offer.

Added animation effects for smooth pop-up and exit transitions.

3.2 Interactive Maps (Contact Page)

Integrated Google Maps via iFrames for multiple business locations.

Created two separate map displays for different store branches.

Enhanced accessibility and ensured the maps are responsive on mobile devices.

3.3 Animations and Transitions

Added CSS animations and transitions for smoother navigation effects.

Applied hover effects to buttons and product cards for better user engagement.

Implemented fade and slide animations for modals and tab content changes.

3.4 Advanced DOM Manipulation

Manipulated the DOM to:

    Filter tab content.

    Control visibility of modals, accordions, and tabs.

    Dynamically load search results.

3.5 Gallery with Lightbox

Integrated a gallery lightbox within the product section.

The lightbox is responsive and visually matches the Needy design theme.

3.6 Dynamic Content and Search Functionality

Added dynamic search functionality using JavaScript.

The search bar now:

Displays a dropdown preview of matching results.

Redirects users to the correct product page when an item is selected.

Supports Enter key navigation and outside-click to hide dropdown.

Enhanced DOM interactivity and search accuracy.

4. SEO Optimization (3.1 – 3.3 Tasks)
4.1 On-Page SEO Enhancements

Added Title Tags for every page with relevant keywords.

Added Meta Keywords and Meta Descriptions for improved search visibility.

Optimized Image File Names and Alt Texts with relevant product names.

4.2 Off-Page SEO Enhancements:

Added Social Media Links to promote the brand externally.

Integrated Backlinks within relevant pages.

4.3 Technical SEO Enhancements:

Created and configured a robots.txt file to guide search engine crawlers.

Created a sitemap.xml to help search engines understand the site structure.

Implemented basic security measures (such as HTTPS setup and clean JS structure).

# 2025-11-01#

Fixed a problem where the homescreen would show the old version of the Needy website by updating it with a newer version.

# 2025-09-26 #
[1.1.0] Added about-us.html, contact.html, cart.html


Added styles.css file with:

      () General reset (margin, padding, box-sizing).
      ()Header, navigation bar, main content, product grid, footer.
      () Basic button styling.

Styled homepage layout with grid sections.

Created main category pages:

    () Electronics (Smartphones, Laptops, Headphones).
    () Appliances.
    () Groceries.
    () Home & Furniture.

Linked all subpages (electronics.html, appliances.html, groceries.html, homefurniture.html).

Added product subpages (fruitandvegetables.html, bakery.html, dairyandeggs.html, softdrinks.html, juices.html, water.html, livingroom.html, bedroom.html, kitchen.html).

Each subpage now displays 5 items with Add to Cart buttons.    

Added navigation menu across all pages (Home, Categories, About, Contact, Cart).

# 2025-09-27 #

Styled typography with font-family, font-size, font-weight, line-height, and letter-spacing.

Applied color scheme based on Needy’s green brand color (#2e7d32) for headers, buttons, and footer.

Created consistent button design with hover states.

Applied box-shadow and borders to product cards for modern styling.

# 2025-09-28 #

Added media queries (@media) for tablet and mobile devices.

Adjusted layouts using CSS Grid and Flexbox for product sections and navigation.

Implemented hover effects on buttons and navigation links for interactivity.

Ensured consistent typography hierarchy (h1, h2, h3, body text).

Created responsive product grid system (grid-template-columns: repeat(auto-fit, minmax(220px, 1fr))).

# 2025-09-29 #

Fixed logo path issue (logo now stored inside /images/ and properly displayed with <img src="images/logo.png" alt="Needy Logo">).

Confirmed responsive logo sizing with .logo { max-height: 60px; width: auto; }.

Added media queries to adjust typography, grid layouts, and navigation for tablets and mobile devices.

Verified inspection points: typography, layout, pseudo-classes, color decoration, and responsiveness all implemented.

# 2025-08-26 #

[1.0.0] An Initial release – The Needy website structure was created.

Added basic HTML pages: index.html, electronics.html, appliances.html, groceries.html, and homefurniture.html.

Implemented header, navigation bar, main content, and footer placeholders in each page.

No styling applied yet (plain HTML).

Navigation links connected between the main pages.

First version marks the foundation of the Needy shopping website.

References:

https://www.makro.co.za/?srsltid=AfmBOor5Pv6q_vfdxNMjPnF-sMgqYpaSy0nYFSzd9RPAgfBoAZTB4Eb4
