---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rancher2_node_template Data Source - terraform-provider-rancher2"
subcategory: ""
description: |-
  
---

# rancher2_node_template (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String)

### Optional

- **id** (String) The ID of this resource.
- **use_internal_ip_address** (Boolean)

### Read-Only

- **annotations** (Map of String)
- **cloud_credential_id** (String)
- **description** (String)
- **driver** (String)
- **engine_env** (Map of String)
- **engine_insecure_registry** (List of String)
- **engine_install_url** (String)
- **engine_label** (Map of String)
- **engine_opt** (Map of String)
- **engine_registry_mirror** (List of String)
- **engine_storage_driver** (String)
- **labels** (Map of String)
- **node_taints** (List of Object) (see [below for nested schema](#nestedatt--node_taints))

<a id="nestedatt--node_taints"></a>
### Nested Schema for `node_taints`

Read-Only:

- **effect** (String)
- **key** (String)
- **time_added** (String)
- **value** (String)


