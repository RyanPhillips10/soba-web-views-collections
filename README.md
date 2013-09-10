# SoBA Web Curriculum

### Lesson 7: Backbone / Parse Views and Collections


#### Overview

For this lesson you will rebuild your assignment from lesson 6 to use the collections and views that Parse provides by way of its Backbone suppprt.

Refer to both the [Parse JavaScript guide](http://backbonejs.org/) and the [Backbone documentation](https://www.parse.com/docs/js_guide). Although there are a few terminological differences and some implementation differences, Parse implements most of the model, view, event and collection functionality of backbone.js the same.

#### Instructions

Again, make sure you fork this repository to your own account and clone it like you did for the first two assignment.

Keep up the habit of branching in git, making your changes, and then merging back into your main branch. As in Assignment 4, instead of branching from main, create a "development" branch first immediately after you clone the repository, and branch from this line when you edit the individual files.

#### Editing the files

For this lesson you will only be editing index.html. You should create it from scratch following the model index.html file provided in assignment 6.

#### The Details

Specifically, you should update assignment 6's application so that:

1. You are using a collection to manage access to your model data
 
2. You are using multiple views, one each for the object list, for updating an object, and for the application which manages interaction between the two (namely, selection)

When you finish, almost all of your application logic should be inside the global app variable, and you should only need one line of code to get your application going.

Once again, I have included an example.html file with the contents of today's lecture. Refer to it as the basis for your assignment. But do not simply copy and paste, and do not simply use functions you do not understand. If you see a function that you do not understand, look it up! Everything we use is part of jQuery, underscore.js, backbone.js or Parse.

#### Advanced [required]	

Extend the functionality so that when you create a new object it is automatically selected in the list and the update view for it is immediately shown. Fix it so that if you delete the currently selected element, the update area is removed.

