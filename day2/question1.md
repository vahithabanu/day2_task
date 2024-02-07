Blog on difference between document and window objects:

Document Object:

-It represents any HTML document or web page that is loaded in the browser.

-It is loaded inside the window.

-It is the object of window property.

-All the tags, elements with attributes in HTML are part of the document.

-We can access the document from a window using the window. Document

-The document is part of BOM (browser object model) and dom (Document object model

syntax:

document.propertyname;


Window object:

-It represents a browser window or frame that displays the contents of the webpage.
  
-It is the very first object that is loaded in the browser.

-It is the object of the browser.

-Global objects, functions, and variables of JavaScript are members of the window object.

-We can access the window from the window only. i.e. window.window

-The window is part of BOM, not DOM.

syntax:

window.propertyname;


Properties of document:

Active element: It returns the currently active elements in the document.

body: It returns the contents of the body element.

anchors: It returns all <a> elements that have a name attribute.

baseURI: It returns a string value that represents the base URI of the document.

charSet: It returns a string, representing the document’s character encoding.

defaultView: It returns the current Window Object.

designMode: It is used to set documents as editable or read-only.

doctype: It returns the document’s doctype.

URL: It returns the complete URL of the document.

forms: It returns all the elements of the form.

title: It returns the title element of the document.

head: It returns the head element of the document.

links: It returns all <area> and <a> elements that have a href attribute.

lastModified: It returns the date and time of the current document that was last modified.

images: It returns the collection of <img> elements in the document.

readyState: It returns the loading status of the current document.

scripts: It returns all script elements present in the document.

Properties of the window:

Closed: It holds a Boolean value that represents whether the window is closed or not.

console: It returns a reference to the console object which provides access to the browser’s debugging console.

crypto: It returns the browser crypto object.

Document: It returns a reference to the document object of that window.

frames[]: It represents an array that contains all the frames of a given window.

History: It provides information on the URLs visited in the current window.

Length: It represents the number of frames in the current window.

fullScreen: This property indicates whether the window is displayed on full screen or not.

Location: It contains the URL of the current window.

Name: It contains the name of the referenced window.

Window: It returns the current window or frame.

Navigator: It returns a reference to the navigator object.

Status: It overrides the default status and places a message in the status bar.

Top: It returns a reference to the topmost window containing a frame if many windows are opened.

Toolbar: It will result in the toolbar object, whose visibility can be toggled in the window.

Opener: It contains a reference to the window that opened the current window.

Parent: It refers to the frameset in which the current frame is contained.

Screen: It refers to the screen object

Self: It provides another way to refer to the current window.








