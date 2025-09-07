So, in the part 1 we saw how to load the documents 
Now , in this part we will see -> how to convert the documents into chunks of texts 

Again , in langchain we have lots of ways to do this 

WHY DO WE DO THIS ?
Every LLM model has a limitation of the context size, in order to take care of that we have to divide this doc into smaller text chunks.

In order to use difffernt types of text splitters we require this library -> langchain-text-splitters
