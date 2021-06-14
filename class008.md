
# Welcome to My eighth reading notes for class08 in 301 level.
## Our topic is **API Design Best Practices**

## API Design Best Practices

1.	What does REST stand for? 
> REST is an architectural style for building distributed systems based on hypermedia.

2.	REST APIs are designed around a **resources**.

3.	What is an identifer of a resource? Give an example.

> Identifer is a URI that uniquely identifies that resource.
> https://adventure-works.com/orders/1

4.	What are the most common HTTP verbs?
- GET, POST, PUT, PATCH, and DELETE.

5.	What should the URIs be based on?
> Should be based on nouns.

6.	Give an example of a good URI.
> https://adventure-works.com/orders/1

7.	What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- ‘Chatty’ web API expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires, so it’s a bad thing.

8.	What status code does a successful GET request return?

>200(OK)


9.	What status code does an unsuccessful GET request return?
>404( not found)

10.	What status code does a successful POST request return?
>Code 201 (Created)

11.	What status code does a successful DELETE request return?
>Code 204
