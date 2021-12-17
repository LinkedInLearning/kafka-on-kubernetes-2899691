# Deploying and Running Apache Kafka on Kubernetes
This is the repository for the LinkedIn Learning course Deploying and Running Apache Kafka on Kubernetes. The full course is available from [LinkedIn Learning][lil-course-url].

![Deploying and Running Apache Kafka on Kubernetes][lil-thumbnail-url] 

Apache Kafka has become the de-facto event-streaming platform, and its popularity is growing every year. Did you know that you can even deploy Kafka on a Kubernetes cluster? Whether you’re deploying Kafka yourself or using a tool or a managed service, there are a few key points to keep in mind. In this course, instructor Kate Stanley talks you through how to deploy Kafka on Kubernetes effectively.

Explore the platform's internals and concepts and learn more about the Kubernetes features that fit best with Kafka. Kate covers the Kafka configuration options that are essential to a successful, healthy deployment. She teaches you how to configure Kafka to make it accessible from outside the Kubernetes cluster. Examples are drawn from existing open-source projects, taking you step by step through the deployment process and giving you tips to make it easier along the way.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files, you must have the following installed:
	- Java version 8 or higher
        - [Apache Kafka](https://kafka.apache.org/downloads)
        - [Docker Desktop](https://www.docker.com/products/docker-desktop) with
Kubernetes enabled
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.


### Instructor

Kate Stanley 
                            


                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/kate-stanley).

[lil-course-url]: https://www.linkedin.com/learning/deploying-and-running-apache-kafka-on-kubernetes
[lil-thumbnail-url]: https://cdn.lynda.com/course/2899691/2899691-1639508803542-16x9.jpg




