<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

No providers.

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_compute"></a> [compute](#module\_compute) | ./modules/compute | n/a |
| <a name="module_database"></a> [database](#module\_database) | ./modules/database | n/a |
| <a name="module_networking"></a> [networking](#module\_networking) | ./modules/networking | n/a |
| <a name="module_resourcegroup"></a> [resourcegroup](#module\_resourcegroup) | ./modules/resourcegroup | n/a |
| <a name="module_securitygroup"></a> [securitygroup](#module\_securitygroup) | ./modules/securitygroup | n/a |

## Resources

No resources.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_app_host_name"></a> [app\_host\_name](#input\_app\_host\_name) | n/a | `any` | n/a | yes |
| <a name="input_app_os_password"></a> [app\_os\_password](#input\_app\_os\_password) | n/a | `any` | n/a | yes |
| <a name="input_app_username"></a> [app\_username](#input\_app\_username) | n/a | `any` | n/a | yes |
| <a name="input_appsubnetcidr"></a> [appsubnetcidr](#input\_appsubnetcidr) | n/a | `any` | n/a | yes |
| <a name="input_dbsubnetcidr"></a> [dbsubnetcidr](#input\_dbsubnetcidr) | n/a | `any` | n/a | yes |
| <a name="input_location"></a> [location](#input\_location) | n/a | `any` | n/a | yes |
| <a name="input_name"></a> [name](#input\_name) | n/a | `any` | n/a | yes |
| <a name="input_primary_database"></a> [primary\_database](#input\_primary\_database) | n/a | `any` | n/a | yes |
| <a name="input_primary_database_admin"></a> [primary\_database\_admin](#input\_primary\_database\_admin) | n/a | `any` | n/a | yes |
| <a name="input_primary_database_password"></a> [primary\_database\_password](#input\_primary\_database\_password) | n/a | `any` | n/a | yes |
| <a name="input_primary_database_version"></a> [primary\_database\_version](#input\_primary\_database\_version) | n/a | `any` | n/a | yes |
| <a name="input_vnetcidr"></a> [vnetcidr](#input\_vnetcidr) | n/a | `any` | n/a | yes |
| <a name="input_web_host_name"></a> [web\_host\_name](#input\_web\_host\_name) | n/a | `any` | n/a | yes |
| <a name="input_web_os_password"></a> [web\_os\_password](#input\_web\_os\_password) | n/a | `any` | n/a | yes |
| <a name="input_web_username"></a> [web\_username](#input\_web\_username) | n/a | `any` | n/a | yes |
| <a name="input_websubnetcidr"></a> [websubnetcidr](#input\_websubnetcidr) | n/a | `any` | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->