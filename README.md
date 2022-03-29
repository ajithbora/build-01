## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_google"></a> [google](#provider\_google) | n/a | <a
| name="provider_local"></a> [local](#provider\_local) | n/a |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_address-fe"></a> [address-fe](#module\_address-fe) |
| terraform-google-modules/address/google | 3.1.1 |

## Resources

| Name | Type |
|------|------|
| [local_file.vm_ip_list](https://registry.terraform.io/providers/hashic
| orp/local/latest/docs/resources/file) | resource |
| [google_compute_subnetwork.subnet](https://registry.terraform.io/provi
| ders/hashicorp/google/latest/docs/data-sources/compute_subnetwork) |
| data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_application"></a> [application](#input\_application) |
| n/a | `any` | n/a | yes | <a name="input_environment"></a>
| [environment](#input\_environment) | n/a | `any` | n/a | yes | <a
| name="input_function"></a> [function](#input\_function) | n/a | `any`
| | n/a | yes | <a name="input_project"></a> [project](#input\_project)
| | n/a | `any` | n/a | yes | <a name="input_region"></a>
| [region](#input\_region) | n/a | `any` | n/a | yes | <a
| name="input_subnetwork"></a> [subnetwork](#input\_subnetwork) | n/a |
| `any` | n/a | yes | <a name="input_subnetwork_project"></a>
| [subnetwork\_project](#input\_subnetwork\_project) | n/a | `any` | n/a
| | yes | <a name="input_vm_count"></a> [vm\_count](#input\_vm\_count) |
| n/a | `any` | n/a | yes | <a name="input_vm_names"></a>
| [vm\_names](#input\_vm\_names) | n/a | `any` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_addresses"></a> [addresses](#output\_addresses) | List
| of address values managed by this module (e.g. ["1.2.3.4"]) | <a
| name="output_names"></a> [names](#output\_names) | List of address
| resource names managed by this module (e.g.
| ["gusw1-dev-fooapp-fe-0001-a-0001-ip"]) | <a
| name="output_vm_ip_list"></a> [vm\_ip\_list](#output\_vm\_ip\_list) |
| List of VM names and associated  ip\_address as a pair |
