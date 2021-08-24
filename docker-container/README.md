# Learn Terraform Docker Container
Use terraform to provision and deploy NGINX to docker

## Steps
```
# Initialize the project, which downloads a plugin that allows Terraform to interact with Docker.
terraform init

# Provision the NGINX server container with apply. When Terraform asks you to confirm type yes and press ENTER.
terraform apply

# Verify existance of NGINX by visiting localhost:8000 or running docker ps
docker ps

# Stop container
terraform destroy
```