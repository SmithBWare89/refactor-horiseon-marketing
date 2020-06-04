***UCF Module One Horiseon Marketing Code Refactor**
V1 - "First Commit"

V1.1  -"refactored header html and css"
    - Added Header semantic element
    - Added Nav semenatic element
    - Added comments dileniating that this is the Navigation section
    - Eliminated "Header" class. Path from Nav element does the same thing
    - Add comments to dileniate general CSS styles
    - Removed "list-style-type" property as it doesn't affect code

V1.2 - "hero refactor"
    - Added comments to separate hero style and html from other sections
    - Moved float left and float right classes to general styles section
    - Added comments to show footer style start and end
    -Added HTML comments to show difference between services and benefits sections

V1.3 - "Services and Benefits Refactor"
    - Consolidated classes search-engine optimization, online-reputation-management, and social-media-marketing into one class "content-info"
    - consolidated descending selectors for img and h2 of Services section so they're under new "content-info" class
    - added semantic "section" element to encompass information
    - consolidated benefits-brand, benefits-lead, and benefits-cost classes into one class "benefits-info"
    - deleted parent div so now section element is parent container with class "content"

V1.4 - "Benefits and Footer Refactored"
    - Deleted benefit-brand and other duplicate code from stylesheet
    - Replaced parent div with section semantic element
    - Replaced footer section parent div with footer semantic element
    - Reintroduced header class to clear up style intent