# Implementing Azure Container Apps

## Objective

In this lab, I learnt how to implement and deploy Azure Container Apps.

## Architecture diagram
![image](https://github.com/user-attachments/assets/26f95483-2276-4705-a998-3abb1ad32ad7)


### Job Skills

- Creating and configuring an Azure Container App and environment.
- Testing and verifying deployment of the Azure Container App.

### Tools Used

- Azure portal - https://portal.azure.com


## Steps

## Task 1: Create and configure an Azure Container App and environment

Azure Container Apps take the concept of a managed Kubernetes cluster a step further and manages the cluster environment as well as provides other managed services on top of the cluster. Unlike an Azure Kubernetes cluster, where you must still manage the cluster, an Azure Container Apps instance removes some of the complexity to setting up a Kubernetes cluster.

1.	From the Azure portal, search for and select Container Apps.
2.	From Container Apps, select Create.
![image](https://github.com/user-attachments/assets/40ec216e-e609-4e6e-84a9-318191b62f75)
 
3.	Use the following information to fill out the details on the Basics tab.*.
![image](https://github.com/user-attachments/assets/5a45d415-0598-4891-9c25-45bb7cb1ce65)
![image](https://github.com/user-attachments/assets/617a0bb4-87af-4661-b9bd-4606882066cd)
 
 
4.	On the Container tab, ensure that Use quickstart image is enabled and that the quickstart image is set to Simple hello world container.
![image](https://github.com/user-attachments/assets/bc152f06-5e8a-4cce-90b3-607526f7eee3)
 
5.	Select the Review and create and then Create.
![image](https://github.com/user-attachments/assets/d0c9285f-9a7f-4db5-975d-2c3d18ec0c78)
![image](https://github.com/user-attachments/assets/0138de77-6b29-48af-bac8-93099bb7b702)
 
 
## Task 2: Test and verify deployment of the Azure Container App

By default, the Azure container app that you create will accept traffic on port 80 using the sample Hello World application. Azure Container Apps will provide a DNS name for the application. Copy and navigate to this URL to ensure that the application is up and running.

1.	Select Go to resource to view your new container app.
2.	Select the link next to Application URL to view your application.
![image](https://github.com/user-attachments/assets/7c886e34-0d18-44b2-bb42-ff7bc09ea2b4)
 
3.	Verify you receive the Your Azure Container Apps app is live message.
![image](https://github.com/user-attachments/assets/c0251cb9-5c01-451e-86e9-307e3c55d4be)
 



