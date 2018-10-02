# Feature Extraction Pipelines

Feature selection is one of the toughest parts of machine learning -- oftentimes we're working in extremely high-dimensional space (as in the case of working with text data), and it's very difficult to identify and extract the features that will be most informative to a predictive model.

Grid search techniques can help us to find the best combination of features, but in a software engineering context, we also need a robust and repeatable means of integrating normalization, transformation, vectorization, feature union, and modeling into a single process -- thankfully the Scikit-Learn `Pipeline` object gives us just that!

# Classifying News Articles using a Feature Extraction Pipeline
The accompanying code comes straight from the [Scikit-Learn documentation](http://scikit-learn.org/stable/auto_examples/model_selection/grid_search_text_feature_extraction.html), and gives a good procedural illustration of how you can use pipelines for feature extraction on a text data classification problem.  

# Challenge
But... what if we wanted to put something like this into production?

## Step one
First, think about what would be necessary to support a real-world news classification application. For instance, how would real live news data likely flow in and out of a live application -- what is the input likely to be? What should the output look like? What are the major objects that will exist within the application, and what is their behavior? Sketch out a rough design of an architecture based on your ideas (feel free to use a whiteboard, paper, Google draw, or whatever you prefer).

## Step two
Once you have some ideas about how to productionize the code, take a crack at refactoring the [grid_search_text_feature_extraction.py](grid_search_text_feature_extraction.py) script using an object-oriented approach, (classes, methods, encapsulation, control routines) that leverages `Pipelines` to do normalization, vectorization, and classification, and output an interpretable result.

## Show and tell
Send us your updated code and a snapshot of your architectural design so we can see what you came up with!

Please feel free to send us a link to a Github repository that will contain your solution.  We are fairly flexible for what language you write this in so feel free to include a response in any of the following languages or what ever language you are most comfortable in:
* Java
* JavaScript
* Go
* Kotlin
* Scala
* Python

When thinking abut how to structure your solution think about how you would typically would work with teams and the common concerns that you may have when sharing code with others.

### Questions

#### How am I evaluated?
* As with all ByteCubed Challenges, we are more concerned about how you went about solving and thinking about the problem than anything else.  We use this as a data point within our interview process and it is meant to help drive the conversation.
