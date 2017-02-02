# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

### [1.5.2] - 2016-11-30

#### Added
- Option to show Apple Pay in list of payment icons

#### Changed
- Fix bug causing 500 error on brand pages


### [1.5.1] - 2016-11-17

#### Added
- `lang` attribute to <html> tag
- Overlay during ajax calls on the faceted search

#### Changed
- Altered logic of customizable form checkbox field so BC validates it correctly
- Fixed bug that caused the "Show More" link on faceted search to not work with spaces


### [1.5.0] - 2016-11-10

#### Added
- Add Apple Pay Support
- Add pagination to brand pages
- A theme customisation to automatically send users to he cart after adding a product
- Add option to disable ajax add-to-cart

#### Changed

- Fixed bug where related products were taking the same price as the product if that
product had options [THEME-1118]
- Fixed bug causing issues with product reviews while the throttler was on [THEME-1103]


### [1.4.3] - 2016-10-27

#### Changed
- Custom "Down for Maintenance" message now works
- Add "Show More" button for product filters that have more than 15


### [1.4.2] - 2016-08-11

#### Changed
- Added nofollow attribute to faceted search links
- Fixed an issue where videos were not showing up on product pages

#### Added
- Add "Show All" links for longer sitemap lists


### [1.4.1] - 2016-07-21

#### Changed

- Update BC footer link with rel="nofollow" [THEME-972]


### [1.4.0] - 2016-07-14

#### Added

- Theme Editor option to control the link color in the banner

#### Changed

- Use full image for pinterest share link


### [1.3.4] - 2016-07-07

#### Changed

- Removed certain elements so print looks better


### [1.3.3] - 2016-06-30

#### Changed

- Modifications to the nav so it looks better with more categories/category levels
- Properly align billing/shipping fields on checkout


### [1.3.2] - 2016-06-22

- Show copyright info in footer [THEME-1053]
- Add classes to product details


### [1.3.1] - 2016-06-16

#### Changed

- Hide Newsletter on signup[THEME-1044]

### [1.3.0] - 2016-06-02

#### Added

- Option to show/hide blog on homepage

#### Changed

- Show "& Up" beside rating stars for faceted search [THEME-1032]
- Fix display of non-resized logo on checkout [THEME-1012]


##[ 1.2.1 ] - 2016-05-26

### Fixed

- Added swatch zoom on hover for desktop, hidden on mobile (fixes THEME-1029)

### [1.2.0] 2016-05-17

#### Added

- Option to show/hide product details

#### Changed

 - Prevent menu from overlapping currency converter when signed in
 - Make swatch image full size
 - Make logo same size on checkout as rest of theme [THEME-1012]


### [1.1.0] - 2016-05-12

#### Added

 - New option for product count [THEME-1006]

### [1.0.12] - 2016-05-05

#### Changed

 - Fixed an issue with Braintree payments not handling user info correctly (fixes THEME-975)


### [1.0.11] - 2016-04-28

#### Changed

 - Close dropdown when you click elsewhere
 - Add Option to limit/hide featured and new products from homepage [PXU-34]


### [1.0.10] - 2016-04-21

#### Fixed

 - Only show gift certificates when setting is on [THEME-956]
 - Only show wishlist when settings is on [THEME-881]
 - Only show account creation links when setting is on [THEME-951]
 - Only show review starts when setting is on [THEME-873]
 - Show Category Description [THEME-957]
 - Show RSS feed if selected on a page [THEME-982]
 - Show custom fields [THEME-963]
 - Show UPS shipping method if there is one [PXU-30]

### [1.0.9] - 2016-4-14

#### Fixed
 - Some glitches in the "more" dropdown
 - Added Colors Back to Bright preset


### [1.0.8] - 2016-04-7

#### Added
 - Display of Facebook like button [THEME-932]
 - Display of Pinterest button [THEME-943]

#### Changed
 - Option to see all or limit display of reviews


### [1.0.7] - 2016-03-31

#### Added
 - Options to show all pages and/or categories

### [1.0.6] - 2016-03-16

#### Added
 - Product options update based on inventory of SKU [THEME-908]


### [1.0.5] - 2016-03-3

#### Added
 - Bulk pricing to products [THEME-926]

#### Changed
 - Core update


### [1.0.4] - 2016-02-24

#### Added
 - Add sitemap to footer with an option to hide it [THEME-883]

#### Changed
 - Core update


### [1.0.3] - 2016-02-5

