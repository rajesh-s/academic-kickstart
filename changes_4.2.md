Version 4.2 (April 2019)
Release Notes tell you what’s new in Academic. As always, we welcome your feedback. You can also file a bug report. Want to update to this version? Refer to the update guide in conjunction with the parameter changes mentioned in the Breaking Changes section below.

See what’s new in Academic!
Welcome to the v4.2 release of Academic. There are a number of exciting updates in this version that we hope you will like, including:

Improved Widget System
Improved Widget Pages
Utilizes Hugo’s new headless page mode
Added Preprint, Thesis, and Patent as publication types
See the Publications section below
Improved appearance of Experience & Accomplishments widgets on mobile devices
Significant improvements to the documentation, especially on using widgets to build the homepage
Auto update the copyright year in the site footer
See the Other section below
Several bug fixes (see below for details)
New option to customize homepage section spacing

Version 4.2 adds support for Preprint, Thesis, and Patent as publication types.
Breaking changes
Here are some considerations to make when updating Academic from the previous version, v4.1.0:

Download the new homepage file and move it to content/home/index.md
This file now forms the parent of all your homepage sections (without it, your homepage will no longer render)
Add headless = true to the front matter of all homepage sections (i.e. all files in content/home/) and any widget page sections
Convert any widget pages by:
Deleting their _index.md file
Creating an index.md file with the new widget page front matter
Publications
Added Preprint, Thesis, and Patent as publication types (#769)
View the new list of mappings
Note that previous “Manuscript” type was renamed to “Preprint”
Widgets
Improve appearance of Experience & Accomplishments widgets
New mobile first approach improves style of widgets on small devices
Add option to customize section spacing
Fix citation view not working in Pages or Featured widgets (#961)
Fix tag and category filters not working in Pages and Featured widgets (#989)
Fix exclude_past and exclude_future not working in Pages or Featured widgets
Fix custom sorting not working in Pages or Featured widgets
Fix “See More” link in Pages widget not appearing
Fix Citation View - do not colour authors as links
Fix Hero text color when text_color_light = false
Other
Add ability to auto update the copyright year in the site footer
To use, add {year} to Copyright option in config.toml. Displays current year.
