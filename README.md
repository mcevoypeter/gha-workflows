# [GitHub Actions][gha] Workflows

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.txt)

## Workflows

| Workflow                                                                      | Purpose                                                                |
| ----------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [`publish-gpr-npm-package`](./.github/workflows/publish-gpr-npm-package.yaml) | Publish an [NPM] package to the [GitHub Packages Registry][gpr].       |
| [`terraform-plan`](./.github/workflows/terraform-plan.yaml)                   | Run `terraform plan` in a [Terraform Cloud] organization's workspace.  |
| [`terraform-apply`](./.github/workflows/terraform-apply.yaml)                 | Run `terraform apply` in a [Terraform Cloud] organization's workspace. |
| [`upload-s3-object`](./.github/workflows/upload-s3-object.yaml)               | Upload an object to an [AWS] [S3] bucket.                              |

## License

This project is licensed under the terms of the [MIT license](https://en.wikipedia.org/wiki/MIT_License).

[AWS]: https://aws.amazon.com
[gha]: https://docs.github.com/en/actions
[gpr]: https://github.com/features/packages
[NPM]: https://www.npmjs.com/
[S3]: https://aws.amazon.com/s3
[Terraform Cloud]: https://developer.hashicorp.com/terraform/cloud-docs
