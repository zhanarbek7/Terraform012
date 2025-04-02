# Terraform012

1. terraform init
Initializes the project, tells everything about your project to Terraform

2. terraform plan
Generates execution plan, like commit, what is ready to be applied

3. terraform apply
first confirms the plan, deploys our planned resources

4. terraform destroy
first confirms the plan, destroys our deployed resources

5. Terraform state?
Stores data about:
* current terraform version and metadata
* resources creates in a list

6. Terraform main.tf files
In Terraform, main.tf is the primary configuration file where you define your infrastructure resources. 
It typically contains:
* Provider Configuration (e.g., AWS, Azure, GCP)
* Resource Definitions (EC2, S3, VPC, etc.)
* Variables and Outputs
* Modules and Dependencies

7. Terraform variables

8. 