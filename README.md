# SelfieLessActs

# Languages Used
1. Python
2. HTML/CSS
3. Javascript

# Introduction
SelfieLessActs is used to share information about anything that is good for the society that you observe.The entire application was built using Amazon Web Services.Examples of such acts could be:
● Picking up a piece of garbage and dumping it in a garbage can.
● Road getting laid in your area ● Someone helping a blind man cross the road. 
● You helping your mother at home in the kitchen.


The SelfieLessActs application will allow users of the application to upload image of the act with a small caption and categories. A user of the application will be presented with a screen that 
● Shows them lists of categories on which Acts have been shared. An act is a ombination of an image and a caption for that image. 
● Allows them to select to a topic. 
● On selection, they will be shown all Acts in a category sorted in reverse chronological order (latest image first). 
● Upvote a particular Act. 
● Upload an Act. 
● Delete an Act.


Cloud Orchestration is use of programming technology to manage the interconnection and interactions among workload on public and private cloud infrastructure. Implemented a custom container orchestrator engine that will:
● Be able to start and stop Acts containers programmatically, and allocate ports for them on localhost.
● Load balance all incoming HTTP requests (to the Acts EC2 instance) equally between all running Acts containers in a round-robin fashion.
● Monitor the health of each container through a health check API, and if a container is found to be unhealthy, stop the container and start a new one to replace it.
● Increase the number of Acts containers if the network load increases above a certain threshold.
