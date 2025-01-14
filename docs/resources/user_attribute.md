---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "looker_user_attribute Resource - terraform-provider-looker"
subcategory: ""
description: |-
  
---

# looker_user_attribute (Resource)



## Example Usage

```terraform
resource "looker_user_attribute" "my_user_attribute" {
  name  = "my_name"
  label = "Display Label"
  type  = "advanced_filter_string"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **label** (String) Human-friendly label for user attribute
- **name** (String) Name of user attribute
- **type** (String) Type of user attribute (string, number, datetime, relative_url, advanced_filter_datetime, advanced_filter_number, advanced_filter_string)

### Optional

- **default** (String) Default value for when no value is set on the user
- **id** (String) The ID of this resource.
- **user_access** (String) Field describing the access non admin users have to their attributes. `view` Non-admin users can see the values of their attributes and use them in filters. `edit` Users can change the value of this attribute for themselves. `none` non-admin users have no access to this user attribute


