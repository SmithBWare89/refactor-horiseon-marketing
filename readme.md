***UCF Module One Horiseon Marketing Code Refactor**
V1 - "First Commit"

V1.1  -"refactored header html and css"
    - Added Header semantic tag
    - Added Nav semenativ tag
    - Added comments dileniating that this is the Navigation section
    - Eliminated "Header" class. Path from Nav tag does the same thing
    - Add comments to dileniate general CSS styles
    - Removed "list-style-type" property as it doesn't affect code

V1.2 - "hero refactor"
    - Added comments to separate hero style and html from other sections
    - Moved float left and float right classes to general styles section
    - Added comments to show footer style start and end
    -Added HTML comments to show difference between services and benefits sections

V1.3 - "Services Refactor"
    - Consolidated classes search-engine optimization, online-reputation-management, and social-media-marketing into one class "content-info"
    - consolidated descending selectors for img and h2 of Services section so they're under new "content-info" class
    - added semantic "section" tag to encompass information
    - consolidated benefits-brand, benefits-lead, and benefits-cost classes into one class "benefits-info"
    - deleted parent div so now section tag is parent container with class "content"