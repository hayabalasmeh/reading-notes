# Welcome to My Thirteenth reading notes for class13 in 301 level.
## Our First topic is **Status Codes Based On REST Methods**


![status code](https://geekflare.com/wp-content/uploads/2015/02/http-status-return.png)


## 1.	In your own words, describe what each group of status code represents:
•	100’s = 
>These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. 

•	200’s = 
>They tell the client that its request was accepted.

•	300’s =
 >They tell the client that the resource they are requesting isn’t available at the expected location anymore.

•	400’s = 
>They are all about invalid requests a client sent to a server.

•	500’s = 
> Often they indicate problems with overwhelmed servers or unreachable servers behind proxies,

## 2.	What is a status code 202?
>  If the deletion is asynchronous this code will return with with some information or URL to tell the client when it will be deleted.

## 3.	What is a status code 308?
>Permanent Redirect - This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future.


## 4.	What code would you use if an update didn’t return data to a client?
> 204 No Content 

## 5.	What code would you use if a resource used to exist but no longer does?
> 410 Gone 

## 6.	What is the ‘Forbidden’ status code?
> The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
