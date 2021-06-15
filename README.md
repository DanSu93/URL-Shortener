# URL-Shortener
Simple Go URL Shortener automatically creating short links

In this project i use package gorilla/mux as a router and dispatcher for matching incoming requests to their respective handler. I prefer to use it because:
- requests can be matched based on URL host, path, path prefix, schemes, header and query values, HTTP methods or using custom matchers;
- registered URLs can be built, or “reversed”, which helps maintaining references to resources;
- very popular, well documented.
