# Horiseon

HTML
7 renamed title- Horiseon
12 renamed div class="header" to header
13 removed class=seo from span
29 renamed div to section, adjusted alignment, leaving image link in CSS, added title element to replace alt
31 added comment first article
33 renamed div to article, added id to fix hyperlink
33-41 corrected article 1 tag format for better layout
43-51 corrected article 2 tag format for better layout
53-61 corrected article 3 tag format for better layout
63-92 corrected benefits tag format for better layout
32, 42, 52 renamed comments from articles to content to better match the div class
65, 74, 83 added comments for benefit articles 1, 2, and 3
94 renamed div class="footer" to footer
added alt attributes and descriptions to all content images
added alt attributes w/o discriptions to all benefits images
adjusted benefits 3 image tag to be self closing
added anchor element to header h1 to link back to homepage
adjusted footer h2 to h3


CSS
renamed all .header tags to header
renamed header h1 .seo to header h1 span
created backup-styles.css
added color element to body, subsequent #ffffff are now redundant
renamed all .footer tags to footer
added footer color to override body color
consolidated .benefit-lead, -brand, and -cost under .benefits
-this included classes benefits article, benefits h3, and benefits img
removed redundant color line from benefits article
consolidated search-engine-optimization, online-reputation-management, and social-media-marketing into .content article
consolidated img and h2 for s-e-o, o-r-m, and s-m-m into .content img and .content h2 respectively
removed redundant color from .content article


Need to do:
Adjust hero picture to match layout given on bootcampspot
Correct loadout order of CSS elements to correspond with logical layout of HTML structure
Continue to comb through CSS file to remove redundancies
Add comments to the CSS file
Get to office hours to learn more about desired product for project grading