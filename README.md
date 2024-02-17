# HTML-Integration

HTML must be integrated with other technologies to create dynamic, interactive, and aesthetically pleasing websites. Web pages are made possible by the mix of HTML, CSS, JavaScript, and server-side languages, which give them structure.

HTML AND CSS:
-------------------------------------------------------
Purpose: CSS (Cascading Style sheet) is used for styling HTML elements. It controls layout, colors, fonts, and the overall feel of a webpage.

Integration: CSS can be split in 3 ways:
--------------------------------------------------------
Inline styles: directly within HTML elements using the style attribute.
Internal stylesheet: within the <head> section of a document using <style> tags.
External stylesheet: linking the external CSS file using <link rel=” stylesheet”.

HTML AND JAVASCRIPT:
---------------------------------------------------------
Purpose: Web sites can have interactive elements and dynamic content thanks to JavaScript. It can react to user events, change HTML elements and CSS styles in real time, and retrieve data from servers without requiring a page reload.

Integration: JavaScript can be integrated into HTML documents in several ways:
----------------------------------------------------------
Inline: directly in HTML elements event attributes (e.g., onclick, onload).
Internal: within <script> tags in the HTML document, typically placed in the <head> or at the bottom of the <boy> to ensure the DOM is fully loaded.
External: linking to the external JavaScript files using <script src=” filename.js”> </script>

HTML and server-side languages:
---------------------------------------------------------
Purpose: server-side languages such as (e.g. PHP, Python, Ruby, Node.js) are used to generate dynamic HTML content, interact with databases and perform backend tasks.
Integration: server-side script generates content on the server and send it to the client. HTML forms can send data to server-side script for processing.

HTML and APIs/ Web Servers:
---------------------------------------------------------
Purpose: APIs and web services allow HTML pages to interact with external data sources and services.
Integration: using JavaScript to fetch data from APIs and dynamically insert it into the HTML document.

HTML DOCUMENT HEAD:
---------------------------------------------------------
THE <HEAD> section of the HTML document is a critical area that contains metadata, links to external resources and other elements that are not directly visible to users on the web pages itself. The head provides search engines and web browsers important details about the activity and content of the website.
The <TITLE> tag defines the title of the document which is displayed on the browser’s title bar or tab.

META Tags: 
---------------------------------------------------------
<meta charset=” UTF-8”>: specifies the character encoding for the document, essential for rendering.
<meta name =” viewpoint” content = “width=device-width, initial-scale=1.0”>:  It gives the browser instructions on how to manage the page's size and scale, which is crucial for responsive design.

Links to external sheets:
--------------------------------------------------------------
o	<link rel=” stylesheet” href=” style.css”>: links to the external style sheet for the website.
o	<link rel= “icon” href= “favicon.ico” type=” image/x-icon”>:  Specifies a favicon for the website, displayed in the browser's address bar and tabs.

Scripts: 
----------------------------------------------------------------
o	<script src= “script.js”></script>: links to external JavaScript file. While non-render blocking or async scripts can be placed in the body of a page, loading times for non-essential features can be accelerated by placing them in the head.

Other elements:
-----------------------------------------------------------------
o	<style>: contains the CSS external file.
o	<base href=” ….”: specifies a base URL for all relative URLs in the document.
o	<link rel=” canonical” href=”…”>: helps prevent duplicate content issues n SEO by specifying the “canonical” or preferred version of a web page URL.

Content Structuring:
Main:
----------------------------------------------------------------
The main element instructs the browser where to find the main content and is used just once per webpage.
Header:
---------------------------------------------------------------
The header and footer elements mark the header and footer areas on the page. Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content (do not confuse head with header). A header is usually found at the beginning of the web page.

Footer:
----------------------------------------------------------------
The footer signifies that there are extra things to convey, regardless of its position on the page.

Article:
----------------------------------------------------------------
An article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header. Many web pages end with a footer at the bottom, containing links, copyright information, and additional details about the company. The article element wraps around any type of content unit, whether it is a long-written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.

Section:
------------------------------------------------------------------
The section element is used to mark sections of content. It is also useful for dividing different topic zones on a website. Each section typically starts with its own headline.

Aside:
------------------------------------------------------------------
Aside element is used for content that is off to the side, such as sidebar details or other information that goes with an article but isn't necessary for understanding its core idea. Advertisements can also be marked as an aside. Although the position on the page does not matter, the semantic meaning of these elements is crucial. The visual layout often conveys meaning, and these HTML elements help transfer that meaning from the design to the content.

When it comes together:
-----------------------------------------------------------------
When creating a web page with various HTML elements work together to form a cohesive structure, styling and functionality.
Document structure starts with the <Doctype html> declaration. The <HTML elements serves a root encapsulating the entire document.
In the <head> and <html> section contains metadata including the document title, character set and links to external sheet. The <body> section contains the content of the webpages.

Page layout:
-------------------------------------------------------------------
The <div> is responsible for grouping and structuring the content.
It helps create headers. Footers, sidebars and content areas allowing for flexible page layouts.
The semantic elements tags are: <header>, <footer>, <nav>, <main> and <article>

Text and formatting:
--------------------------------------------------------------------
Various text-related tags like <h1> to <h6>, <p>, and <span> are used for creating headings, paragraphs and inline styling.
Lists (<ul>, <ol>, <li>), line breaks (<br>), and horizontal rules (<hr>) help structure and format content.

Links and Media:
---------------------------------------------------------------------
Hyperlinks <a> are used to connect pages or resources.
Images <img> are embedded using the src attribute within appropriate containers.

Styling with CSS:
------------------------------------------------------------------
CSS is linked to HTML using the <link> tag or applied directly within the <style> tag.
Classes and IDs are used to target specific elements for styling.
The <style> tag in the <head> section or an external stylesheet enhances the visual presentation of the content.
