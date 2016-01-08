---
layout: post
title:  "The wrong tile"
date:   2016-01-08 08:01:53 -0600
blog-hero: /assets/images/blog/puzzle-design.jpg
---

I recently remodeled the bathroom in my home. It was so satisfying to see that ugly 75-year-old floor tile and nasty tub surround demolished. I was eager to line the space with gleaming, modern ceramic and porcelain tile.

I visited the tile store with my contractor's interior designer to make tile selections. We picked out large rectangular tiles for both the tub surround and floor. We took photos of the tile specifications that had been created by the tile store, and sent them off to the contractor for ordering. The tub surround tile came in a myriad of shapes and sizes, so that information was important to get the order right. What better way than a photo? What could possibly go wrong?

On the day the tile was to be installed, imagine our suprise when square 8" x 8" tile was waiting for pickup, when I had picked out rectangular 9" x 12" tile. How could that happen? I never wanted square tile. I never saw square tile. I never specified square tile.

Or did I?

![Tile order form](/assets/images/blog/content/wrong-tile-checkbox.jpg)
*What size tile would you order?*

Take a quick glance at that  photo. It's the tile specifications from the tile store, on a sticker affixed to the back of a piece of tile. If you think the checked box is associated with the 8x8 choice, instead of the 9x12 choice, I wouldn't blame you. And I didn't blame the contractor for the mistake, either.

It's bad form design. And bad form design creates bad results.

If we examine the problems with this form within the context of [UI Gestalt priciples](https://www.smashingmagazine.com/2014/03/design-principles-visual-perception-and-the-principles-of-gestalt/ "Design Principles: Visual Perception And The Principles Of Gestalt"), we can discover why the wrong tile was ordered.

First, let's consider the principle of *proximity*. This concept says:

 > When elements are positioned close to one another, they are seen as part of a group rather than as individual elements. This is especially true when the elements in the group are closer to each other than they are to any elements outside the group.

If we look at our form, the checkbox between 9x12 and 8x8 is roughly equidistant between the two choices. It's impossible to determine which choice is associated with that checkbox without additional context. There's no grouping of checkbox and tile size.

So from there, let's consider the principle of *past experiences*. This concept says:

> Elements tend to be perceived according to an observer’s past experience.

When we glance at our form, we see that the checkbox before 8x8 is checked. Our past experience has taught us that checkboxes precede the option associated with it. Since we don't have any proximity clues, it's natural for us to assume that the checked box is for 8x8. In fact, when we actually mark the box using a pen, the ink mark knocks into the 8x8 text.

All it takes to fix this form is moving the checkboxes in front of the options, and adding additional space between the options. With those simple changes, a user would have no doubt which tile to order, solving problems for both the tile store, the contractor, and the homeowner.

![Tile order form](/assets/images/blog/content/better-tile-checkbox.jpg)
*Simple changes to improve the form make the desired tile obvious.*




