---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "commvault_company Resource - terraform-provider-commvault"
subcategory: ""
description: |-
  
---

# commvault_company (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **company_alias** (String) Specifies the Alias name for the company.
- **company_name** (String) Specifies the name of the Company.
- **contact_name** (String) Specifies Name of the tenant administrator.
- **email** (String) Specifies Email address for the tenant administrator.

### Optional

- **associated_smtp** (String) Specifies the SMTP address of the company.
- **company_id** (Number) Sepcifies the company id to which the child company should be associated with.
- **id** (String) The ID of this resource.
- **plans** (Set of String) Specifies the data protection plans to use for the company. The plans you select are the plans that the tenant administrator can choose from.
- **send_email** (Boolean) Specifies whethere email needs to be sent ot not

