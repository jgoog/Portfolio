# Voice-Controlled Task Manager

## Overview
The Voice-Controlled Task Manager is an innovative application that leverages Amazon Alexa to manage tasks through voice commands. This project utilizes various AWS services, including AWS Lambda and SNS, to handle backend processing and ensure seamless interaction between the user and the application.

## Users
- **General Users**: Anyone who wants to manage tasks hands-free using voice commands.
- **Busy Professionals**: Individuals who need to manage tasks efficiently without interrupting their workflow.
- **Accessibility Users**: Users with disabilities who benefit from voice-controlled applications.

## Job it Performs
The Voice-Controlled Task Manager allows users to:
- **Add Tasks**: Add tasks to their list using voice commands.
- **View Tasks**: Retrieve and listen to their current task list.
- **Complete Tasks**: Mark tasks as complete using voice commands.
- **Set Reminders**: Set reminders for tasks at specified times.

## Inspiration
The inspiration for this project came from the need for hands-free task management. With the increasing use of voice assistants in daily life, integrating task management with Amazon Alexa provides a convenient and efficient way for users to manage their tasks without manual input.

## Key Features
- **Add Tasks**: Add tasks to your list using voice commands.
- **View Tasks**: Retrieve and listen to your current task list.
- **Complete Tasks**: Mark tasks as complete.
- **Set Reminders**: Set reminders for tasks at specified times.

**Interaction Model**: 
![image](https://github.com/user-attachments/assets/c8753f57-291f-4436-bc92-a2146a614acc)

**Alexa Recorded chat log**:
![image](https://github.com/user-attachments/assets/49fbdb21-8876-4e09-9d3b-039cc68ac4d2)


## Architecture
The system architecture includes the following components:
- **Amazon Alexa**: Captures voice commands and triggers the appropriate intents.
- **AWS Lambda**: Processes intents and executes backend logic.
- **AWS SNS**: (Future implementation) Sends reminders to users.
- **AWS SAM**: Used for deploying and managing serverless resources.

## Technologies
- **Voice Assistant**: Amazon Alexa
- **Backend Processing**: AWS Lambda
- **Notifications**: AWS SNS (future implementation)
- **Serverless Management**: AWS SAM

## Dependencies
- **Alexa Skills Kit SDK** Version X.X
- **AWS SDK**
- **AWS SAM**

## Deployment Tools
- **AWS SAM**: Used for deploying and managing serverless resources

## Competencies

### JF 4.3
- Is able to build, manage and deploy code into the relevant environment.
- **Situation**: For the Voice-Controlled Task Manager project, I was responsible for building and deploying the AWS Lambda functions and configuring the Alexa Skills Kit.
- **Actions**: 
  - **Build**: Developed AWS Lambda functions to handle various intents from Alexa.
  - **Manage**: Managed the deployment of these functions using AWS SAM.
  - **Deploy**: Deployed the application to AWS, ensuring seamless integration with Alexa and other AWS services.
- **Results**: The automated deployment process using AWS SAM ensured that the Lambda functions were consistently and reliably deployed, providing a robust backend for the voice-controlled application.
- **Connection to Project**: Proper deployment and management of the backend services were crucial for the successful operation of the Voice-Controlled Task Manager.

### JF 6.3
- Able to communicate software solutions and ideas to technical and non-technical stakeholders.
- **Situation**: During the development of the Voice-Controlled Task Manager, it was necessary to communicate the project's progress and technical details to various stakeholders.
- **Actions**: 
  - **Documentation**: Created detailed documentation explaining the architecture, features, and deployment process of the application.
  - **Presentations**: Conducted presentations to explain the project to non-technical stakeholders, ensuring they understood the benefits and functionality.
  - **Collaboration**: Worked closely with team members to ensure clear communication and understanding of project goals and tasks.
- **Results**: Effective communication ensured that all stakeholders were well-informed about the project's progress and technical aspects, facilitating better collaboration and support.
- **Connection to Project**: Clear and effective communication was essential for aligning the project's goals with stakeholder expectations and ensuring successful development and deployment.
