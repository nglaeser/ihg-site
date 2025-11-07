Italy's Hidden Gems website
====================

Live at [italyshiddengems.com](https://italyshiddengems.com). Based on the [Agency Jekyll theme](https://github.com/y7kim/agency-jekyll-theme).

# How to use

### Trip Data
Each trip has its own [Markdown](https://www.markdownguide.org/) file with the trip information to be displayed on the website.

- Previous trips are in `/_posts`
- Upcoming trips are in `/_next_trips`
- A template file for new trips is in `/_drafts`

Trip images are in `/img/trips`. Other images are either directly in `/img` or in another relevant subdirectory.

### Demo

To view the site locally, run
```
bundle exec jekyll serve
```
in the terminal and navigate to localhost.

### Publishing the site

This is a Jekyll site. Jekyll takes care of turning the markdown data, HTML templates, etc. into a classic HTML site, which is placed into the generated directory `_site`. 

To publish the site on third-party hosting provider, copy the contents of `_site` to the HTML directory of the provider.

For more details, read the [Jekyll documentation](http://jekyllrb.com/).