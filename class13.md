# Welcome to reading notes code 201 class 13:

## Native client applications V.S web applications

### Advantage of native client applications over we applications:

- **The Persistent local storage** for storing and retrieving application-specific data is the main advantage of native web applications, where web application lacks this advantage.

### Disadvantages of web applications over native client applications:
- It didn’t had the advantage of storing data until the cookies were invented but still the cookies have many bad sides such as ; **slowing down the web application**, **sending data unencrypted over the internet** and are limited to about 4 KB of data.

### So, the hero of this problem was **HTML5 Storage**;

![html5 local storage](https://i2.wp.com/youvcode.com/wp-content/uploads/2017/07/html5-local-storage.png?fit=540%2C205&ssl=1)

#### What is HTML5 Storage?
   - we can say about it like a way for web pages to store named key-value pairs locally browser inside the client web browser.

**In comparison with cookies what HTML5 Storage added?**
   - The data is *never*transmitted to the remote web server.

**Which browsers support it?**
   - We can say almost all of the latest versions.

**How to use it?**
   - First you need to check if the browser support it.
   - Second you can access to it through the **localStorage** object.
   - Then you need to understand how it works.

**How it works?**
   - As I have said earlier that it uses the key-value pair as you store data based on a named key, then you can retrieve that data with the same key.
   - Named key is a *string* and the retrieved data will be as a string despite it can be different data types.
    - You can deal with this object as an array and to access its elements you can use square bracket.
    - There is also methods for *removing the value* for a given named key, or if you want to *clear the entire storage area*.

**Is there any limitation for **HTML5 Storage**?
- Yes, there is such as the storage space, by default, that each origin take is 5 megabytes. 

**Is there something that we can say it’s more advance than the HTML5 Storage?**
- Yes , first we have **Web SQL Database specification**, which we can say about it  that it’s like *backend database programming*, except you’re doing it from JavaScript.
- Then a better vision created which is “WebSimpleDB,” also known as “IndexedDB.”
What we can say about, which is also known as index database API, and I am quoting from a website :
  >The Indexed Database API exposes what’s called an *object store*. An object store shares many concepts with a SQL database. There are “databases” with “records,” and each record has a set number of “fields.”
  > my reference website [my local stprage](http://diveinto.html5doctor.com/storage.html)

