# AuthorIntro Widget for Wowchemy

_[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio, generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with widgets, themes, and language packs._

## 🌈 Add the Widget to your Site

1. Install your widget in your site by referencing it at the bottom of your `config/_defaults/config.toml`:
   ```toml
   # At the bottom of your `config.toml` is a Module section:
   [module]

     # Your existing modules will appear here.

     [[module.imports]]
       path = "github.com/Chrede88/wowchemy-widget-authorIntro"
   ```
2. Create an instance of your widget in `home/`, for example let's create `home/authorIntro.md`:
   ```markdown
   ---
   # AuthorIntro widget.
   widget: "github-Chrede88-authorIntro"
   headless: true  # This file represents a page section.
   active: true  # Activate this widget? true/false
   weight: 1  # Order that this section will appear in.

   # Choose the user profile to display
   # This should be the username of a profile in your `content/authors/` folder.
   author: "admin"

   # Subtitle
   subtitle: "A subtitle that discribe something. Really, it could be anything!:smile:"

   design:
     background:
       # Apply a background color, gradient, or image.
       #   Uncomment (by removing `#`) an option to apply it.
       #   Choose a light or dark text color by setting `text_color_light`.
       #   Any HTML color name or Hex value is valid.

       # Background color.
       # color: "rgb(0,0,0)"

       # Background gradient.
       # gradient_start: "DeepSkyBlue"
       # gradient_end: "SkyBlue"

       # Background image.
       # image: "image.png"  # Name of image in `static/media/`.
       # image_darken: 0.0  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

       # Text color (true=light or false=dark).
       # text_color_light = true
   ---
   ```
