# POSTMARK: THE LOST ART OF SENDING POSTCARDS
==============================================

Project Description:
A responsive editorial magazine exploring the art of sending postcards, romanticizing everyday life, and finding beauty in small moments.

Design Style:
A mix of vintage nostalgia and modern editorial design, using warm colors, creative layouts, and postcard-inspired details.

# PROGRESS LOG
-------------
-Step 1: Set up the project using the provided starter file

-Step 2: Updated the HTML title, headline, introduction, issue badge, and color pallet. 

-Step 3: Added editorial serif heading and responsive typography for a modern magazine appearance. 

-Step 4: Organized the article into two sections and updated the navigation links to match

-Step 5: Added editorial content about handwritten postcards, personal connections, and romanticizing everyday moments. 

-Step 6: Added the second article section about postcards as travel memories, keepsakes, and art.

-Step 7: Added a third section about slowing down called The Art of Slowing Down

-Step 8: Added personal story about collecting and sending postcards during my six weeks in Ireland.

-Step 9: Created a composition plan documenting the magazine's positioning, layers, and shapes.

-Step 10: Styled the magazine header and added a responsive postage-stamp inspired badge. 

-Step 11: Styled the article layout using css grid and added responsive sticky story navigation.

-Step 12: Styled the pull quote as a layered paper element with a controlled overlap on larger screens.

-Step 13: Added tow postcard illustrations to the article for a decorative layered collage. 

-Step 14: styled the postcard collage with Grid, rotation, and controlled layering. 

-Step 15: Created an images folder to organize the magazine's visual assets.

-Step 16: Added a vintage postcard photograph to the images folder
    Image Credit:
    Fiona Murray-deGraaff / Unsplash
    https://unsplash.com/photos/dZZxUjWUx_o

-Step 17: Connected the vintage postcard photograph to the article and added description alt text and image attribution. 

-Step 18: Added a clip-path enhancement to the feature photograph and checked its rectangular fallback.

-Step 19: Kept the oval postcard image to complement the magazine vintage editorial aesthetic.

-Step 20: added vintage editorial dividers and decorative details to the article section heading

-Step 21: verified the article meets the 600-900 word requirement and corrected minor text and heading issues.

-Step 22: Replaced the documentation placeholder with a composition plan link, CSS support overview, image credits and AI assistance disclosure. 

-Step 23: Fixed the sticky "in this story" navigation by placing the sidebar and article inside a shared story-layout container. Updated CSS Grid so the nav remains in the left column and is bounded by the article instead of extending into the documentation section.

# ---Browser Support and Fallbacks---
Reviewed November 17, 2026

1. CSS Grid and Flexbox
Used to arrange the article, sidebar, and postcard collage. 
Fallback: content remains in HTML reading order if these layout features are unavailable.

2. Stick Positioning
Used for the "In This Story" navigation on wider screens. 
Fallback: The navigation remains in normal document flow when sticky positioning is unavailable or disabled. 

3. Absolute Positioning
Used for the "Wish You Were Here" badge in the header.
Fallback: On smaller screens, the badge uses relative positioning to avoid covering the heading.

4. Border Radius
Used for rounded image frames and the oval rose illustration.
Fallback: Images remain visible with square corners.

5. Clip Path
Used to give the vintage postcard photograph an irregular paper-cut edge. 
Fallback: The photograph displays without clipping. The effect is inside an @support rule.

5. Shape Outside
Used to wrap article text around the floral illustration. 
Fallback: Text wraps around the rectangular floated image on desktop when shape-outside is unsupported. On smaller screens, the image returns to normal flow. 

# ---MDN References---
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/position
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/clip-path
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/shape-outside

