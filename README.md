# DATA VERSION CONTROL(DVC) IN ML
Machine Learning development involves comparing models and storing the artifacts they produced. We often compare several algorithms to select the most efficient ones. We assess different hyper-parameters to fine-tune the model. Git helps us store multiple versions of our code. Additionally, we need to keep track of the datasets we are using. This is important not only for audit purposes but also for assessing the performances of the models, developed at a later time. Git is a standard code versioning tool in software development. It can be used to store your datasets but it does not offer an optimal solution.

An alternative solution is to use Data Version Control (DVC). Despite its name, it is not just a data versioning tool, but also enables model and pipeline tracking. It runs on top of Git, which makes it easy to learn for Git users. At the same time, it overcomes the limitations of storing big files by storing them remotely (e.g. Azure, S3) and keeping in Git only their metadata.