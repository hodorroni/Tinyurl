##How to Run the Application 
Initialize Services: Open the project terminal and run the following command:

docker-compose up -d
This command initializes Redis, MongoDB, and Cassandra. The application will not run without these services.

Run the Application: After successful initialization, launch the application using your preferred Integrated Development Environment (IDE).

Access Swagger UI: Open your web browser and navigate to:

http://localhost:8080/swagger-ui.html
This will provide a visualization for the backend APIs.

How to Use the Application
Access User Creation: In the Swagger UI, locate the app-controller section.

##Create a User:

Open the POST endpoint for /user.
Enter a name in the provided field and click the Try it out button.
You should receive a response with a status code of 200 if the user is created successfully.
Shorten a URL:

Navigate to the POST endpoint for /tiny.
Click on the example value (the yellow window) on the right side to fill in the details:
longUrl: For example, https://www.google.com
userName: Use the name you created earlier.
Click Try it out to submit the request.
Receive Shortened Link: After submitting, you should receive a shortened link. Clicking on this link will redirect you to the original URL specified above.

View User Information: You can find users and see which URLs they have shortened, along with the number of clicks each shortened link has received.
