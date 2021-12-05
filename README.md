# Earthquake-Entity-Typing-Dataset
Named Entity Typing dataset on earthquake news article. This dataset contents hundreds of task-unrelated entities 

### Use Guide ###

This is our self-collected dataset for the named entity typing on the earthquake news articles. Our concerned entities include the earthquake happening location, magnitude, and casualty (death and injure).
We totally collect 351 articles of 41 earthquake events for the named entity typing with task-unrelated entities (label with "None").
This dataset is presented as csv files. The meaning of each column is shown below:

Event Key Words | Event Happening Date | News Publish Date | News Title | Contents of News Article | Entity Information (Label)

Entity Information records all the entities in this article. Each row in this slot represents one entity.
Each row is structured below:

Entity texts | Start index, End index in the sentence | Located sentence index | Coarse Entity Type | Fine-grained Entity Type

In this dataset, there are five fine-grained entity types.

  death:  death number (earthquake casualty)/
    mag:  earthquake magnitude/
    loc:  earthquake happening location/
 injure:  injure number (earthquake casualty)/
   None:  task-unrelated entities
