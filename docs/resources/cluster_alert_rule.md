---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rancher2_cluster_alert_rule Resource - terraform-provider-rancher2"
subcategory: ""
description: |-
  
---

# rancher2_cluster_alert_rule (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **cluster_id** (String) Alert rule cluster ID
- **group_id** (String) Alert rule group ID
- **name** (String) Alert rule name

### Optional

- **annotations** (Map of String) Annotations of the resource
- **event_rule** (Block List, Max: 1) Alert event rule (see [below for nested schema](#nestedblock--event_rule))
- **group_interval_seconds** (Number) Alert rule interval seconds
- **group_wait_seconds** (Number) Alert rule wait seconds
- **id** (String) The ID of this resource.
- **inherited** (Boolean) Alert rule inherited
- **labels** (Map of String) Labels of the resource
- **metric_rule** (Block List, Max: 1) Alert metric rule (see [below for nested schema](#nestedblock--metric_rule))
- **node_rule** (Block List, Max: 1) Alert node rule (see [below for nested schema](#nestedblock--node_rule))
- **repeat_interval_seconds** (Number) Alert rule repeat interval seconds
- **severity** (String) Alert rule severity
- **system_service_rule** (Block List, Max: 1) Alert system service rule (see [below for nested schema](#nestedblock--system_service_rule))
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))

<a id="nestedblock--event_rule"></a>
### Nested Schema for `event_rule`

Required:

- **resource_kind** (String) Resource kind

Optional:

- **event_type** (String) Event type


<a id="nestedblock--metric_rule"></a>
### Nested Schema for `metric_rule`

Required:

- **duration** (String) Metric rule duration
- **expression** (String) Metric rule expression
- **threshold_value** (Number) Metric rule threshold value

Optional:

- **comparison** (String) Metric rule comparison
- **description** (String) Metric rule description


<a id="nestedblock--node_rule"></a>
### Nested Schema for `node_rule`

Optional:

- **condition** (String) Node rule condition
- **cpu_threshold** (Number) Node rule cpu threshold
- **mem_threshold** (Number) Node rule mem threshold
- **node_id** (String) Node ID
- **selector** (Map of String) Node rule selector


<a id="nestedblock--system_service_rule"></a>
### Nested Schema for `system_service_rule`

Optional:

- **condition** (String) System service rule condition


<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)


