---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rancher2_certificate Resource - terraform-provider-rancher2"
subcategory: ""
description: |-
  
---

# rancher2_certificate (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **certs** (String) Certificate certs base64 encoded
- **key** (String, Sensitive) Certificate key base64 encoded
- **project_id** (String) Project ID to add certificate

### Optional

- **annotations** (Map of String) Annotations of the resource
- **description** (String) Certificate description
- **id** (String) The ID of this resource.
- **labels** (Map of String) Labels of the resource
- **name** (String) Certificate name
- **namespace_id** (String) Namespace ID to add certificate
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)


