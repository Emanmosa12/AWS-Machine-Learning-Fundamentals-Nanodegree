# Build a ML Workflow for Scones Unlimited on Amazon SageMaker

An end-to-end machine learning workflow project completed as part of the **Machine Learning Fundamentals Nanodegree by Udacity, sponsored by AWS**.

## Project Overview

This project uses **Amazon SageMaker** to build an image classification workflow capable of distinguishing between **bicycles and motorcycles**.

The trained model is deployed for inference and integrated with **AWS Lambda** and **AWS Step Functions** to create an event-driven machine learning application.

The project demonstrates how machine learning components can be combined into a production-oriented workflow.

## Workflow

The project consists of the following stages:

1. **Data Staging**
   - Prepare and stage image data for model training.

2. **Model Training and Deployment**
   - Train an image classification model using Amazon SageMaker.
   - Deploy the trained model for inference.

3. **AWS Lambda Functions**
   - Build supporting Lambda functions for data processing and model inference.
   - Validate inference results against a confidence threshold.

4. **AWS Step Functions**
   - Connect the Lambda functions and model endpoint into an event-driven workflow.
   - Control the workflow based on inference results.

5. **Testing and Evaluation**
   - Test the complete workflow.
   - Evaluate successful and unsuccessful inference paths.

6. **Cloud Resource Cleanup**
   - Clean up deployed resources after completing the project to avoid unnecessary cloud costs.

## Architecture

```text
Image Input
    │
    ▼
AWS Lambda
    │
    ▼
SageMaker Model Endpoint
    │
    ▼
Inference Result
    │
    ▼
Confidence Threshold
    │
    ├── Meets Threshold ──► Continue Workflow
    │
    └── Below Threshold ─► Validation / Failure Path
