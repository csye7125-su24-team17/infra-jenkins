Terraform infra for Jenkins Server
## Terraform commands

  Initializes the working directory containing Terraform configuration files:

```console
$ terraform init
```

  Rewrite Terraform configuration files to a canonical format and style:

```console
$ terraform fmt .
```

  Validate the configuration files in a directory:

```console
$ terraform validate .
```

## Building the cloud infrastructure

   Creates an execution plan, which lets you preview the changes that Terraform plans to make to your infrastructure:

```console
$ terraform plan
```

   Apply a configuration to build infra:

```console
$ terraform apply
```

## Destroying the cloud infrastructure

   Destroy infrastructure:

```console
$ terraform destroy
```
