+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Hello!"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "blimp.jpg"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = "#E7EBEC"
  
  # Background gradient.
  #gradient_start = "#4bb4e3"
  #gradient_end = "#2b94c3"
  
  # Background image.
  # image = ""  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://pages.rstudio.net/SharingonShortNoticeHowtoGetYourMaterialsOnlinewithRMarkdown_WebinarRegistration.html"
  label = "Register"
  icon_pack = "fas"
  icon = "pen-nib"
  
[cta_alt]
  url = "https://rstd.io/sharing"
  label = "See the slides"

# Note. An optional note to show underneath the links.
[cta_note]
  label = 'Last updated: 2020-03-31'
+++

This is a [demo course website created](https://github.com/apreshill/share-blogdown) for an [RStudio Education](https://education.rstudio.com/) webinar by [Alison Hill](https://alison.rbind.io/) and [Desirée De Leon](https://desiree.rbind.io/).

To turn off this announcement, change **content/home/hero.md** from **active = true** to **active = false**.

<span style="text-shadow: none;"><a class="github-button" href="https://github.com/rstudio-education/sharing-short-notice" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star this on GitHub">Star</a><script async defer src="https://buttons.github.io/buttons.js"></script></span>
