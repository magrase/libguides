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

Page Layout--Guides
    The system-wide template/default and the template being used for all public guides (all guides in Research Guides group), are using the 2018 Guides Redesign template. The customized code for this template can be found in system_page layout_guide_2018 guides redesign.html. Further customization options for Page Layout--Guides is listed below:
    Guide Title - Show on all guide pages (vs. show on guide homepage only)
    Guide Description - Show on all guide pages (vs. show on guide homepage only)

Page Layout--Homepage
    The system-wide template/default for the homepage is using 2021 - Home Template. The customized code for this template can be found in system_page layout_homepage_2021 home.html.

Page Layout--Search
    The system-wide template/default for the search results page is using Search Page 2021 template. The customized code for this template can be found in system_page layout_search_search page 2021.html.

Page Layout--Individual Subject Page
    The system-wide template/default for individual subject pages is using Individual Subject Pages - Hidden Tabs - 2021. The customized code for this template can be found in system_page layout_ind subject page_individual subject pages hidden tabs 2021.

Page Layout--Subject Landing Page
    The system-wide template/default for the subject landing page is using 2021 Subject Landing Page Template. The customized code for this template can be found in system_page layout_subject landing page_2021 subject landing page.html

Page Layout--Individual Profile Page
    The system-wide template/default for individual profile pages is using Individual Profile Page - 2021 Template. The customized code for this template can be found in system_page layout_ind profile page_individual profile page 2021.html

Page Layout--Profile Landing Page
    The system-wide template/default for the profiles landing page is using System Default - Profile Landing Page Template. The code for this template can be found in system_page layout_profile landing page_system default.html

Page Layout--A-Z
    The system-wide template/default for the A-Z database page is A-Z Page (New Layout - Hide Search Box). The customized code for this template can be found in system_page layout_az_az page new layout hide search box.html.