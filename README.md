# DIT1203_PRINCIPLES-OF-WEB-DESIGN-_Assignment-2_DIT2101_905005967_IMRAM-CHERNOR-SESAY
Explore Salone

Explore Salone is a travel information website for first-time visitors to Sierra Leone. It presents destinations, dining ideas and national holidays in a simple, easy-to-read format, with a search bar, traveller reviews and a footer with image credits.

It was built for a university web design project (Limkokwing DCOMP204) from the pages and layouts in the project's wireframes. The site is static: plain HTML, CSS and a small amount of JavaScript. There is no build step, framework or server.

What is included
File	Purpose
index.html	Home page with the welcome message, large photo and search bar
locations.html	Locations listing: 8 destination cards
locations_info.html	Detail page shared by all locations
dinning.html	Dining listing: 8 cards
dinning_info.html	Detail page shared by all dining entries
activities.html	Activities and holidays listing: 3 rows
activities_info.html	Detail page shared by all activities
about.html	Mission, user-driven design and the traveller review box
CREDITS.txt	Image sources, authors and licence notes

Each HTML file contains its own styles and scripts, so no other CSS or JavaScript files are needed. There is no images folder, because the photos are loaded online (see below).

How to run
Unzip the project and keep all nine files in the same folder. The footer links to CREDITS.txt, so it must stay beside the HTML files.
Open index.html in any modern browser.
Make sure you are online, so the photos can load.

To publish the site, upload all the files to a static host such as GitHub Pages, Netlify or your university web space.

Content

Locations (8): River Number Two Beach, Tacugama Chimpanzee Sanctuary, Tiwai Island Wildlife Sanctuary, Bunce Island, Tokeh Beach, Lumley Beach, Bureh Beach and Outamba-Kilimi National Park.

Dining (8): River NO.2 Beachfront, Tokeh Beach Seafood, Lumley Beach Strip, Bureh Beach Kitchens, Local Sierra Leonean Dishes, Fresh Grilled Fish, Street Food and Snacks, and Local Drinks.

Activities (3): Independence Day, The Armed Forces Day and Christmas.

About us: The mission statement, the user-driven design (feedback loop) section and a review box.

Features
Search: The search bar on every page finds locations, dining entries and activities. Type a word, press Enter and choose a result from the list that appears.
Detail pages: Clicking a card opens its own information page. The three detail pages read the chosen item from the address, for example locations_info.html?id=tiwai-island, so open them by clicking cards rather than by double-clicking the file.
Traveller reviews: On the About us page, visitors can leave a star rating, title, review and name. Reviews are saved in that visitor's own browser, so other visitors do not see them. Sharing reviews between visitors would need a server or database.
Language control: The EN button shows that the site is in English. There are no other languages yet.
Footer: Every page has a footer with the site description, links to each section and a note pointing to the image credits.
Responsive layout: The pages adapt to phones, tablets and desktops.

JavaScript must be enabled for search, detail pages and reviews.

Images

The photos are loaded from Wikimedia Commons through its Special:FilePath service, so the browser fetches them online each time a page opens. If you are offline, or an image cannot load, the grey photo box from the wireframes is shown instead. The pages still work.

Things to know before you publish:

Licences: The photos use different Creative Commons licences. CC BY images need credit to the author and a link to the licence. CC BY-SA images also require adaptations to be shared under the same or a compatible licence.
Check each file: CREDITS.txt lists the source page for every image. For a few images the author and licence were not confirmed, so open the Commons page and check them before you publish.
Stand-in images: Some pictures are not an exact match for their card, and CREDITS.txt says so. The Bureh Beach card uses another peninsula beach photo. The Local Drinks card uses a local milk-packaging photo. The Independence Day card uses the national flag. The Armed Forces Day card uses a historical regiment parade from 1939. Replace these with matching, properly licensed photos when you can.
Keep the credits: Leave CREDITS.txt with the project and keep the footer credit note on the pages.

To use your own photos instead, replace the src web address of an image in the HTML file with the path to your photo, for example images/tiwai-island.jpg, and add a credit line to CREDITS.txt if the photo needs one.

Editing the content
Cards and text: The listing cards are written directly in locations.html and dinning.html. The detail text for each item is stored in a list near the bottom of the matching _info.html file (the ITEMS list, or the ACTS list for activities).
Search results: The search uses a SITE_INDEX list inside each page. If you add or rename an item, update this list too.
Colours and fonts: The colours are set in the :root block at the top of the <style> section.
Repeated code: Because each page is self-contained, a change to the header, footer, colours or search must be made in every file. Use find and replace across the folder to keep the pages consistent.
Accuracy

Please verify facts such as opening times, access routes, fees, entry rules and holiday dates against official sources before you publish or rely on them. Holiday dates that follow the moon or the Easter calendar change each year. Details about places can also change over time.

Browser support

Current versions of Chrome, Edge, Firefox and Safari, on desktop and mobile.

Credits
Project: Explore Salone, Limkokwing University, DCOMP204 assignment portfolio.
Photographs: Wikimedia Commons contributors, as listed in CREDITS.txt.
Text: written for the project from the project document and public sources.
Licence

This project was created for educational purposes. Add your own licence here if you publish or share the code. Image licences are listed separately in CREDITS.txt.
