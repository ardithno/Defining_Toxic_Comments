# Defining Toxic Comments

## ***Introduction***

### *Project Description:*
The Wikishop online store is launching a new service. Now users can edit and supplement product descriptions, like in wiki communities. That is, customers offer their edits and comment on others' changes. The store needs a tool that will search for toxic comments and send them for moderation.

### *Project Goal:*
Train a model to classify comments into positive and negative. Build a model with an F1 quality metric value of at least 0.75.

### *Data Description:*
  Data in the toxic_comments.csv table:
  
    text - comment text
    num_orders - target feature

### *Work Plan:*
1. Data Preparation:
- Data Unloading
- Data Sampling
- Token Creation
- Embeddings
- Sample and Pipeline Creation
2. Model Training
3. General Conclusions
