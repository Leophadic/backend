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
