## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_flow_log.flowlog](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/flow_log) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_enable_flow_log"></a> [enable\_flow\_log](#input\_enable\_flow\_log) | n/a | `bool` | `true` | no |
| <a name="input_flowlog_log_destination"></a> [flowlog\_log\_destination](#input\_flowlog\_log\_destination) | n/a | `string` | `""` | no |
| <a name="input_flowlog_log_destination_type"></a> [flowlog\_log\_destination\_type](#input\_flowlog\_log\_destination\_type) | n/a | `string` | `"cloud-watch-logs"` | no |
| <a name="input_flowlog_role_arn"></a> [flowlog\_role\_arn](#input\_flowlog\_role\_arn) | n/a | `string` | `""` | no |
| <a name="input_flowlog_tags"></a> [flowlog\_tags](#input\_flowlog\_tags) | n/a | `map(string)` | <pre>{<br/>  "Terraform": "true"<br/>}</pre> | no |
| <a name="input_flowlog_traffic_type"></a> [flowlog\_traffic\_type](#input\_flowlog\_traffic\_type) | n/a | `string` | `"ALL"` | no |
| <a name="input_vpc_id"></a> [vpc\_id](#input\_vpc\_id) | n/a | `string` | `""` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_flowlog_arn"></a> [flowlog\_arn](#output\_flowlog\_arn) | n/a |
| <a name="output_flowlog_id"></a> [flowlog\_id](#output\_flowlog\_id) | n/a |
