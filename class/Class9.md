## HTTP Request Steps

1. **Local Setup**: Your browser figures out what you're asking for from the website's address.
2. **Get IP Address**: Your browser finds the unique address of the website's server using its name.
3. **Connect**: Your browser and the server do a special handshake to set up a line to talk on.
4. **Ask**: Your browser sends a message asking for what you want from the website.
5. **Get Response**: The server sends back the thing you asked for.

## Things Client Needs Before Asking

- **Website's Address**: The name of the website you want to visit.
- **Connected Line**: A way to talk to the website's computer.

## Four-Way Handshake

1. **Goodbye from You**: You say you're done talking and want to leave.
2. **Got It from Server**: The website's computer says it got your message.
3. **Goodbye from Server**: The website's computer says it's done talking too.
4. **Got It from You**: You say you got the message that the website's computer is leaving.


## HTTP Request Simplified

1. **True or False: When making an HTTP request, you MUST follow any redirect returned by the request.**
   - **False**: You don't always have to follow redirects. It depends on your needs.

2. **Which built-in Java class can be used to perform an HTTP request?**
   - **`HttpURLConnection`**: This is the Java class you use to talk to websites.

3. **What HTTP status codes represent a successful response? A redirect? A client error?**
   - **Successful**: Codes like **200 OK** show things went well.
   - **Redirect**: Codes like **301** and **302** say the page moved somewhere else.
   - **Client Error**: Codes like **400** and **404** mean you made a mistake in your request.
