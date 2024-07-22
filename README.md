# Building a Cloud-Native Monitoring Application with HTML, Python Flask & Psutil Library and deploying it using Docker And AWS Kubernetes
## Introduction:
In the fast-evolving realm of cloud-native monitoring applications play a pivotal role in ensuring system performance, resource utilization, and reliability. This project delves into the development of a cloud-native monitoring application utilizing HTML, Python Flask, Docker, AWS Kubernetes, and the Psutil library. By harnessing these technologies, we aim to construct a scalable and efficient solution for monitoring system resources within cloud environments.

### My Technology Stack
Here are the technologies I used in this project:

<div style="display: flex; flex-direction: row;">
<img src="Images/icons8-docker-logo-144.png" width="75" height="75" style="margin-right: 15px;">
<img src="Images/icons8-kubernetes-144.png" width="75" height="75" style="margin-right: 15px;">
<img src="Images/icons8-aws-logo-144.png" width="75" height="75" style="margin-right: 15px;">
<img src="Images/icons8-flask-100.png" width="75" height="75" style="margin-right: 15px;">
<img src="Images/icons8-python-144.png" width="75" height="75" style="margin-right: 15px;">
<img src="Images/icons8-html-logo-144.png" width="75" height="75" style="margin-right: 15px;">
</div>

- **Defining Requirements:**
Prior to delving into implementation details, it's crucial to delineate the prerequisites of our monitoring application. This encompasses monitoring various system metrics such as CPU usage, memory utilization, disk I/O, and network traffic. Additionally, we aspire to fashion a user-friendly web interface for real-time visualization of these metrics.

- **Backend Development with Python Flask:**
Our journey commences with the construction of the backend using Python Flask. Flask offers a lightweight and adaptable framework for crafting web applications. Through Flask routes, we define endpoints for retrieving system metrics. By integrating the Psutil library, we can efficiently gather system-level information, including CPU, memory, and disk usage.

- **Frontend Design with HTML:**
Simultaneously, we craft the frontend of our monitoring application using HTML. HTML provides the foundation for the structure and layout of our web interface. We devise interactive components such as charts, graphs, and tables to effectively visualize system metrics. Additionally, JavaScript can be incorporated for dynamic updates and enhanced user interactivity if warranted.

- **Containerization with Docker:**
To ensure portability and consistency across diverse environments, we containerize our application utilizing Docker. Docker facilitates the encapsulation of our application and its dependencies into lightweight containers. We formulate a Dockerfile delineating the environment and dependencies necessary for executing our Flask application. This simplifies deployment and scalability across cloud environments.

- **Deployment on AWS Kubernetes:**
For deploying our containerized application at scale, we leverage AWS Kubernetes (Amazon Elastic Kubernetes Service - EKS). Kubernetes automates container orchestration, scaling, and management. We deploy our Docker containers as pods within a Kubernetes cluster, ensuring high availability and fault tolerance. Kubernetes also facilitates seamless scaling in response to demand fluctuations, optimizing resource utilization.

- **Integration of Monitoring and Logging:**
In addition to monitoring system resources, we integrate monitoring and logging solutions to track the health and performance of our application. Kubernetes-native monitoring tools like Prometheus and Grafana can be employed for collecting and visualizing metrics. Furthermore, logging frameworks such as Fluentd or Elasticsearch capture application logs for troubleshooting and analysis.


Constructing a cloud-native monitoring application employing HTML, Python Flask, Docker, AWS Kubernetes, and the Psutil library furnishes a resilient and scalable solution for monitoring system resources within cloud environments. By leveraging containerization, orchestration, and automation technologies, we can devise a robust monitoring solution that aligns with the demands of contemporary cloud-native architectures.

### Output Images
Here are some Output images of this project:

<div style="display: flex; flex-direction: row;">
<img src="Images/Output/Output -1.jpg" width="500" style="margin-right: 50; margin-bottom: 50;">
<img src="Images/Output/Output -2.jpg" width="500" style="margin-right: 50; margin-bottom: 50;">
</div>
