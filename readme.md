1. Difference between HTTP and HTTPS (Simple Terms)

HTTP (HyperText Transfer Protocol) is a protocol used to transfer information between a web browser and a website. It does not encrypt the data being sent, so anyone who intercepts it may be able to read it.

HTTPS (HyperText Transfer Protocol Secure) is the secure version of HTTP. It encrypts the data exchanged between your browser and the website using SSL/TLS encryption, making it much safer for sensitive information like passwords, credit card details, and online banking.

2. JSON Object Representing a Student Enrolled at Marusoft Technologies

{
  "studentId": "MT2026001",
  "firstName": "John",
  "lastName": "Doe",
  "age": 22,
  "gender": "Male",
  "institution": "Marusoft Technologies",
  "course": "Full Stack Web Development",
  "email": "john.doe@example.com",
  "phone": "+2348012345678",
  "enrollmentDate": "2026-06-29",
  "status": "Active"
}

3. Five Real-World APIs You Use Every Day


Google Maps API – Provides maps, directions, and location services.
Weather API – Supplies current weather and forecasts in weather apps.
Payment APIs (e.g., Stripe or Paystack) – Process online payments securely.
YouTube API – Retrieves videos, playlists, and channel information.
Social Media APIs (e.g., Facebook, Instagram, or X) – Enable apps to share content, log in, and retrieve social data.



4. Compare REST and GraphQL.

REST uses multiple URLs (endpoints) to access different resources, such as /users or /products. It returns a fixed amount of data determined by the server, which can sometimes include more or less information than needed. REST is simple to learn and widely used.

GraphQL uses a single endpoint, usually /graphql, where the client specifies exactly what data it wants. This avoids receiving unnecessary data and makes it more efficient for applications that require complex or customized queries. However, GraphQL is generally more complex to learn than REST.



5. Explain the Request–Response cycle using a banking application as an example.

The Request–Response cycle is the process where a client (such as a banking app) sends a request to a server, and the server processes the request and sends back a response.

Example: Checking your account balance

You open your banking app and tap "Check Balance."
The banking app sends a request to the bank's server asking for your account balance.
The server verifies your identity and checks your account information in the database.
The server retrieves your account balance.
The server sends the balance back to the banking app.
The app displays your current balance on your screen.

This same request–response process happens whenever you log in, transfer money, pay bills, or perform any other action in a banking application.




Explain Backend Development in your own words.

Backend development is the part of software development that focuses on everything that happens behind the scenes of a website or application. It is responsible for processing user requests, managing databases, handling authentication, performing business logic, and sending the correct information back to the user. In simple terms, the backend is the "brain" of an application that makes everything work.

2. Draw a Client–Server Architecture Diagram.
             Client–Server Architecture

        +------------------+
        |      Client      |
        | (Browser/Mobile) |
        +------------------+
                 |
                 | HTTP Request
                 ▼
        +------------------+
        |      Server      |
        | (Backend/API)    |
        +------------------+
                 |
                 | Query
                 ▼
        +------------------+
        |     Database     |
        +------------------+
                 ▲
                 | Data
                 |
        +------------------+
        |      Server      |
        +------------------+
                 |
                 | HTTP Response
                 ▼
        +------------------+
        |      Client      |
        +------------------+
3. Compare HTTP and HTTPS.

HTTP (HyperText Transfer Protocol) is used to transfer data between a web browser and a web server. It does not encrypt the information being sent, making it less secure.

HTTPS (HyperText Transfer Protocol Secure) is the secure version of HTTP. It encrypts all data exchanged between the browser and the server using SSL/TLS, protecting sensitive information such as passwords, banking details, and personal data.

Simple Example:

HTTP is like sending a postcard that anyone can read.
HTTPS is like sending a sealed envelope that only the recipient can open.
4. Explain the Request–Response cycle using an online shopping example.

The Request–Response cycle is the communication process between a client (browser or app) and a server.

Example: Buying a phone online

You open an online shopping website.
You click on a phone and select "Buy Now."
Your browser sends a request to the server asking to purchase the phone.
The server checks the product availability and processes your order.
The server sends a response confirming whether the purchase was successful.
Your browser displays a message such as "Order placed successfully."
5. Create three valid JSON objects.
Student
{
  "studentId": "ST001",
  "name": "John Doe",
  "age": 21,
  "department": "Computer Science"
}
Course
{
  "courseId": "CS101",
  "courseName": "Backend Development",
  "duration": "12 Weeks",
  "instructor": "Mr. David"
}
Product
{
  "productId": "P1001",
  "productName": "Wireless Mouse",
  "price": 15000,
  "stock": 25
}
6. List five HTTP methods and describe when each should be used.
GET – Used to retrieve data from a server, such as viewing a list of products.
POST – Used to send new data to the server, such as creating a new account or placing an order.
PUT – Used to completely update an existing resource, such as updating all details of a user's profile.
PATCH – Used to partially update an existing resource, such as changing only a user's phone number.
DELETE – Used to remove a resource from the server, such as deleting a user account or a product.
7. Research one public API and explain what it does.

One popular public API is the OpenWeather API.

The OpenWeather API provides weather information for locations around the world. Developers use it to display current weather conditions, hourly and daily forecasts, historical weather data, air quality information, and weather alerts in websites and mobile applications. It returns data in JSON format, making it easy for applications to process and display weather information. To use the API, developers typically sign up for an API key and send requests with a location, after which the API responds with the requested weather data.