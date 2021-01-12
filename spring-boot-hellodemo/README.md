# Servlet

Servlet is a technology/API/class that is used to handle requests in web applications and it resides on server side. Spring Boot uses Servlet to receive requests from client side.

There are two ways in Spring Boot to use Servlet Api:

1. Use @ServletComponentScan annotation.
2. Use @Bean annotation.

In this demo @ServletComponentScan annotation is used.

@ServletComponentScan: is making SpringBoot scan for @WebServlet annotation and it's only perform when using an embedded web server such as Spring Boot.

# Filter

Filter is a component that is used to preprocessing and postprocessing requests. It can be used to validate, encrypt/decrypt, and log requests. For instance, it can filter out a request if it contains some invalid content, or ignore requests that do not contain required request parameters.

# Lister

Servlet Listner is used for listening to events in a web container, such as when create a session or create an attribute in a session.
