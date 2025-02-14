---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rancher2_secret_v2 Resource - terraform-provider-rancher2"
subcategory: ""
description: |-
  
---

# rancher2_secret_v2 (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **cluster_id** (String) K8s cluster ID
- **data** (Map of String, Sensitive) Secret data map
- **name** (String) K8s Secret name

### Optional

- **annotations** (Map of String) Annotations of the resource
- **id** (String) The ID of this resource.
- **immutable** (Boolean) If set to true, ensures that data stored in the Secret cannot be updated
- **labels** (Map of String) Labels of the resource
- **namespace** (String) K8s Secret namespace
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))
- **type** (String) Used to facilitate programmatic handling of Secret data

### Read-Only

- **resource_version** (String)

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)


