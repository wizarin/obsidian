<!-- This is a comment, Click below for html tags-->
<!doctype html> Required, this ensures the webpage is using the latest version of HTML
<html lang="en-US"> Root element, lang attribute sets the docs primary language
	<head></head> Used to store content for the page that doesn't appear on the page. SEO, CSS, character set declarations
	<meta charset="utf-8"> Sets the character set to 8, this has characters from most languages
	<meta name="viewport" content="width=device-width">
	<title></title> Every page MUST have one. The name of the browser tab and bookmark
	<body></body>This contains all content. Text, images, videos, games, audio tracks
	<h1>Text</h1> ... <h6></h6> Headings
	<p>Text</p> Paragraphs
	<em>Text</em> Emphasis - Italics
	<strong>Text</strong> Strong Emphasis - Bold
	<header></header>
	<article></article>
	<section></section>
	<footer></footer> Parts of a document
	<a href="https://www.website.com/home#hello">Text</a> Anchor, used for hyperlinks can eb linked to same page using fragment url(hello in url above). fragment urls are made using 
	<a href = "#hello">nestled tags or text</a> in the tag you are anchoring to you would have id="hello"
	<ul></ul> Unordered List - Bullet points
	<ol></ol> Ordered List - Numbers
	<li>Text</li> Used for to hold the content for each item in a list
	<img src="C/image-name.png" alt="my test image" /> Image element, attributes for file path and alt text if image doesn't load,
	<code>tags text as computer code, default formatting in monospace font</code>
	<span</span> Does nothing on its own but is used to encapsulate global attributes like
	<picture> Used to adjust images based on window size or other functions
		<source 
			type = "image/webp" <!-- Used to define the image format for browser capabilities , providing different formats based on what the browser can render-->
			media = "object name in media class"
			srcset = "
				img1,
				img2",>
		<source>
		<source>can have many sources with srcset in them
		<img src ="" alt=""> requires img element for backup
	</picture> class, lang or dir.
</html>
 


