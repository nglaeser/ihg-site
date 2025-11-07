Italy's Hidden Gems website
====================

Live at [italyshiddengems.com](https://italyshiddengems.com). Based on the [Agency Jekyll theme](https://github.com/y7kim/agency-jekyll-theme).

# How to use

This is a Jekyll site. Jekyll takes care of turning the markdown data, HTML templates, etc. into a classic HTML site, which is placed into the generated directory `_site`. For the full details, read the [Jekyll documentation](http://jekyllrb.com/). 

**TL;DR:** To edit the *content* of the site (not the style), you only need to modify files in the following directories: `_drafts`, `_next_trips`, `_posts`, and `img`. They are described in more detail in the next section.

The remaining directories have to do with the site layout itself and should not be touched unless you intend to mess with the look of the website.
- `_data` contains site-wide variable settings (brand colors, fonts, etc.)
- `_includes` contains the HTML and CSS sources (**using the [Liquid](https://jekyllrb.com/docs/liquid/) templating language**) for the various parts of the webpage
- `_layouts` includes HTML templates reused across the website
- `css` contains additional external CSS artefacts
- `img` and its subdirectories contain images for the various parts of the site
- `js` and `mail` contain the JS source and PHP code for the contact form, respectively

Finally, `_site` is auto-generated as described above and should not be edited, as any changes will be overwritten.

### Trip Data
Each trip has its own [Markdown](https://www.markdownguide.org/) file with the trip information to be displayed on the website.

- Previous trips are in `/_posts`
- Upcoming trips are in `/_next_trips`
- An blank template file for new trips (with instructions) is in `/_drafts`

Trip images are stored in `/img/trips`.

### Demo

To view the site locally, run
```
bundle exec jekyll serve
```
in the terminal and navigate to localhost.

### Publishing the site

To publish the site on third-party hosting provider, copy the contents of `_site` to the HTML directory of the web server.