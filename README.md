## PIZZAPROJECT

This project details the development and deployment of a static website for pizza ordering, leveraging Microsoft Azure's cloud services for hosting and scalability. The website offers users an intuitive interface to select from a variety of pizza options, customize their orders with various toppings, crust types, and sizes, and provide delivery information. Built using HTML, CSS, and JavaScript, the static site ensures fast loading times, responsive design, and a smooth user experience across devices. 

# Contributors:
- Dhiraj Bhosle. (dhirajbhosle (github.com))
- Mithilesh Vishwakarma. (47Mith (Mithilesh Vishwakarma) (github.com) )
- Aishwarya Ambre. (AishwaryaAmbre (github.com) )

Azure Bot Service is a managed service provided by Microsoft Azure for building, testing, and deploying intelligent chatbots. These bots can interact with users via various channels such as websites, mobile apps, and messaging platforms like Microsoft Teams, Slack, and Facebook Messenger.
Azure Alerts is a monitoring service that enables you to detect and respond to issues across your Azure resources. It provides real-time alerts based on metrics, logs, and performance thresholds.
Azure Storage Account provides a scalable and secure storage solution for a wide variety of data objects, including blobs, files, queues, and tables. It is designed to handle large amounts of unstructured data.
Azure Web App is a fully managed platform-as-a-service (PaaS) that enables you to build, deploy, and scale web applications and APIs quickly.
These Azure services collectively offer robust solutions for building, monitoring, and managing cloud-based applications and services, providing scalability, security, and ease of integration.

# System Requirements
# Hardware Requirements
- Development Machine:
  - Processor: Intel Core i5 or equivalent
  - RAM: 8 GB or higher
  - Storage: 256 GB SSD or higher
  - Display: 1080p resolution or higher
- User Devices:
  - Any device capable of running a modern web browser (desktop, laptop, tablet, smartphone)
Software Requirements
- Development Tools:
  - Code Editor: Visual Studio Code, Sublime Text, or any preferred code editor
  - Version Control: Git
  - Node.js and npm (for managing JavaScript dependencies and running build tools)
  - Browser: Latest version of Chrome, Firefox, Safari, or Edge for testing
- Hosting and Cloud Services:
  - Microsoft Azure:
    - Azure Static Web Apps for hosting the static site
    - Azure Blob Storage for storing and serving static content
    - Azure Functions for serverless backend operations
    - Azure Logic Apps for integrating with third-party services (e.g., payment gateways, SMS notifications)
    - Azure CDN for content delivery optimization
Performance Requirements
- Content Delivery : Use Azure CDN to ensure fast content delivery globally.
- Load Balancing : Utilize Azure's load balancing capabilities to manage traffic and maintain performance during peak times.
- Monitoring and Logging : Implement monitoring and logging using Azure Monitor and Azure Application Insights to track performance and identify issues.

# IMPLEMENTATION:
Implementation involves creating Chatbot, alert, storage account and web app for the website which we have created.
**Resource group**
 ![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/d39e0f43-1386-4bfe-b27d-627f7e029d4b)

**Resource visualizer**
 ![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/f7944ff8-5fb0-4412-9a8f-0802c61a56c0)

**Storage account**
![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/3737815f-4702-4ecd-af74-b17356e7bf73)
#
![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/09a55765-2f6b-454a-b2cd-1b2101a2e184)


**Azure storage container**
![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/b95ea59c-8180-42cd-982f-92f000b322e0)

**$web container contains all the necessary content related to the website.**
 ![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/9ef5877d-0d03-423b-80f4-c931ea036dbf)
#
  **Alerts**
  
![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/5ac57d6a-ff9b-4fe9-b037-d133a91a4208)

![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/ed56e843-de88-4ff2-b8bb-467152c68458)
 
**Alert is sent when more than 10 users visit the site.**
 ![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/d8a0599e-42fd-4f07-85e1-e273e0cd0cca)
 
 **Chatbot**
 
![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/f4c0682f-dcfd-4a6a-98f6-0ef60bdb98bd)

![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/17f2f38d-45c3-437a-a282-b38526e8d1cf)

# WEB OVERVIEW
**Homepage**
![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/d12d04d5-b625-4143-bc27-486344c786b9)

![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/799c82e0-6755-434f-a577-ded151fdbc07)

![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/dba32a0b-089d-4f9a-87ba-a34db54a073d)

**About us**

 ![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/1f32bff6-0e73-4def-b150-e5abfa2be3be)

 ![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/67c95f26-f102-4956-b81e-f82db3fbb4ca)

**Chatbot**

 ![image](https://github.com/DBhosle/Pizzaproject/assets/166639726/303cd3cf-9d0e-427f-9935-1116550c8cd9)

# How to use the Project:
1.	User is required to visit the Microsoft azure portal(https://portal.azure.com)
2.	Azure account ID- dhiraj201804@mccmulund.ac.in
3.	If needed you can switch directory
4.	Followed by user is required to  enable the alerts , and start the AI service that is chatbot.
5.	Start the website by clicking 
https://pizzaproject.z13.web.core.windows.net/
or
https://pizzaproject-secondary.z13.web.core.windows.net/

6.	The user can visit the azure account and still open the website by going into storage account -> static website-> links  
7.	User and can navigate on the website.

•	URL of Documentation (PDF file):
https://drive.google.com/file/d/1Nsx7u59KWwVO_6OwaodFHkF6qHxIU6ki/view?usp=sharing 
•	URL of Documentation (WORD file): 
https://docs.google.com/document/d/1cxfKm-RC-ih0iSq-VLFzNgUo2DJ2XiP3/edit?usp=sharing&ouid=118107359696225724444&rtpof=true&sd=true 
•	URL of Video of the project :
https://drive.google.com/file/d/1RqFiOS24UKRGqz6gLnlle8i7B3w3mAb0/view?usp=sharing


For more information about the project please refer the PDF file attached.

