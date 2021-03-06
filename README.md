# Defra digital services portfolio

[![Build Status](https://travis-ci.org/DEFRA/defra-portfolio.svg?branch=master)](https://travis-ci.org/DEFRA/defra-portfolio)
[![Dependency Status](https://david-dm.org/environmentagency/defra-portfolio.svg)](https://david-dm.org/DEFRA/defra-portfolio)

## View the portfolio
[Defra digital service portfolio](http://defra-digital-services.herokuapp.com/)

## Creating a new service
- Create a new branch in GitHub prefixed with `new-` to indicate a new service rather than an update, followed by the name of your service (abbreviation is fine)
- Services are based in `/lib/projects/`
- Open `/lib/id_tracker.txt` and pick the next free number within your theme and add your service name. If all numbers are used, just add the next one in sequence.
- Take a look at `/lib/projects/defaults.js` for a template of what a project should contain
- Create a unique project file, copy in the configuration, and add your details
- Alternatively, copy an existing project and change the details
- When adding details, be sure to use an existing theme and location so that the sorting will work
- If you require a new location or theme, please contact the site maintainer explaining why it is needed
- Commit your work, create a pull request, and assign the site maintainer to review.

## Updating a service
- Create a new branch prefixed with `update-` followed by the name of your service (abbreviation is fine)
- Make your changes, *ensuring you also edit the `last updated` section on `/app/views/index.html`*
- Commit your work, create a pull request, and assign the site maintainer to review.


Site content is maintained by @liammcmurray https://github.com/liammcmurray

### Credit

Credit to https://github.com/dwpdigitaltech/dwp-portfolio from where this site has been cloned and adjusted to Defra.
