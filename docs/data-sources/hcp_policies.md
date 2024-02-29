---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rhcs_hcp_policies Data Source - terraform-provider-rhcs"
subcategory: ""
description: |-
  List of ROSA operator role policies and account role policies.
---

# rhcs_hcp_policies (Data Source)

List of ROSA operator role policies and account role policies.



<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `account_role_policies` (Attributes) Account role policies. (see [below for nested schema](#nestedatt--account_role_policies))
- `operator_role_policies` (Attributes) Operator role policies. (see [below for nested schema](#nestedatt--operator_role_policies))

<a id="nestedatt--account_role_policies"></a>
### Nested Schema for `account_role_policies`

Read-Only:

- `sts_hcp_installer_permission_policy` (String)
- `sts_hcp_instance_worker_permission_policy` (String)
- `sts_hcp_support_permission_policy` (String)


<a id="nestedatt--operator_role_policies"></a>
### Nested Schema for `operator_role_policies`

Read-Only:

- `openshift_hcp_capa_controller_manager_credentials_policy` (String)
- `openshift_hcp_cloud_network_config_controller_cloud_credentials_policy` (String)
- `openshift_hcp_cluster_csi_drivers_ebs_cloud_credentials_policy` (String)
- `openshift_hcp_control_plane_operator_credentials_policy` (String)
- `openshift_hcp_image_registry_installer_cloud_credentials_policy` (String)
- `openshift_hcp_ingress_operator_cloud_credentials_policy` (String)
- `openshift_hcp_kms_provider_credentials_policy` (String)
- `openshift_hcp_kube_controller_manager_credentials_policy` (String)
- `shared_vpc_openshift_ingress_operator_cloud_credentials_policy` (String)