# DevNest Education Tech
DevNest is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

## Table of Content
| Section  | Description |
| ------------- | ------------- |
| Aim  | Goals of DevNest  |
| Tech Stack  | Technologies Used  |
| Functionalities  | All the functionalities DevNest provides  |
| System Architecture  |  Flow of project |
| API Design  | All the Apis used  |
| Screen Preview  | Screenshots  |

## Aim
DevNest aims to provide: <br/>
A seamless and interactive learning experience for students, making education more accessible and engaging.
A platform for instructors to showcase their expertise and connect with learners across the globe.

## Tech Stack
HTML, CSS, Tailwind, JS, React.js, Node.js, Express.js, MongoDB, RESTFul APIs, JWT, Cloundinary

## Functionalities

For Students:
1. Homepage: This page will have a brief introduction to the platform, as well as links to the course list and user details.
2. Course List: This page will have a list of all the courses available on the platform, along with their descriptions and ratings.
3. Wishlist: This page will display all the courses that a student has added to their wishlist.
4. Cart Checkout: This page will allow the user to complete the course purchase.
5. Course Content: This page will have the course content for a particular course, including videos, and other related material.
6. User Details: This page will have details about the student's account, including their name, email, and other relevant information.
7. User Edit Details: This page will allow the student to edit their account details.

For Instructors:
1. Dashboard: This page will have an overview of the instructor's courses, as well as the ratings and feedback for each course.
2. Insights: This page will have detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.
3. Course Management Pages: These pages will allow the instructor to create, update, and delete courses, as well as manage the course content and pricing.
4. View and Edit Profile Details: These pages will allow the instructor to view and edit their account details.


## System Architecture

1. Front-end<br/>
The front end of the platform is built using ReactJS, which is a popular JavaScript library for building user interfaces. ReactJS allows for the creation of dynamic and responsive user interfaces, which are critical for providing an engaging learning experience to the students. The front end communicates with the back end using RESTful API calls.

2. Back-end<br/>
The back end of the platform is built using NodeJS and ExpressJS, which are popular frameworks for building scalable and robust server-side applications. The back end provides APIs for the front end to consume, which include functionalities such as user authentication, course creation, and course consumption. The back end also handles the logic for processing and storing the course content and user data.

3. Database<br/>
The database for the platform is built using MongoDB, which is a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data, which is useful for storing course content such as videos, images, and PDFs. The database stores the course content, user data, and other relevant information related to the platform.


## API Design

Sample list of API endpoints and their functionalities:<br/>
1. /api/auth/signup (POST) - Create a new user (student or instructor) account.
2. /api/auth/login (POST) – Log in using existing credentials and generate a JWT token.
3. /api/auth/verify-otp (POST) - Verify the OTP sent to the user's registered email.
4. /api/auth/forgot-password (POST) - Send an email with a password reset link to the registered email.
5. /api/courses (GET) - Get a list of all available courses.
6. /api/courses/:id (GET) - Get details of a specific course by ID.
7. /api/courses (POST) - Create a new course.
8. /api/courses/:id (PUT) - Update an existing course by ID.
9. /api/courses/:id (DELETE) - Delete a course by ID.
10. /api/courses/:id/rate (POST) - Add a rating (out of 5) to a course.
<br/>
Sample API requests and responses:<br/>
1. GET /api/courses: Get all courses<br/>
Response: A list of all courses in the database<br/>
<br/>
2. GET /api/courses/:id: Get a single course by ID<br/>
Response: The course with the specified ID<br/>
<br/>
3. POST /api/courses: Create a new course<br/>
Request: The course details in the request body<br/>
<br/>
Response: The newly created course<br/>
4. PUT /api/courses/:id: Update an existing course by ID<br/>
Request: The updated course details in the request body<br/>
Response: The updated course<br/>
<br/>
5. DELETE /api/courses/:id: Delete a course by ID<br/>
Response: A success message indicating that the course has been deleted.


# Screen Preview

![6](https://github.com/user-attachments/assets/d74f54d9-e8a8-4f7f-ba50-0f11160fac8b)
<br/>
<br/>
![5](https://github.com/user-attachments/assets/dc1fad54-e125-412b-88f6-ef86ba8f2243)
<br/>
<br/>
![4](https://github.com/user-attachments/assets/8e9afc8e-e6e4-41cd-8fc0-b1d1f6c0007a)
<br/>
<br/>
![3](https://github.com/user-attachments/assets/5b8908db-b8e8-47c0-9b2b-d0b54df79cbe)
<br/>


