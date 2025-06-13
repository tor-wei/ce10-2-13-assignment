# ce10-2-13-assignment
Assignment 2.13

Make a comparison between Serverless Framework and Terraform as tools for IaC by answering:

1. What type of infrastructure and application deployments are each tool best suited for?

Serverless Framework focuses on building and deploying serverless applications while Terraform is a general purpose tool that handles cloud infrastructure.


2. How do their primary objectives differ?

Serverless Framework is more for developers working on code to deploy while Terraform is more for DevOp Engineers setting up and maintaining cloud infrastructure.


3. How do they differ in terms of learning curve and ease of use for developers or DevOps teams?

Serverless Framework abstracts the underlying complexities so developers can focus on writing the codes to deploy while Terraform can be more challenging for developers who aren't experienced with cloud infrastructure.


4. What are the differences in how each tool handles state tracking and deployment changes?

Serverless Framework uses AWS S3 to store the state of services and deployment artifacts.

Terraform creates a local state file which can also be stored remotely, e.g. Terraform Cloud or AWS S3 bucket.


5. In what scenarios would you recommend using Serverless Framework over Terraform, and vice versa?

Use Serverless Freamework when deploying serverless applications and use Terraform for other aspects of the cloud infrastructure.


6. Are there scenarios where using both together might be beneficial?

We can use Serverless Framework to deploy Lambda functions and API Gateway after using Terraform to provision the infrastructure.
