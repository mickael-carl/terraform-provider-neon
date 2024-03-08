---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "neon_branch_roles Data Source - terraform-provider-neon"
subcategory: ""
description: |-
  Fetch Branch Roles.
---

# neon_branch_roles (Data Source)

Fetch Branch Roles.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `branch_id` (String) Branch ID.
- `project_id` (String) Project ID.

### Read-Only

- `id` (String) The ID of this resource.
- `roles` (Block List) (see [below for nested schema](#nestedblock--roles))

<a id="nestedblock--roles"></a>
### Nested Schema for `roles`

Read-Only:

- `name` (String) Role name.
- `protected` (Boolean)