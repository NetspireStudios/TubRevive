TUBREVIVE STATIC BLOG 
=====================

ADDING A NEW POST
-----------------
1. Create a new folder inside /blog/ using the SEO URL slug as the title (with hyphens).
   Example: 'how-long-does-bathtub-reglazing-last' would be the name of the new folder in the /blog/ directory.

2. Copy the blog/templates/post-template.html FILE into that new folder you just created and rename the FILE to: index.html.

3. Replace every [[PLACEHOLDER]] text, update the article body, and change robots to index, follow. You can easily CTRL + F while editing the file to find the exact spots that need to be replaced.

4. Add a new article card to blog/index.html. The easiest method is to duplicate the existing <article> card and replace its URL, image, title, date, excerpt, and read time.

5. Add the new URL to sitemap.xml and update the blog page lastmod date.

6. Commit the changes and you're done.

IMAGE NOTE
----------
For new images, please upload them in the /gallery/ directory.
