
#### Part A (Theory)

#### 1)

While working on internet website the terms frontend and backend refer to the separation of concerns between the presentation layer (frontend), and the data access layer (backend). The front is an abstraction, simplifying the underlying component by providing a user-friendly interface, while the back usually handles data storage and business logic.Here's a breakdown of how the front-end and back-end work in the context of an internet website:

#### Front-end:

The part of a website that the user interacts with directly is termed the front end. It encompasses everything that a user sees, interacts with, and experiences in their web browser. The main technologies used in front-end development are HTML (Hypertext Markup Language), CSS (Cascading Style Sheets), and JavaScript.

The front-end is responsible for delivering a visually appealing and user-friendly interface. It communicates with the back-end to retrieve and display data, handle user inputs, and provide a seamless user experience.

Key components of the front-end include:

HTML: It provides the structure and content of the web page using tags to define elements like headings, paragraphs, images, forms, etc.

CSS: Cascading Style Sheets are used to control the presentation and layout of the web page, including aspects like colors, fonts, spacing, and overall visual styling.

JavaScript: This programming language enables interactivity and dynamic behavior on the website. It allows for tasks like form validation, animations, and handling user interactions.

#### Back-end:
The back-end refers to the server-side of the website, which handles the behind-the-scenes operations and processes the data required by the front-end. It involves the server, the application logic, and the database.

The back-end handles tasks such as authentication, data processing, server-side validation, and database operations. It ensures the website's functionality, security, and performance.

Key components of the back-end include:

Server: The server is responsible for receiving requests from the client (front-end), processing those requests, and sending back the appropriate response. 

Application Logic: This represents the business logic and functionality of the website. It involves the programming languages and frameworks used to handle the data, process requests, and perform various operations on the server.

Database: It stores and manages the website's data. It allows for data retrieval, storage, modification, and deletion. The back-end interacts with the database to fetch and store information as requested by the front-end.




#### 2)

HTML tags are like keywords which defines that how web browser will format and display the content. With the help of tags, a web browser can distinguish between an HTML content and a simple content. HTML tags contain three main parts: opening tag, content and closing tag. But some HTML tags are unclosed tags.

In an HTML document, all tag names are differentiated from other simple text. The tag names are enclosed in between angle brackets or a ‘less than’ and a ‘greater than’ symbol, (<) and (>).

#### Syntax-

<tag> content </tag>

#### 1) Structural Tags:
Structural tags define the overall structure of the web page. They include:
#### <html>: Represents the root element of an HTML 

Example:

<html>
  <!-- Content -->
</html>

#### <head>: Contains metadata about the HTML document, such as the page title, character encoding, and CSS stylesheets.
Example:

<head>
  <title>My Page</title>
  <!-- add more metadata and stylesheets -->
</head>

#### <body>: Encloses the main content of the web page that is visible to the user.
Example:

<body>
  <h1>Welcome to My Page</h1>
  <p>This is the main content of the page.</p>
</body>

#### 2)Heading Tags:
Heading tags define various levels of headings on the page, ranging from the most important (h1) to the least important (h6).

Example:
<h1>Main Heading</h1>
<h2>Sub Heading</h2>

#### 3)Paragraph Tags:
Paragraph tags are used to define paragraphs of text.

Example:

<p>This is a paragraph of text.</p>
<p>Another paragraph goes here.</p>

#### 4)Link Tags:
Link tags define links to other web pages or external resources.

Example:

<a href="https://www.example.com">Visit Example.com</a>
#### 5)Image Tags:
Image tags are used to display images on the web page.

Example:

<img src="image.jpg" alt="Description of the image">

#### 6)List Tags:
List tags define ordered (numbered) and unordered (bulleted) lists.

Example of an unordered list:

<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

Example of an ordered list:

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>

#### 3)

DOM stands for ‘Document Object Model’. In simple terms, it is a structured representation of the HTML elements that are present in a webpage or web-app. DOM represents the entire UI of your application. The DOM is represented as a tree data structure. It contains a node for each UI element present in the web document.

Virtual DOM (Document Object Model) is a concept and technique used in frameworks of React to optimize and improve the performance of web applications. It involves creating a virtual representation of the actual DOM and using it to efficiently update and render changes to the web page.

Utilizing the Virtual DOM, the framework minimizes direct interactions with the real DOM, which can be a costly operation in terms of performance. The Virtual DOM acts as an intermediary layer that optimizes updates and reduces unnecessary rendering cycles.

 Here's a step-by-step explanation of how the Virtual DOM works:

Initial Render:
When an application starts or a component is first rendered, the Virtual DOM is created as an in-memory representation of the actual DOM.

Updating the Virtual DOM:
When there are changes in the application state or user interactions trigger updates, the Virtual DOM is updated rather than directly modifying the real DOM. 

Diffing:
The updated Virtual DOM is compared with its previous version to determine the differences between them. 

Computing the Minimal Set of Changes:
It determines which elements need to be added, modified, or removed to reflect the changes.

Applying Changes:
Once the minimal set of changes is computed, the framework applies these changes to the actual DOM. 

Reconciliation:
It updates the component state and triggers any necessary lifecycle methods to ensure that the application is in sync with the new DOM structure.

#### 4)Mention some Differences between MySQL and No SQL














#### 5)Explain any one DBMS Technology in your own words

One of the best technologies used in DBMS is postgreSQL.
PostgreSQL is like a reliable and efficient data warehouse that organizes information in a structured manner. It allows users to define their own data types, create tables, and establish relationships between them using keys. With its object-relational capabilities, PostgreSQL combines the benefits of both traditional relational databases and object-oriented programming.

#### Features are as follows:

Helps developers to build applications.

It allows administrators to build fault-tolerant environment by protecting data integrity.

Support for multi-version.

Full support for client-server network architecture.

PostgreSQL can run dynamic websites and web apps.

PostgreSQL supports geographic objects.


