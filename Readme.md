# Terraform Docker Tutorial

This project demonstrates how to use Terraform to provision a Docker container locally using the Docker provider.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/JAYPORWAL/terraform-docker-tutorial.git
cd terraform-docker-tutorial
````

### 2. Initialize Terraform

```bash
terraform init
```

### 3. Review the Execution Plan

```bash
terraform plan
```

### 4. Apply the Configuration

```bash
terraform apply
```

> Confirm when prompted with `yes`.

### ✅ Verify the Container

Check your Docker environment — you should see a running container (e.g., Nginx on port 8080).

### 5. Destroy the Infrastructure

```bash
terraform destroy
```

> Confirm with `yes` to clean up resources.

---

## 📁 Files

* `main.tf` – Terraform configuration to create a Docker container
* `.terraform.lock.hcl` – Auto-generated provider version lock file
* `terraform.tfstate` – Terraform state file (after running apply)

---

## 🛠 Prerequisites

* [Docker](https://docs.docker.com/get-docker/)
* [Terraform](https://developer.hashicorp.com/terraform/downloads)

---

## 📌 Note

This example uses the [Kreuzwerker Docker provider](https://registry.terraform.io/providers/kreuzwerker/docker/latest) to manage Docker resources locally.

```
