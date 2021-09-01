Clone the repo

Run command npm install

Run command npm run dev

Browse http://localhost:3006/


Able to render HTML from server 


 ReactDOMServer.renderToString(<App />);

 
Render a React element to its initial HTML. This should only be used on the server. 

React will return an HTML string. You can use this method to generate HTML on the server and send the markup 
down on the initial request for faster page loads and to allow search engines to crawl your pages for SEO purposes.

If you call ReactDOM.hydrate() on a node that already has this server-rendered markup, 

React will preserve it and only attach event handlers, allowing you to have a very performant first-load experience.


