# Desision Tree
- It is tree based classification algorithm which can be also used for regression purposes.

[//]: # (add the image of an example decision tree)

- the logic behind the decision tree can be easily understood because it shows a tree-like structure.

- the internal nodes of the tree represents the features of the dataset the branches represent the decision rule and the leaf node is representing the outcome/prediction

- In the decision tree there are two nodes
    1. decision node
    2. leaf node
    
- Note: a decision is a graphical representation for getting all the possible solution to a given problem based on a given condition.


- desicion trees usually mimic human like thinking ability while making a decision, so it is easy to understand.

## Decision tree terminologies

1. root node:
    - root node is from where the decision tree starts. 
    - it represents the entire dataset, which further gets divided into two or more homogeneous sets.

2. leaf node:
    - leaf nodes are the final output node, and the tree cannot be segregated further after getting a leaf node. 

3. spliting:
    - splitting is the process of dividing the decision node/root node into sub-nodes according to the given condisions.

4. branch/sub tree:
    - a tree formed by splitting the tree
    
5. pruning:
    - pruning is the process of removing the unwanted branches from the tree.
    
6. parent/child node:
    - the root node of the trees is called the parent node, and other nodes are called the child nodes.

CART: Classificiation and regression Tree


## How to select attributes smartly for a decision tree
- the main issue of selecting the best attributes for the node and sub-node.
- to solve such problems there is a technique which is called as **Attribute selection measure (ASM)**.

    a. Information gain:
    - information gain is the measure of entropy after the segementation of a dataset based on an attribute. 
    - it calculates how much information a feature provide us about a class.
    - according to the value of information gain, we split the node and build the decision tree.
    - a decision tree algorithm always tries to maximise the value of information gain and a node/attribute having the highest information gain is split first.
    - It can be calculated using the below formula:
    
    Information gain  = Entropy(S) - [(weight average)* entropy(each feature)]
    
    **entropy:**
    - it is a metric to measure the impurity in a given attribute.
    - it specifies randomness in data.
    - entropy can be calculated as follow:
    
    Entropy(s) = -P(yes)log_2 P(yes)- P(no)log_2 P(no)
    
    where, s = total number of samples
    p(yes) = probability of yes
    p(no) = probability of no
    
    
    
    b. gini index:
    - gini index is a measure of impurity or purity used while creating a decision tree in the CART (Classification and regression tree) algorithm.
    
    - 