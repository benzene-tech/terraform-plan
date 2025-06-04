# terraform-plan

### Usage

```yaml
name: Terraform

on:
  push:

jobs:
  terraform:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - uses: hashicorp/setup-terraform@v3

      - name: Plan
        uses: benzene-tech/terraform-plan@v2
```
