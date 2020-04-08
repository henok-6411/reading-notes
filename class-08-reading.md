[homePage](https://henok-6411.github.io/reading-notes)

# Class 08 — Express Routing & Connected API

What is a benefit to using express.Router()?
* Is a class which help us to create route handler and also can be extended to create validater handler. 

When I say that top-down order matters in Express, what does that mean?
* top-down order is like object oriented approach, we classified it one problem or task in to different pieces from top to bottom because of they are refer to one problem. when we solve the problem we have to follow the order of there place. 

Why do we use a model class (with create(), read(), etc.) instead of directly calling MongoDB operations (such as save(), find(), etc.) within our Express route handlers?

* We want to use middleware before we actually using our main mongoDB . 
