Specify Index Page with a Servlet Demo
=======================

Use a servlet as a index page.

```
mvn jetty:run
```

Then visit <http://localhost:8080>, you will see the content from the servlet.

Note
----

The `webapp/hello.html` is a placeholder, it should exist but not used.

If we don't provide it, it will just list all files when visit <http://localhost:8080>
