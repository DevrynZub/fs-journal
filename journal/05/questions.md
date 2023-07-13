# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?
  C - Create
  R - Read
  U - Update
  D - Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  >   C - Create - POST
  R - Read - Get 
  U - Update - Put
  D - Delete - Delete 

  these are how the crud method correlates to HTTP

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > ORM stands for Object-Relational Mapping. It is the middle man between javascript and MongoDB, this wold be used in a 1 to 1 relationship. 

04. Which two `HTTP` request types include a body?

  > post and push

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > In a synchronous coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise, in an asynchronous coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.

06. What are the three types of data relationships? Provide an example of each.

  > One to One, an example of 1:1 would be something like author to address.  One to Many and an example of that would be: a blog with comments, anf finally many to Many, and a good example of this would be an author who wrote multiple books. 

07. What is middleware?

  > middleware can be defined as, a framework or application that allows updates through your database that typically works with the response/request side of the database

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > The request pipeline delivers information from the client while the response pipeline returns it.

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > http://example.com/path/to/resource?tag=winter

10. What is a ***virtual property***?

  > Virtual property are additional fields for whatever the model is you are working on, for example first and last name, but these do not persist through the database. 
