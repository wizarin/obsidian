## Uniform Resource Locator

URLs can be absolute or relative. An absolute URL is the path that resource is contained in. Relative URL
Scheme
	This is the first part of the URL, it indicates which protocol the browsers uses to request the resource located at the URL

Authority
	Separated from the scheme by `://` This is the *domain* name, it can be followed by a *port* using `:`

Path to Resource
	This points to the resource on the web server. It used to point to the physical file path on the server but is now an abstraction handled by the server. Starts with and is separated by `/`

Parameters
	These are optional values passed to the server starting with `?` then the parameter name and what it equals, separated by `&`

Anchor
	This is a kind of 'bookmark' that points to a part of the resource with the browser only showing what the anchor points to. This is handled by the browser, the server provides the whole resource and the browser reads the anchor to only point to a specific part of it.