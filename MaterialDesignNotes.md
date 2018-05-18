
# Material Design Notes

## Problems
1. I am not currently using dps as the units of measurement
1. Nav/Overflow Menu has no elevation
  a. Nav Menu covers two elements of different elevation: The background ( 0 ) and the Header ( not 0 ..? What is the header Elevation?? )
     That sucks so how do we deal with that?
1. Menu Corners aren't rounded enough
1. Filter's scrollbar is an eyesore
1. Our App bar is totally non-complient
   a. Hamburger menu goes into the top left
   b. Filters are in the way of the hamburger menu's nav drawer
   c. Logo needs to go elsewhere, like the nav drawer.
   d. Search box needs to be replaced by a simple magnifying glass
1. The buttons on our cards are non-complient.  They are not toggle buttons but they have no text.  All buttons that 
   are not toggle buttons _always_ have text and the icon is optional. 
1. The ripple effect cannot be red

## Suggestions
1. In the material spec, the section regarding how Material can grow to reveal other content looks like the property we should use
   to reveal the controls on a selected card for channels, files, etc. https://material.io/design/environment/surfaces.html#attributes.      Look at "Stretchable Surfaces" in the same section as well 

## Observations
1. The vertical three dots menu ( kabob menu ) is consistently being referred to as the icon for the "overflow menu".  I think 
   that means it's a junk drawer.  The spec always shows it in the top right hand corner all the way because it's for the extra 
   relativly unimportant stuff.
   a. Scott Ortel didn't like the idea of there being a menu there I think...
1. Buttons on the filter panel are one of the four material button types referred to as "toggle buttons". Toggle buttons always appear
   to have an icon and never have text. ( https://material.io/design/components/buttons.html#anatomy )
1. The Ripple effect is supposed to be the used pressing down on a peice of material with their finger causing it to "ripple" throughout
   the z-axis of the screen.
1. The element covering and darkening content to focus on a nav drawer or dialog is called a "Scrim". Applying them is called a
   "treatment".
1. Elevations of all the components are available here: https://material.io/design/environment/elevation.html
1. Device Independant Pixels are an abstraction that interpolate's to different lengths on different platforms. For example, on the        Android operating system a device-independent pixel is equivalent to one physical pixel on a 160 dpi screen, while the Windows          Presentation Foundation specifies one device-independent pixel as equivalent to 1/96th of an inch.
