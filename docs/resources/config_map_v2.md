---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rancher2_config_map_v2 Resource - terraform-provider-rancher2"
subcategory: ""
description: |-
  
---

# rancher2_config_map_v2 (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **cluster_id** (String) K8s cluster ID
- **data** (Map of String) ConfigMap V2 data map
- **name** (String) ConfigMap V2 name

### Optional

- **annotations** (Map of String) Annotations of the resource
- **id** (String) The ID of this resource.
- **immutable** (Boolean) If set to true, ensures that data stored in the ConfigMap cannot be updated
- **labels** (Map of String) Labels of the resource
- **namespace** (String) ConfigMap V2 namespace
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))

### Read-Only

- **resource_version** (String)

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)


