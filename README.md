# COMP-3020 Final Project - Branch Asset Management System

## About the Project

This is my final project for COMP-3020 Cloud Infrastructure

For this project, I will be creating a Branch Asset Management System for Yarrow-Mullein Bank using AWS.

The purpose of the application is to help bank staff keep track of equipment at different branches, such as computers, printers, and ATMs.

## Project Features

The application will allow staff to:

- Register and log in.
- Add new equipment.
- View a list of equipment.
- Update equipment information.
- Track maintenance status.
- Mark equipment as retired.
- View a basic inventory summary.

## AWS Services

I will be using the following AWS services:

- AWS Amplify - To host the website.
- API Gateway - To connect the website to Lambda.
- AWS Lambda - To handle the backend functions.
- DynamoDB - To store equipment information.
- Amazon Cognito - For user registration and login.
- AWS SAM - To deploy the AWS resources.
- AWS IAM - To manage permissions.
- Amazon CloudWatch - To check logs and errors.

## Database

I will be using one DynamoDB table called `Assets`.

Each asset will have a unique `assetId` and store information such as the asset name, type, branch, purchase date, status, and maintenance notes.

## Project Status

I am currently working on Milestone 1, which includes planning the project, identifying the requirements, designing the AWS architecture, and setting up the GitHub repository.

The application will be built and tested in the next stages of the project.