#### Added
 - New theme author metadata

#### Changed
 - Footer theme credits
 - Centred product images when they aren't big enough to fill the container
 - Reduced header font-size


### 1.0.2] - 2016-01-26

#### Added
 - Option to hide brands in footer
 - Option to truncate brands in footer to 5
 - New wishlist icon

#### Changed
 - Fixed issue with the quantity clicker where if used on multiple quick-viewed
items from one page it'd increase erratically
 - Fixed issue where items removed from cart preview popup wouldn't refresh cart
page
 - Mobile mosaic now displays images at their true aspect ratios
 - Mobile category sort/clear filters are centered
 - Increased logo size for mobile
 - Mosaic text color settings pull from theme editor
 - Primary navigation will no longer wrap if the text is too long
 - Padding on the body
 - Mobile nav is now masked behind the padding when it slides out from the left
 - Font sizes on product-grid items
 - Fixed an issue where alerts from quick-viewed products would show up on the
single product page's product


### 1.0.1] - 2016-01-22

#### Added
 - URLs to theme demos in config


### [1.0.0] - 2016-01-21

#### Changed
 - Added screenshots and description for release


### [0.6.11] - 2016-01-21

#### Changed
 - Remove extra settings from schema


### [0.6.10] - 2016-01-21

#### Changed
 - Fix duplicate images from showing up when toggling product variations
 - Add toggle to hide the theme credits
 - Make it so ESC closes modals


### [0.6.9] - 2016-01-20

#### Added
 - Generic error pages
 - Missing snippet tags

#### Changed
 - Hide alerts and buttons on unpurchaseable products
 - Fixed issue with ajax on search/category/brand pages


### [0.6.8] - 2016-01-19

#### Added
 - Mosaic font options added
 - All fonts added to theme editor
 - Font overrides added to theme editor

#### Changed
 - Style updates to headings, banners, promos, contact form, shipping calculator,
 labels, product prices and titles, form swatches
 - Longer blog excerpts on homepage
 - Cart Preview remove item button works
 - Navigation typography tweaked
 - Revamp footer styling
 - Max width added to quick-shop


### [0.6.7] - 2016-01-19

#### Added
 - Shop by brand pages

#### Changed
 - Moved subcategories, clear filters, and sort order in the sidebar


### [0.6.5] - 2016-01-18

#### Added
 - Product variation images

#### Changed
 - Layout of mobile clear/sort filters on category pages


### [0.6.4] - 2016-01-12

#### Added
 - Product event date
 - Styles to unavailable pages
 - Shipping messages to homepage and product page

#### Changed
 - Videos will fill tabs
 - Moved shipping messages on cart page
 - Fixed some cart alerts


### [0.6.3] - 2016-01-11

#### Added
 - Payment icons to footer
 - Hibernation and maintenance pages
 - Search by price when faceted search is disabled

#### Changed
 - Header nav now users pages instead of categories
 - Footer nav has 3 columns: pages, categories, brands
 - Location of notification when user leaves a review
 - Styling for shipping estimate
 - Product grid moves to 4 column so empty sidebars no longer show on brand and
 search pages when faceted search is disabled


### [0.6.2] - 2016-01-08

#### Added
 - Subscribe template
 - Brands template

#### Changed
 - Product list options display properly


### [0.6.1] - 2016-01-07

#### Added
 - Alerts
 - Error pages
 - Gift certificate pages

#### Changed
 - Product price structure
 - Product data is complaint with google


### [0.5.3] - 2016-01-07

#### Changed
 - Styled missing product form elements
 - Various updates to product JS
 - Add to wishlist button is functional


### [0.5.2] - 2016-01-06

#### Added
 - Sign up and login pages
 - Account pages


### [0.4.2] - 2016-01-05

#### Changed
 - Various bug fixes


### [0.4.1] - 2015-12-18

#### Changed
 - Proper image sizes are being used
 - Default image fallbacks added throughout


### [0.4.0] - 2015-12-17

#### Added
 - Homepage Mosaic
 - Variant designs


### [0.3.0] - 2015-12-17

#### Added
 - Content pages
 - Contact us pages
 - WYSIWYG (RTE) styling


### [0.2.0] - 2015-12-17

#### Added
 - Compare functionality


### [0.1.0] - 2015-12-16

#### Added
 - Quick View modal


### [0.0.1] - 2015-12-14

#### Added
 - First release for QA. Added all development to date.
