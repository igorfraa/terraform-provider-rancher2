---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rancher2_app Resource - terraform-provider-rancher2"
subcategory: ""
description: |-
  
---

# rancher2_app (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **catalog_name** (String) Catalog name of the app
- **name** (String) Name of the app
- **project_id** (String) Project ID to add app
- **target_namespace** (String) Namespace name to add app
- **template_name** (String) Template name of the app

### Optional

- **annotations** (Map of String) Annotations of the resource
- **answers** (Map of String) Answers of the app
- **description** (String)
- **force_upgrade** (Boolean) Force app upgrade
- **id** (String) The ID of this resource.
- **labels** (Map of String) Labels of the resource
- **revision_id** (String) App revision id
- **template_version** (String) Template version of the app
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))
- **values_yaml** (String) values.yaml base64 encoded file content of the app
- **wait** (Boolean) Wait until app is deployed and active

### Read-Only

- **external_id** (String) External ID of the app

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)


