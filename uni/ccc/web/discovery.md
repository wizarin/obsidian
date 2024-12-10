Embedded vs Linked style sheets:
	Embedded is quicker to access and edit
	Linked can be applied to more than one file

In an img element srcset can also be used(but src is still required for backup), this allows you to put in multiple sources for the same element, separated by commas. The sizes attribute is regularly used to tell the browser the size of each source in the set, from here the browser can choose the appropriately sized source for the current window size. 

Device Pixel Ratio(DPR) can be selected from the f12 menu in browser by accessing device toolbar(mobile view).

@media is a css query that can set the rules for any media on the page based on the attributes queried. Within an element you define the attributes that the media would be querying by using the example format below, in the example media is set to two attributes of the element, 'monochrome' and 'orientation: landscape'. This query is carried out in the pages css by using @media as a general selector for all defined media, this selector can be specified by in the format: @media (orientation: landscape) { encapsulated attributes and selectors}
![[media_query.png]]

type = "image/webp" or /svg+xml or /png etc. Used to define the image format for browser capabilities , providing different formats based on what the browser can render

npm, Node Package Manager is a registry that lists nodes of. with npm you can install any package as a dependency in the file. this might appy to json.
npx, Node Package Execute is used to execute a package without installing it. 

border-radius: 0 25vmin 25vmin 0;
This is a css attribute that applies a custom radius to each corner, starting in the top left and going clockwise. Here the top left and bottom left corner are set to `0` (no rounding). The top right and bottom right corners are set to 25vmin. vmin is the smaller dimension of the viewport, either width or height. 25vmin sets the corner to be based on 25% of the vmin.