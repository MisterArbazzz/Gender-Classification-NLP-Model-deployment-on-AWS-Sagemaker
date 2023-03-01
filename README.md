# Gender-Classification-NLP-Model-deployment-on-AWS-Sagemaker

## Prerequisites

### AWS Account

In order to complete this workshop you'll need an AWS Account with access to create AWS IAM, S3, DynamoDB, Lambda, API Gateway, Comprehend, and Sagemaker. The code and instructions in this workshop assume only one student is using a given AWS account at a time. If you try sharing an account with another student, you'll run into naming conflicts for certain resources. You can work around these by appending a unique suffix to the resources that fail to create due to conflicts, but the instructions do not provide details on the changes required to make this work.

All of the resources you will launch as part of this workshop are eligible for the AWS free tier if your account is less than 12 months old. See the [AWS Free Tier page](https://aws.amazon.com/free/) for more details.

### Browser

We recommend you use the latest version of Chrome to complete this workshop.

## Modules

This workshop is broken up into multiple modules. You must complete each module before proceeding to the next. The first module has a slidedeck to understand the context, then second module explores the use of Amazon Comprehend, the next model helps you build a TensorFlow Model in Sagemaker, and in the last module we build the complete voice-of-the-customer application using a CloudFormation template. 

1. [NLP workshop Slides](Presentation-AWS-NLP-workshop.pptx) - 15 mins
2. [Creating a VOC application framework](1_VocFramework) - 15 mins
3. [Using Amazon Comprehend to add sentiment analysis](2_SentimentAnalysis) - 30 mins
4. [Create your own Gender classifier](3_GenderClassification) - 60 mins
5. [Create a summarizer](Coming soon)

## Cleanup
After you have completed the workshop, you can delete all of the resources using the following steps:
1. Delete all Cloudformation stacks created in all modules
2. Delete the Sagemaker deployment instance hoting the endpoint
3. Delete the Sagemaker notebook instance
