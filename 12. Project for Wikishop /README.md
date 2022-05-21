# Yandex-Practicum

**Project - For Wikishop**

Online store "Wikishop" launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. That is, clients propose their edits and comment on the changes of others. The store needs a tool that will look for toxic comments and submit them for moderation.

Let's train the model to classify comments into positive and negative. We have at our disposal a dataset with markup on the toxicity of edits.

Let's build a model with the value of the accuracy metric F1 score not less than 0.75.

**Data Description**

The data is in the /datasets/toxic_comments.csv file.

The text column in it contains the text of the comment, and toxic is the target feature.