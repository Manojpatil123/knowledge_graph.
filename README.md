What is a Knowledge Graph?

Let’s get one thing out of the way – we will see the term “graphs” a lot in this article. We do not mean bar charts, pie charts, and line plots when I say graphs. Here, we are talking about interconnected entities which can be people, locations, organizations, or even an event.

![Alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/10/graph_not_plots.png)


We can define a graph as a set of nodes and edges.

Take a look at the figure below:

![Alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/10/graph_link.png)



Node A and Node B here are two different entities. These nodes are connected by an edge that represents the relationship between the two nodes. Now, this is the smallest knowledge graph we can build – it is also known as a triple.

Knowledge Graph’s come in a variety of shapes and sizes. For example, the knowledge graph of Wikidata had 59,910,568 nodes by October 2019.

 

How to Represent Knowledge in a Graph?
Before we get started with building Knowledge Graphs, it is important to understand how information or knowledge is embedded in these graphs.

Let me explain this using an example. If Node A = Putin and Node B = Russia, then it is quite likely that the edge would be “president of”
![Alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/10/putin_1.png)

A node or an entity can have multiple relations as well. Putin is not only the President of Russia, he also worked for the Soviet Union’s security agency, KGB. But how do we incorporate this new information about Putin in the knowledge graph above?

It’s actually pretty simple. Just add one more node for the new entity, KGB:

![Alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/10/KGB.png)

The new relationships can emerge not only from the first node but from any node in a knowledge graph as shown below:

![Alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/10/APEC.png)

Russia is a member of the Asia Pacific Economic Cooperation (APEC).

Identifying the entities and the relation between them is not a difficult task for us. However, manually building a knowledge graph is not scalable. Nobody is going to go through thousands of documents and extract all the entities and the relations between them!

That’s why machines are more suitable to perform this task as going through even hundreds or thousands of documents is child’s play for them. But then there is another challenge – machines do not understand natural language. This is where Natural Language Processing (NLP) comes into the picture.

To build a knowledge graph from the text, it is important to make our machine understand natural language. This can be done by using NLP techniques such as sentence segmentation, dependency parsing, parts of speech tagging, and entity recognition. Let’s discuss these in a bit more detail.
