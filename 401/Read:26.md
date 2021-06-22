# Routing

React Router v4 is a pure React rewrite of the popular React package.

- Single-page application?

single-page application is an app that doesn't need to reload the page during its use and works within a browser. Think of the apps you use daily: Facebook, Google Maps, Gmail, Twitter, Google Drive, or even GitHub.

When starting a new project, you need to determine which type of router to use. For browser based projects, there are <BrowserRouter> and <HashRouter> components. The <BrowserRouter> should be used when you have a server that will handle dynamic requests (knows how to respond to any possible URI), while the <HashRouter> should be used for static websites (where the server can only respond to requests for files that it knows about).