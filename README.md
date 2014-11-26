Change Brackets basic web container
=======

This is a version of Change Brackets front end that's more easily reusable than working from previous project-specific versions.

Adapting this for use minimally requires the following:

1. Set up a hashtag harvester on the Nerdsfornature.org-owned changebrackets Heroku app (or another similar service)
2. Insert the Google Docs ID as the value of `googleSpreadsheetId`in index.html
3. Add a link to that same document in the introductory area, which contains a blank href for that purpose.
3. Update other intro copy
3. Replace "thehashtag" with correct hashtag in `index.html`
4. Add a new map centerpoint in the Google maps code.
5. Add a new publicly accessible KML file in the Google Maps code.
6. Edit the cname file as needed to give this page a web presence.

Variations on this repo served via Github Pages combined with that one running on Heroku constitute a free, low-maintenance front and backend solution for Change Bracket installations.

TODO: Consider just moving this page and all variations of this page to a subdirectory

