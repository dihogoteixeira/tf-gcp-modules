Módulo para gerenciamento de instâncias para Google Cloud Platform
---

Example usage:

***main.tf***
```go
module "group-web" {
  source = "git@github.com:dihogoteixeira/tf-gcp-modules.git?ref=v1.0"

  amount = 3
  name   = "linux-web"
  image  = "centos-cloud/centos-8"
}
```