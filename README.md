# JavaScript 2 - Progressive Web Apps

## Objective

Create a class that would expand on the concepts of Mobile Friendly First (Responsive Content, Accessibility) and Intro to Javascript (Promises, Objects, Handling Data). Additionally, this class would serve as an introduction to databases and making requests to create, read, update, or delete data.

## Technologies

1) Vanilla JavaScript - No Front-End Frameworks (i.e. Angular, React, etc.)
1) [Service Workers](https://developers.google.com/web/ilt/pwa/introduction-to-service-worker) - Cache assets like project files and images for offline access
1) [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) - Use the Fetch API to create, read, update, or delete data from a database
1) [Indexed DB](https://github.com/jakearchibald/idb) - Store data retrieved from a DB to to be accessible for offline use

## Project

###### Students would be provided with a local server that contains some mock JSON data. That website they build should:

1) Utilize a service worker to cache assets like project files and images for offline use.
1) Use the Fetch API to retrieve and modify data.
1) Store any retrieved data in an Indexed DB database.
1) If there is no network connection, pull data from Indexed DB.
1) If there is no network connection, store network requests until a connection is established, then send the request.
1) Adapt to any screen size.
1) Be built with accessibility in mind by maintaining proper tab order, aria attributes, color contrast, etc.
1) Use optimized for web photos. Optionally, lazily load these images with the [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API).
1) Maintain basic functionality with no online connection.
