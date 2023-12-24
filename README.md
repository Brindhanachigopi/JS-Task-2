**"# JS-Task-2"**

# Document and Window Objects

**Window Object:**

The window object represents the browser window and serves as the global object in client-side JavaScript. It encapsulates the entire browser window, including tabs, frames, and iframes. The window object provides access to various properties and methods related to the browser environment, such as opening new windows, resizing, scrolling, and interacting with the browser's history.

+ It represents the browser window in which you are seeing the content.

+ The properties related to it are stored in the window object.

+ It is loaded before the document because window container document.

+ The window is the global element for all objects, functions, etc.

+ It is an object of the browser.

+ We can access document object properties inside the window.
```
logically:

    window:{
        document:{properties}
    }
```
+ Example: window.document.title will return the title of the document.

**Document Object:**

The document object represents the current web page displayed in the browser window. It provides access to the HTML content of the page and allows you to manipulate the structure, content, and styling using the Document Object Model (DOM). Through the document object, you can access elements, modify their attributes and content, and respond to user interactions.

+ It represents the document loaded inside the window or browser.

+ The properties related to it are stored in the document object.

+ It is loaded after the loading window because the window contains a document.

+ It is the root element of the document object model.

+ It is an object of window.

+ We can not access windows objects properties inside the document.
```
logically:

document:{ properties}
```
+ Example: document.title will return the title of the document.

