---
marp: true
---
<!-- class: invert -->

# A Normal Connection

When you normaly connect to a website/server you send a get request (or any other HTTP request) to the server. The server then processes that request and sends a response back to you.

---

# A Proxy Connection

When you connect to a website/server via a proxy your actually sending the HTTP request to the proxy server. The porxy server may modify this request and then send it off to the real website your trying to connect to. The real server than sends the response to the proxy server instead of you. The proxy server may modify this response and then send it back to you.

---

# UBTW2

[UBTW2](https://github.com/commandergl/ubtw2) is a proxy server used to unblock websites on school chromebooks. UBTW2 is still under development but is still extremly powerful. The way UBTW2 works is by injecting javascript into the website before you get the data. This javascript code replaces all URLs to also go through the proxy server.