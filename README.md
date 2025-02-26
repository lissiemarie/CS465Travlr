This project is a full stack web application that serves both customer and administrative sides. In the final iteration, secure login authentication was added for the admin area. The application uses a combination of Express for server-rendered HTML and a Single-Page Application (SPA) built with Angular for richer admin functionality. The backend uses a NoSQL MongoDB database.

Architecture

**Frontend Development:**  
The customer-facing side of the application is built using Express and server-side HTML templating, which delivers static pages to users. For the administrative side, a Single-Page Application (SPA) was created using Angular and JavaScript. The SPA provides a more dynamic and responsive experience by managing state on the client, handling routing without full page reloads, and using reusable UI components to streamline development and maintenance.

**Backend Database:**  
A NoSQL MongoDB database is used for the backend. This choice was made because MongoDB offers a flexible schema that adapts well to changing data models and rapid prototyping. Its scalability and native support for JSON-like documents make it an ideal match for a JavaScript/Node.js environment.

Functionality

**JSON and JavaScript:**  
JSON is a lightweight, language-independent data interchange format that mirrors JavaScript’s object literal syntax. Unlike JavaScript, which can include functions and behaviors, JSON is strictly data. It serves as the common language between the frontend and backend, ensuring consistent communication across the application.

**Code Refactoring and Reusable Components:**  
Throughout the full stack process, code was refactored to improve functionality and efficiency. For instance, common HTTP request logic was consolidated into Angular services, and UI elements such as form inputs and navigation bars were abstracted into reusable components. These refactoring efforts reduced code duplication, simplified maintenance, and improved the overall modularity and scalability of the project.

Testing

**API and Security Testing:**  
To ensure the SPA worked with the API for GET and PUT operations, API endpoints were thoroughly tested using tools like Postman and browser developer tools. This testing verified that endpoints returned the expected data and that error handling worked properly. The addition of security features—such as token-based authentication—introduced extra layers of complexity, making automated testing more challenging. Tests had to simulate authenticated sessions and verify that secure endpoints behaved as expected. Overall, testing required a careful balance between functional verification and security assurance.

Reflection

This course has significantly advanced my full stack development skills. I learned to integrate Express with Angular, create dynamic SPAs, and implement secure login authentication. Mastering these techniques—along with the use of modern testing and debugging tools—has not only deepened my understanding of web application architectures but also enhanced my marketability as a developer. The experience of refactoring code for improved efficiency and learning to manage both client- and server-side security has prepared me to tackle more complex projects in my professional career.
