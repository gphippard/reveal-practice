## Sample _reveal.js_ slides

<https://revealjs.com>

---

### Why use Markdown?

Slides can be written in HTML or Markdown

Markdown is shorter and more readable as plain text

- [Markdown overview](https://wwww.markdownguide.org/)
- [Basic Markdown syntax](https://www.markdownguide.org/basic-syntax/)

---

<!-- .slide: data-background="steelblue" -->
### Set background color 

The code for this slide sets "steelblue" as the background color

(Works with HTML named colors or hex codes)
  
---

<!-- .slide: data-background="black" -->
### Change display themes

The theme is set in the "index.html" file, this presentation uses "simple.css"

Theme options are in _/reveal.js/dist/themes/_

---


### Animations (aka fragments)

Fragments appear one-by-one

- First item <!-- .element class="fragment" -->
- Second item <!-- .element class="fragment" -->
- Third item <!-- .element class="fragment" -->

<https://revealjs.com/fragments/> <!-- .element class="fragment" -->

---

### Speaker notes

This slide has speaker notes, press "s" to see them (must allow browser popups)

notes: These are the speaker notes. To add them to a slide, start a line with "notes:" at the bottom of your slide code; anyting after this line is part of the notes. 

Notes open in a popup window with a clock and a preview of the next slide. Advancing the slide in this speaker view advances the slides in the main presentation.

---

<!-- .slide: data-transition="zoom-in slide-out" -->
### Control slide transitions

This slide "zooms" in, explore other transition options:

- none
- fade
- slide
- convex
- concave
- zoom

---

### Mix HTML and Markdown

If you prefer HTML for something, go ahead. 

<p><em>This</em> line is HTML and renders just as well.</p>


---

### Show code blocks

_reveal.js_ handles syntax highlighting if you tell it the language (e.g. "r")

```r
install.packages("dplyr")
library(dplyr)
my_iris_subset <- iris %>%
    filter(Species == "Setosa")
```

---

### Format with CSS

This sentence is smaller, italicized, and red thanks to inline CSS  <!-- .element: style="font-style: italic; color: red; font-size: 0.7em" --> 

Alternatively, assign CSS classes and create a "custom.css" file (this element has class "demo") <!-- .element: class="demo" --> 

--- 

### Make slides that go down

This slide has a down arrow.

Separate slides with "--" instead of "---"...

--

...and the presentation goes **down**...

--

...and **down**...

--

...until the next slide with a "---" separator

notes: In this case the "---" and "--" behavior is set in the "index.html" file that references "slides.md"

---

<!-- .slide: data-background="green" -->

Most _reveal.js_ documentation examples show HTML... you might need to dig deeper or experiment to get things working in Markdown
