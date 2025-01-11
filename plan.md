I want to change this hugo site to a wedding site that has a navbar at the top and two pages:

I want to have a home page with a welcome message and a picture of us.

I want to have a page for the wedding details, including the date, time, location, and a map.

there will be a large link to the typeform that we will use to collect RSVPs on all pages.

1. Create content pages:

   - Create `/content/_index.md` for the home page
   - Create `/content/details.md` for the wedding details page

2. Set up navigation:

   - Edit the site configuration (config.toml/yaml) to add menu items
   - Create/modify the header partial template for the navbar

3. Create/modify layouts:

   - Create/modify `layouts/_default/baseof.html` for the main template
   - Create/modify `layouts/index.html` for the home page
   - Create/modify `layouts/_default/single.html` for the details page

4. Add the persistent RSVP button:

   - Add a prominent button/link in the base template
   - Style it to be visible and attractive

5. Add content:
   - Add welcome message and photo to home page
   - Add wedding details and embed map on details page

Next immediate step: Create the content files and basic structure
