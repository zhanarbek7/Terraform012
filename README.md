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

8. Terraform modules
Terraform modules are reusable packages of configurations that simplify complex setups, promote reusability, and enable sharing within teams. They typically include `main.tf` for resources, `variables.tf` for inputs, and `outputs.tf` for outputs.
We can import to modules other main.tfs and reuse the code from there.

9. Terraform errors

10. Terraform value imported from other terraform file in the 
same directory
1) feature_switch run terraform init
2) run terraform plan -var-file="test.tfvars"
this command injects values from the test.tfvars, where it 
overrides the existing values