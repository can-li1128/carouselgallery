# Carousel Design for New Books #
*Content*
- index.html is a self-contained .html file that has html, CSS, and script.
- new-arrivals.xlsx minimally requires title, author, ISBNs (used to fetch Syndetics cover link), MMS ID (Alma specific ID used to generate permalink)

*Function*
- index.html automatically reads book records in new-arrivals.xlsx from the same directory, extracts cover image URLs, titles, format author names, and explicit catalog permalinks.reads new-arrivals.xlsx for image display.
- Smooth infinite auto-rotation & controls: auto starts at loading, rotates in a continuous loop, supported by Prev, Pause/Play, and Next navigation buttons.
- Hover behaviors: magnifies book covers by $1.15$ times on mouse hover or keyboard focus, displaying the book title immediately and fading in the formatted author's name after a 1-second delay.
