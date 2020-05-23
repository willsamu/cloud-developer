The endpoint for the running elastic beanstalk deployment can be found at

image-filter-udacity-prod.eu-central-1.elasticbeanstalk.com

A postman (test-) configuration file is located at the root of the project.

Valid requests are accepted, processed and the result is returned. Invalid requests are handled (such as image source urls returning a 404 status code - including the one from the project rubric).


I encountered one major problem during deployment to the cloud:

Using the provided aws starter account, i could not create an IAM user with the necessary privileges to initiate, create and/or deploy to ebs.

I therefore had to use another aws account and provide my credit card, is it possible to transfer the credits from the starter account to the one i am using now?

Would greatly appreciate some help on that topic!