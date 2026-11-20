<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
| ---- | ------- |
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.4.2 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | >= 5.7.0 |

## Providers

| Name | Version |
| ---- | ------- |
| <a name="provider_aws"></a> [aws](#provider\_aws) | >= 5.7.0 |

## Modules

No modules.

## Resources

| Name | Type |
| ---- | ---- |
| [aws_elastic_beanstalk_application_version.application_version](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/elastic_beanstalk_application_version) | resource |
| [aws_s3_object.object](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_object) | resource |

## Inputs

| Name | Description | Type | Default | Required |
| ---- | ----------- | ---- | ------- | :------: |
| <a name="input_application_bucket"></a> [application\_bucket](#input\_application\_bucket) | The name of the bucket. | `string` | `"elasticbeanstalk-eu-central-1"` | no |
| <a name="input_application_description"></a> [application\_description](#input\_application\_description) | Short description of the Application Version. | `string` | `"Beanstalk Application"` | no |
| <a name="input_application_name"></a> [application\_name](#input\_application\_name) | Name of the Beanstalk Application. | `string` | `"beanstalk"` | no |
| <a name="input_application_name_version"></a> [application\_name\_version](#input\_application\_name\_version) | Version of the Beanstalk Application. | `string` | `"beanstalk-1"` | no |
| <a name="input_application_source"></a> [application\_source](#input\_application\_source) | The source file with application code. | `string` | `"app.zip"` | no |

## Outputs

| Name | Description |
| ---- | ----------- |
| <a name="output_application_version"></a> [application\_version](#output\_application\_version) | n/a |
<!-- END_TF_DOCS -->