# uidai-sih
Created in Eclipse workspace

Problem statement is a part of Smart India Hackathon

In this project, I had formatted the address by removing the repetitive words in it.

PROBLEM STATEMENT

Address Formatting Issue Imagine you belong to the capital city of India and you reside within IIT Delhi campus. You have just enrolled yourself to the aadhaar identity platform and after successful enrolment, you have received your letter containing the aadhaar number, demographics data such as name and address. Alas, in the address field you see the repetition of ‘Delhi’ multiple times, making the address a little convoluted. Like you, many of the residents especially those who are residing inthe urban areas see the repetition of the same content in the final address.

SOLUTION) a) In my project, I had used java servlet api and jdbc along with MySQL database.

b) The dependencies that I had used are mentioned below:-

mysql-connector-java-8.0.25 jar Servlet-api-2.5

c) I had used Apache Tomcat v9.0 as a local server.

d) Working of the Code

Client page sends request to the Servlet API. Servlet API validates and sends value to the database. Database creates table, stores values in it and executes the required query JSP takes response from the servlet Client-page displays the required result.
