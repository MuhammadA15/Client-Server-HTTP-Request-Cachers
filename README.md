# Client-Server-HTTP-Request-Cacher
Mock client-server program that allows client to send URLs to the server. The server then makes an HTTP request over port 80 to the URL sent by the client and if it exists, the HTTP response is cached into a file. The URL is also stored into a cache file which can only hold up to 5 URLs at once. If the client sends a URL and the cache is full, the server will delete the oldest entry and its corresponding HTTP file.
