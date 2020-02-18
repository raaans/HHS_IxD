# Structure
CSS, HTML, JS, Images and Icons have their own separate folders

## HTML
HTML is stored per section in the HTML folder

## CSS
CSS is pre-processed by SASS and is separated into partials and page folders. 
A page folder contains a query.scss file, which imports all the relevant css: the 'base' partial and a device file.
The possible device files are 'mainScreen' (desktop), 'dataPad_Large' (tablet) and 'dataPad_Small' (mobile). They contain the styling that only apply to their respective device types.

### CSS Partials
'base' imports all the CSS that's applicable on every device type:
* 'content' (layout styling for the content container)
* 'footer' (styling for the footer)
* 'header' (styling for the header)
* 'modal' (styling for modal panel pop-ups)
* 'typography' (styling for p, h1, a, etc.)
