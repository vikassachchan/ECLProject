# Elastic Beanstalk Application Deployment

This repository contains CloudFormation templates and application files to deploy a simple web application to AWS Elastic Beanstalk.

## Prerequisites

Before deploying the application, ensure you have the following prerequisites:

- An AWS account with appropriate permissions to create resources.
- AWS CLI configured on your local machine.
- Basic knowledge of AWS services like Elastic Beanstalk, EC2, and CloudFormation.

## Deployment Steps

Follow these steps to deploy the application:

1. Clone this repository to your local machine:

2. Navigate to the repository directory:


3. Update the CloudFormation parameters file (`parameters.json`) with your desired values.

4. Deploy the CloudFormation stack using the AWS CLI:

5. Wait for the CloudFormation stack creation to complete.

6. Once the stack creation is successful, you can access the deployed application using the Elastic Beanstalk environment URL.

## Cleanup

To avoid incurring unnecessary costs, make sure to delete the CloudFormation stack after you've finished testing or using the application. You can delete the stack using the AWS CLI:

## Additional Information

For more information about Elastic Beanstalk and AWS CloudFormation, refer to the following resources:

- [AWS Elastic Beanstalk Documentation](https://docs.aws.amazon.com/elasticbeanstalk/)
- [AWS CloudFormation Documentation](https://docs.aws.amazon.com/cloudformation/)

