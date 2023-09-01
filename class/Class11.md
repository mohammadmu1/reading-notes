**Role of @Controller classes in Spring MVC:**
- Think of @Controller classes as traffic managers for a website.
- They decide where to take you when you visit a website, such as showing the homepage or a specific page.
- They determine which part of the website to display when you click links or type addresses.

**Explanation of a GET request to a non-technical friend:**
- Imagine the internet as a giant library of web pages.
- When you click a link or type a web address, you're asking the library for a specific book (web page).
- A GET request is like sending a polite request to the librarian, saying, "Can I have this book, please?"
- You're not changing anything; you're just asking for information.

**Annotation for Spring Boot application class:**
- In a Spring Boot application, you use the `@SpringBootApplication` annotation on your main class.
- It tells Spring Boot, "This is where our app begins."
- Spring Boot takes care of everything else, like setting up the app's environment, so you don't have to worry about it.


1. **Method to display a Java variable in HTML with Thymeleaf:**
   - To show a Java variable in HTML using Thymeleaf, use `${variableName}` in your HTML.
   - Just make sure the `variableName` matches the name of your Java variable in the Spring Controller.

2. **Role of a @Controller class in a Spring MVC application:**
   - A `@Controller` class in Spring MVC handles requests from web browsers.
   - It's like a traffic cop for your website, deciding what to show when you click or type something.
   - It collects data (model attributes) and decides which page (view) to display.

3. **What is a model attribute referred to in Thymeleaf:**
   - In Thymeleaf, a model attribute is like a special variable.
   - It's data that the Controller prepares for the web page.
   - You can use `${attributeName}` in HTML to put that data on the page, where `attributeName` matches the name in the Controller.
