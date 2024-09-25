Browser Lifecycle

The client's device makes a request to the application server to access the application. The app server returns the data required and what needs to be shown (rendered) on the device's screen. In the case of a browser-based web application, the browser receives this data from its networking layer, which is then passed on to the rendering engine. Different browsers use different rendering engines: Internet Explorer uses Trident, Microsoft Edge uses EdgeHTML (older versions) or Blink (newer versions), Firefox uses Gecko, and both Safari and Chrome (along with Opera from version 15) use WebKit and Blink, respectively.

Rendering Pipeline Overview

    HTML Parsing into DOM
    The rendering engine parses the HTML and converts it into a tree of DOM (Document Object Model) nodes called the "DOM tree." Each node corresponds to an HTML tag, forming the content structure of the page.

    CSS Parsing into CSSOM
    Simultaneously, the browser parses the CSS stylesheets and inline styles to build a CSS Object Model (CSSOM), which is a tree-like structure representing the styles to be applied to the DOM.

    JavaScript Execution
    Once the DOM and CSSOM are built, the browser executes JavaScript. JavaScript can modify both the HTML (DOM) and CSS (CSSOM). However, JavaScript execution can block other processes, particularly parsing, unless asynchronous or deferred methods are used to load the scripts.

    Layout Phase
    The browser uses the DOM and CSSOM to create a Render Tree, which defines the layout of the page. This step calculates the positions of all elements on the page. Any changes to the DOM or CSSOM trigger reflow, which recalculates the layout—a potentially resource-intensive task.

    Painting
    After the layout is determined, the browser begins the paint process, converting elements into pixels. The browser uses its graphics engine (e.g., Skia in Chromium-based browsers or WebRender in Firefox) to render these pixels on the screen. The final painted image is then displayed to the user.

Front-End Execution

The browser’s default rendering process can effectively display web pages, but it becomes inefficient for dynamic content or frequent updates because it often involves transferring large amounts of data or re-rendering entire pages. To improve performance and user experience, front-end libraries and frameworks like React, Vue.js, and Angular have emerged. These frameworks optimize the rendering process by creating a Virtual DOM—a lightweight in-memory representation of the actual DOM. Only the necessary changes between the virtual DOM and the actual DOM are sent to the browser, reducing re-rendering and improving performance.
Front-End Framework Lifecycle

These front-end frameworks also introduce a component-based architecture. The lifecycle of these components is essential to understanding how they render, update, and clean up during their existence.

    Mounting
    The component is created and inserted into the DOM. This is when the constructor is called in React, initializing the component’s state and props. The state represents data that belongs to the component and triggers updates whenever it changes.

    Updating
    Changes in the component’s state or props trigger an update and re-render. In React, updates can be triggered by events like form input changes, mouse clicks, or keyboard interactions, which alter the state and cause the component to re-render with the updated information. These updates are efficient, only re-rendering parts of the UI affected by the change.

    Unmounting
    When a component is no longer needed, it is removed from the DOM, and React cleans up any associated resources, like event listeners or timers, to prevent memory leaks.