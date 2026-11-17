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

-Step 24:Completed the composition plan with six layout and positioning techniques, including fallbacks and required tests. 

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

# --- Responsive Layout Test ---
Test date: November 17th, 2026
Browser: Google Chrome
Method: Chrome Developer Tool

Desktop: 1440px
Result: pass
The sidebar and article display in two columns.
The postcard collage and images display correctly 
The sticky navigation stays within the article layout
and does not overlap documentation section.

Tablet: 768px
Result: pass
The layout remains readable and usable.
Images fit within the viewport without horizontal scrolling.
Navigation and article content remain accessible.

Mobile: 375px
Result: pass
The postcard collage adjusts for the smaller screen.
Text and images remain readable without horizontal scrolling.
Navigation does not cover the article content.

Evidence: 
images/screenshotsResponsive
Screenshots captured at 1440px, 768px, and 375px

# --- Keyboard Accessibility Test ---
Test: November 17th, 2026
Browser: Google Chrome

Result: Pass

Tab navigation follows a logical order. 
Focused links have a visible focus indicator.
Navigation links work using the Enter key.
Image credits and documentation links are accessible using the keyboard.

Evidence: 
images/ScreenshotsKeyboard

# ---CSS Fallback Testing ---
Test date: November 17, 2026
Browser: Google Chrome
Method: Disabled CSS declarations using DevTool

Test. 1: Clip-path disabled
Result: Pass
The vintage postcard photographed remained visible when clip oath was disabled. The decorative paper-cut edges disappeared, but the image retained its normal rectangular shape and remained readable

Test 2: Shape-outside Disabled
Result: Pass
The oval botanical illustration remained visible when shape-outside was disabled. The surrounding text wrapped around the rectangular floated image instead of following the curved boundary. All text remained readable and accessible.

During testing, a duplicate @support rule for shape-outside was discovered in styles.css. The duplicate rule was removed, and the fallback was tested again.

Fallback Testing Summary
Both CSS enhancements were tested by temporarily disabling their declarations in Chrome DevTools

Evidence: images/screenshotsCSSfallback

# --- CSS Validation ---
Date: November 17,2026
Tool: W3C CSS Validation service
Result: Three reported errors related to CSS Shapes.

The validator flagged shape-outside and shape-margin, which are valid CSS properties supported by modern browsers. These properties rae intentionally used for the botanical illustrations curved text wrap.
The feature was tested in Chrome including a fallback test with shape-outside disabled. Text remained readable. 

Evidence: images/css-validation

# --- HTML Validation ---
Date: November 17, 2026
Tool: W3C Nu HTML Checker

Files tested:
-index.html
-composition-plan.html

Results: 
-corrected an image filename containing a space.
-added an identifying heading inside the article.
-corrected the article's aria-labelledby by reference.
-reviewed html structure and accessibility.

Evidence: 
-images/html-validation.png
-images/html-composition-validator.png
