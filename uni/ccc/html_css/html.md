Hypertext Markup language
**HTML** uses a series of [[elements]] to enclose, or **wrap**, the different parts of your **content**, with each element affecting the content differently. 
Elements can be **nestled** in other elements, meaning they open and close within another element.
The **Tags** are what define the opening and closing of each element.
![[html_element.png]]
Elements can have attributes, which contain extra information about the element. 
![[element_attribute.png]]
**Attributes** have a name and most have a value, attributes with a value always us the formatting above. Attributes are always placed in the opening tag and have a space between them.

Some elements have no content and therefore no closing tag, these are called **Void** Elements. An example is the image (img) element in the document HTML below.

Use **Descriptive** Markup that has **semantic** value.
Descriptive - using the elements to describe what the content means. 
Stratified - separating content from presentation of said content. This is CSS.
Dynamic- different presentation to suit circumstances
Semantic -Enables machine processing


<html>
	<head>
		<title></title>
		<meta name="date" content="20234-0104"> 
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width">
	</head>
	<body>
		<header>
			<h1>Header 1, biggest heading syntax</h1>
			<p>Paragraph start, if left unclosed auto adds break and closes
			<p>This is a new line after break</p>
		</header>
		<img src="images/images-name.opng" alt="image description" />
		<section>
			<h1>New Heading</h1>
			<p> Text manipulation uses tags like <em>Emphasis (Italics)</em> 
			or <strong>Strong Emphasis (Bold)</strong> </p> 
		</section>
		<footer>
			<p>This is an unordered list:</p>
			<ul>
				<li>Item 1</li>
				<li>Item 2</li>
				<li>Item 3</li>
			</ul>
			<p>This is an ordered list:</p>
			<ol>
				<li>Item 1</li>
				<li>Item 2</li>
				<li>Item 3</li>
			</ol>
		</footer>
		
	</body>
</html> 
HTML and CSS uses ids to give elements unique ID. This is done using id=id_name within the opening tag. To call this id you use #id_name, this call can be used as a selector in CSS or as an identifier for anchors.
class=class_name can be used in the same way but isn't unique to one element. To use a class as a selector you use the format .class_name {}