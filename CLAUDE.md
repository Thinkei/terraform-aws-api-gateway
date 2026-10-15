# terraform-aws-api-gateway

## Purpose

Terraform module for AWS API Gateway — reusable module for creating and managing API Gateway resources.

## Stack

- Terraform
- AWS API Gateway

## Repo Structure

```
main.tf        # Main module resources
variables.tf   # Input variables
outputs.tf     # Output values
versions.tf    # Provider version constraints
context.tf     # Atmos context variables
modules/       # Sub-modules
examples/      # Usage examples
test/          # Module tests
atmos.yaml     # Atmos configuration
```

## Common Commands

```bash
terraform init     # Initialise module
terraform plan     # Plan changes
terraform apply    # Apply changes
```

## Architecture Constraints

- Semver tagging required for module releases — consumers pin to a version
- Examples in `examples/` must be kept working and up-to-date
