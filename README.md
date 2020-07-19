# Terraform Backend S3

Terraform module that configures an S3 bucket to
be used for managing remote state.

## Getting started

Define the module.

```terraform
module "terraform-backend-s3" {
  source = "github.com/wurde/terraform-backend-s3"

  bucket_name = "example-bucket-name"
  role_name   = "example-role-name"
}
```

## License

This project is __FREE__ to use, reuse, remix, and resell.
This is made possible by the [MIT license](/LICENSE).
