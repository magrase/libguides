# libguides
HTML, CSS, and JS templates and customizations for LibGuides
# libguides
HTML, CSS, and JS templates and customizations for LibGuides
LibGuides doesn't provide a comprehensive codebase, so I've copy/pasted the custom code and am documenting the known hierarchy and current settings.
LibGuides Admin-->Look and Feel provides options to customize the following at a system level, while still allowing for more specific customization at the group or guide level. These settings basically set a new default, unless un-customized, in which case the default is the LibGuides default for which I have no code.

Header/footer/tabs/boxes
Page header: public/guide pages html - this is provided in the system_page_header.html file
Page footer: no customization provided
Tab and box options:
    Tabs - Display options: Rounded (vs. square)
    Tabs - Active background: #e03131 (red)
    Tabs - Active font: #ffffff (white)
    Tabs - Inactive background: #f3f2fa (light gray)
    Tabs - Inactive font: #0f0e0e (black)
    Boxes - Shape: Square (vs. round)
    Boxes - Border width: 1
    Boxes - Border: none
    Boxes - Background: none
    Boxes - Header background: #e03131 (red)
    Boxes - Header font: #ffffff (white)
    