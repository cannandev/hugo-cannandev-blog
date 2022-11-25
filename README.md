# Yet another blog by cannandev

## Getting started

Run `hugo server -t hugo-paper` to start the hugo-paper theme example site.

Run `hugo server` to start the cannandev theme.

To create a new blog page, use the archetype command `hugo new posts/a-new-post.md` By default, blog posts have today as the `date`, `draft: true`, and `category: tutorial` as default front matter values.

For a new main page, run `hugo new -k page new.md`. Careful! Main pages automatically appear in the main menu.

For a new testimonial, run `hugo new -k testimonial firstname-middle-lastname.md`. Testimonial pages have `company` and `weight` front matter keys.
