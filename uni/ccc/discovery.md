Embedded vs Linked style sheets:
	Embedded is quicker to access and edit
	Linked can be applied to more than one file

In an img element srcset can also be used(but src is still required for backup), this allows you to put in multiple sources for the same element, separated by commas. The sizes attribute is regularly used to tell the browser the size of each source in the set, from here the browser can choose the appropriately sized source for the current window size. 

Device Pixel Ratio(DPR) can be selected from the f12 menu in browser by accessing device toolbar(mobile view).

@media is a css query that can set the rules for any media on the page

type = "image/webp" or /svg+xml or /png etc. Used to define the image format for browser capabilities , providing different formats based on what the browser can render

npm, Node Package Manager is a registry that lists nodes of. with npm you can install any package as a dependency in the file. this might appy to json.
npx, Node Package Execute is used to execute a package without installing it. 