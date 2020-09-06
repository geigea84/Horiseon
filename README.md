# Horiseon Read Me

Refactor project for digital marketing company Horiseon.  The primary goal of this project is to improve accessibility for search engine optimization, screen readers, and litigation prevention.

I re-worked the HTML layout and improved tag semantics, consolidated the CSS elements and declarations, and removed redundant declarations.  All changes are listed below.

Link to deployed application:
https://geigea84.github.io/Horiseon/

Link to GitHub repository:
https://github.com/geigea84/Horiseon


HTML
renamed title from website to Horiseon
renamed div class="header" to header
removed class=seo from span
renamed div to section, adjusted alignment, leaving image link in CSS, added title element to replace alt
added comment first article
renamed div to article, added id to fix hyperlink
corrected article 1 tag format for better layout
corrected article 2 tag format for better layout
corrected article 3 tag format for better layout
corrected benefits tag format for better layout
renamed comments from articles to content to better match the div class
added comments for benefit articles 1, 2, and 3
renamed div class="footer" to footer
added alt attributes and descriptions to all content images
added alt attributes w/o discriptions to all benefits images
adjusted benefits 3 image tag to be self closing
added anchor element to header h1 to link back to homepage
adjusted footer h2 to h3
updated title, may need to adjust further to have full accessibility read-out
adjusted alt attributes for improved search engine optimization
changed div classs="content" to main


CSS
*renamed all .header tags to header
*renamed header h1 .seo to header h1 span
*created backup-styles.css
*added color element to body, subsequent #ffffff are now redundant
*renamed all .footer tags to footer
*added footer color to override body color
*consolidated .benefit-lead, -brand, and -cost under .benefits
  *this included classes benefits article, benefits h3, and benefits img
*removed redundant color line from benefits article
*consolidated search-engine-optimization, online-reputation-management, and social-media-marketing into .content article
*consolidated img and h2 for s-e-o, o-r-m, and s-m-m into .content img and .content h2 respectively
*removed redundant color from .content article
*removed header div ul list style type
*removed header color
*added font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; to body
*removed font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; from .content article, .benefits, 
*added margin-right to .header div ul li, adjusted margin l&r to 30px - improved spacing in header
*added font-size to body, deprecated p element
*added comments to break up style sections
*tweaked .header div ul li margins again
*changed .content to main
*removed margin adjustment from .header div ul li, reinstated original to stay true to refactor, still suggest adding px to margins to improve spacing


Need to do:
Get to office hours to learn more about desired product for project grading

Questions to ask: 
what should the README screenshot look like? -is this a snip or full blown screen?
how do I properly set up the return to homepage hyperlink?
-tried both:
<a href="https://geigea84.github.io/Horiseon/">Hori<span>seo</span>n</a>
<a href="/">Hori<span>seo</span>n</a>
