---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rancher2_global_dns Resource - terraform-provider-rancher2"
subcategory: ""
description: |-
  
---

# rancher2_global_dns (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **fqdn** (String)
- **provider_id** (String)

### Optional

- **annotations** (Map of String) Annotations of the resource
- **id** (String) The ID of this resource.
- **labels** (Map of String) Labels of the resource
- **multi_cluster_app_id** (String)
- **name** (String)
- **project_ids** (List of String)
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))
- **ttl** (Number)

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)


