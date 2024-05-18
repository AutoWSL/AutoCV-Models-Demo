
# AutoCV-Models-Demo

This project is a demonstration of deploying Computer Vision models using Django on AWS EC2 led by AutoWSL. The repository is aimed at sharing an experience of deploying ML models on a Django web application hosted on AWS EC2 instances.

In this demonstration, we're not necessarily concerned about creating a highly secure, full-fledged website. Instead, the primary focus is on demonstrating the steps involved in deploying ML models. Several parts of the project might disregard advanced security features and web development standards.

Please remember to follow the AWS guidelines while deploying on an EC2 instance, such as ensuring proper choice of instance, setup, and following appropriate security policy.

## Tutorial Layout

- Local/dev side
  - ML models side
  - Django framework side
  
- Server side
  - Website settings
  - Remote server setup/Apache configuration
  - Remote instance (EC2) choice


Refer to the in-depth README on GitHub for project setup, further steps, and added insights. This includes URLs for running the project locally, an analysis of how Django works to connect backend and front end, base HTML setup with bootstrap and more. Moreover, outlining Django framework, backend and frontend setup, deployment procedure, requirements, and EC2 Instance setup.

This demo displays three computer vision tasks. In each one, the web application requests to load an image and then outputs the corresponding result. The tasks demonstrated include Classification, Semantic Segmentation, and Object Detection.