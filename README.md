# terraform-module-november-2024

## Copy and paste following block

```hcl
module "november-2024" {
  source  = "nazikmusa/november-2024/module"
  version = "3.0.0"
  region = "us-east-1"     # Replace with your values
  vpc_cidr = "10.0.0.0/16"  # Replace with your values
  subnet_cidr = "10.0.1.0/24"  # Replace with your values
  igw_name = "Kaizen"   # Replace with your values
}
```