Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

Contributors
=================

    Adam Ahmed


License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Site Access
=================
This repo is hosted on GitHub Pages at: <https://adamva.github.io/CMPUT404-assignment-css-hell/>

Modifications
=================
## Part 1: 
- All gutenberg files (1.html, 2.html, 3.html) have a `<link>` tag that points to a shared [CSS file](static/gutenberg.css) `static/gutenberg.css`.
- All gutenberg files (1.html, 2.html, 3.html) have a `<!-- rev: $xjofEj4$x -->` comment under the `<title>` tag and indicates the file's revision number for this project only. The revision number is a random 6 alphanumeric string that has no association with Project Gutenberg or the book's content.
- All gutenberg files (1.html, 2.html, 3.html) have a `<class="first-paragraph">` added to the first `<p>` of each chapter.
- All gutenberg files (1.html, 2.html, 3.html) have a `<div class="book-info">` at the top of the page for information related to Project Gutenberg, and book's title, publication, and language.
- All gutenberg files (1.html, 2.html, 3.html) have a `<div class="book-license">` at the bottom of the page for information related to the Project Gutenberg's licence for the book.
- All gutenberg files (1.html, 2.html, 3.html) have a `<div class="toc">` surrounding the book's content header & chapter listing to be used as the table of contents.
- The Project Gutenberg eBook of Alice’s Adventures in Wonderland, by Lewis Carroll, [3.html](3.html) ending line `THE END` container tag has been modified from `<h3>` to `<p class="center">`
- The Project Gutenberg eBook of Alice’s Adventures in Wonderland, by Lewis Carroll, [3.html](3.html) cover image tag had it's link updated to be the absolute path of the cover image hosted at `https://www.gutenberg.org/files/11/11-h/images/cover.jpg`
- The Project Gutenberg eBook of Peter Pan, by James M. Barrie, [2.html](2.html) table of contents chapter listing has had its single `<td>` of the chpater number and name split into two individual `<td>`.

References
=================
- Katariina Valen. 2021. Yellow. Retrieved from https://unsplash.com/photos/0-Qw9mYw7Lw
- McGill Library. 2020. Who killed cock robin?. Retrieved from https://unsplash.com/photos/eMw-fVXNpME
- Project Gutenberg-tm. 1993. The Project Gutenberg eBook of Alice’s Adventures in Wonderland, by Lewis Carroll. Retrieved from https://www.gutenberg.org/files/11/11-h/11-h.htm
- Project Gutenberg-tm. 1993. The Project Gutenberg eBook of Frankenstein, by Mary Wollstonecraft Shelley. Retrieved from https://www.gutenberg.org/files/84/84-h/84-h.htm
- Project Gutenberg-tm. 1993. The Project Gutenberg eBook of Peter Pan, by James M. Barrie. Retrieved from https://www.gutenberg.org/files/16/16-h/16-h.htm
- Shot By Ireland. 2020. Lightning black white lake. Retrieved from https://unsplash.com/photos/xUKuhL-8_60
