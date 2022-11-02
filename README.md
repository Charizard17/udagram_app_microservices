# Udagram Image Filtering Application

Udagram is a simple cloud application developed alongside the Udacity Cloud Developer Nanodegree.

It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

### 1. Database - AWS RDS

AWS RDS is used to store the application's metadata.

### 2. S3

The S3 bucket is used to store images that are displayed in Udagram.

### 3. AWS EKS

Amazon Elastic Kubernetes Service is used to orchestration and managing containers.

### 4. Services - Frontend Service

Frontend of this application is build with Ionic. Checkout services/frontend-service folder. You can run following commands to start the app locally:

npm install .
npm install -g ionic
ionic build
ionic serve

### 5. Services - Feed Service

This service is one of the backend services. It manages user feeds. Checkout services/feed-service folder. You can run following commands to start the app locally:

npm install .
npm run dev

### 6. Services - User Service

This service is one of the backend services. It manages user feeds. Checkout services/user-service folder. You can run following commands to start the app locally:

npm install .
npm run dev

### 7. Services - Reverseproxy Service

This service manages the backend servers. Checkout services/reverseproxy-service folder.
