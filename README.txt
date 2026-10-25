WHAT REMAINS — SECTION PAGE

1. Keep before.html and style.css together in the same folder.
2. Open before.html in a browser to preview the layout.
3. Replace the placeholder paragraphs in before.html with your content.
4. Link your homepage's Before box to before.html. For example:
   <a href="before.html" class="your-existing-box-class"> ...existing box content... </a>
   Keep your existing box styling/class name on this link.
5. In before.html, index.html is the homepage link. Change it if your homepage
   uses another filename. The homepage is not included in this package.
6. Change href="next.html" to the actual next section filename. That next page
   is not included. The visible link label stays "Next tab →".
7. For another section, copy before.html, rename it, and update the title,
   number, heading, subtitle, content, and navigation links.

SECTION COLORS
The default blue is set by --card-background in style.css.
To use a different color for one page while sharing the same stylesheet,
change its opening article tag, for example:
<article class="content-card" aria-labelledby="section-title" style="--card-background: #f3dddd;">

Suggested alternatives: pink #f3dddd, sage #e3eee5, lavender #e7e2f1,
cream #f3e9d7, and peach #f5e0d5.

The content card expands with your writing; long sections scroll naturally.
Navigation links sit below the card, after the content. "Next tab" opens the
next section in the same browser tab.
