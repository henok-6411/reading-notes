[home page](https://henok-6411.github.io/reading-notes)
# Class 09 — API Server 

Describe a use-case where param middleware would come in handy.

* Parameters store as a url path when it send request , if we want to use that same url while it's making the request,then we use middleware param.

What are the two ways to add middleware in-between Mongoose and MongoDB interactions?

* toObject and toJSON. 

What is the difference between a join by reference and a virtual join?
* virtual join help up to use the collection value after we match by there unique Id. 

What do localField and foreignField mean?

* They both describe the field that we want to connect. Localfield is describing the local collection that we are running the query on but, foreignfield are the field that we want to join by in the foreign collection.
