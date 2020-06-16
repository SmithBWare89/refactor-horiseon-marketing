# ***UCF Module One Horiseon Marketing Code Refactor***

# Purpose
### Horiseon has recruited us to reformat the code of their website so that it meets accessibility standards in order for it to be optimized for search engines. This will include, but not be limited to, consolidating elements of the web page, adding additional attributes to ensure the site if readable by screen readers, and improving the flow of the webpage for future revisions.

## V1 - "First Commit"

## V1.1  -"Refactored header html and css"
- Added Header semantic element
- Added Nav semantic element
- Added comments delineating that this is the Navigation section
- Eliminated "Header" class. Path from Nav element does the same thing
- Add comments to delineate general CSS styles
- Removed "list-style-type" property as it doesn't affect code

## V1.2 - "Hero refactor"
- Added comments to separate hero style and html from other sections
- Moved float left and float right classes to general styles section
- Added comments to show footer style start and end
- Added HTML comments to show difference between services and benefits sections

## V1.3 - "Services and Benefits Refactor"
- Consolidated classes search-engine optimization, online-reputation-management, and social-media-marketing into one class "content-info"
- consolidated descending selectors for img and h2 of Services section so they're under new "content-info" class
- added semantic "section" element to encompass information
- consolidated benefits-brand, benefits-lead, and benefits-cost classes into one class "benefits-info"
- deleted parent div so now section element is parent container with class "content"

## V1.4 - "Benefits and Footer Refactored"
- Deleted benefit-brand and other duplicate code from stylesheet
- Replaced parent div with section semantic element
- Replaced footer section parent div with footer semantic element
- Reintroduced header class to clear up style intent

## V1.5 - "Final page clean up"
- Deleted extraneous white space between sections in HTML
- Changed parent div for Hero section to section semantic element
- Indented all items contained within HTML element
- Changed title to "Horiseon
- Deleted extraneous white space between CSS selectors
- Added title attribute to image in hero
- Added blank alt attribute for images in benefits section
- Deleted closing img tag for "Cost Management" photo
- Added alt attribute descriptions to services section
- Added single quotes to 'Calibri' in benefits and content-info classes

# V2.0 - "Website Redeploy And Reformatted Readme"

## V2.1 - "Additional Edits"
- Changed services section semantic element to "main" to better represent its purpose
- Changes services section class to "services" and "services-info" to better represent which section it's for
- Updated semantic element for hero to aside as the image is only indirectly related to the sites main content