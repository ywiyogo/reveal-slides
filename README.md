# My Revealjs Markdown Presentation Slides

## Getting Started

1. Install reveal-md with `npm install -g reveal-md`.
2. Create reveal.json for configuring the Reveal.js.
2. Create reveal-md.json for configuring the Reveal-Markdown. For more details see https://github.com/webpro/reveal-md.

## Custom Theme

1. Create a new file *.scss under theme/source.
2. Run `sass --watch theme/source/ydark.scss:theme/ydark.css`
3. Run `reveal-md slides/XXX.md --theme theme/ydark.css -w`

## Custom Styling using HTML attribute and CSS

Create a CSS block tag `style` on the bottom of the markdown file and include it in as the class or id attribute in HTML5.

## References

* https://github.com/webpro/reveal-md
* https://blog.hanklu.tw/post/2021/use-reveal-md-to-generate-multiple-slides-and-host-them-on-github-page/#Generate-static-site