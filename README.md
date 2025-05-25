**#Book-My-Show**

### 'Project Summary:'

This web application allows users to select movie names, choose a slot, and book seats for their preferred showtimes. The app also provides users with the option to view their previous bookings. The project utilized a combination of front-end and back-end technologies to deliver a seamless user experience.

**Front-End Technologies:**

React: We chose React as our front-end framework due to its component-based architecture, which enabled us to create reusable UI elements and efficiently manage state throughout the application.

CSS Styling: We used CSS to style the application, ensuring an attractive and intuitive user interface that aligns with the Book My Show brand.

React Hooks: Leveraging React Hooks allowed us to manage state and perform side effects, such as API calls, within functional components.

Axios: To fetch data from the server, we integrated Axios, a popular JavaScript library that simplifies the process of making HTTP requests.

**Back-End Technologies:**

MongoDB: We selected MongoDB as our database to store movie details, slot information, seat availability, and user bookings. Its flexibility and scalability made it an ideal choice for our application.

Express.js: As the back-end framework, Express.js facilitated the creation of a robust API for handling user requests, managing data, and communicating with the database.

The backend of the application works in conjunction with the Front-end to handle user data. It utilizes the powerful capabilities of MongoDB Atlas, a cloud-based database service, to store and retrieve the user data.

When a user interacts with the frontend, such as making a booking, the backend receives the data from the frontend. It securely stores the received data in the MongoDB Atlas database for future reference.

The backend seamlessly handles the storage and retrieval of user data, ensuring that the necessary information is stored accurately and efficiently. When a user performs an operation, such as booking a movie ticket or updating their seat selection, the backend fetches the relevant data from the database and presents it back to the user.

By utilizing the capabilities of MongoDB Atlas, the backend provides a reliable and scalable solution for managing user data. It ensures that the operations performed by users are successfully completed and the data remains easily accessible for future interactions.

This integrated approach between the frontend and backend, coupled with the power of MongoDB Atlas, delivers a seamless and efficient user experience while maintaining the integrity and persistence of user data.

Overall, here successfully implemented a Book My Show app that allows users to conveniently book movie tickets online. By utilizing React, CSS, React Hooks, and Axios on the front end, along with MongoDB and Express.js on the back end, we delivered a seamless and user-friendly experience. The app offers the essential features of movie selection, slot and seat selection, booking confirmation, and a history of previous bookings.
