# PHP-Insightly
## Getting started
### Composer
`composer require ggdx/php-insightly`


Currently a work in progress. The following traits are all done and usable:
* Activity Sets
* Comments
* Contacts
* Countries
* Currencies
* Custom Field Groups
* Custom Fields
* Emails
* Error
* Events
* File Attachments
* File Categories
* Follows
* Helpers
* Instance
* Leads
* LeadSources
* LeadStatus
* Milestones
* Notes
* Opportunities
* Opportunity Categories
* Opportunity State Reasons
* Permissions
* Pipelines


The following need to be built in:
* Organisations
* Pipeline Stages
* Project Categories
* Projects
* Relationships
* Tags
* Task Categories
* Team Members
* Teams
* Users

### Example:
```php
$insightly = new Insightly($api_key, $api_version) // $api_version is optional, v2.2 is default
$insightly->getContacts();
```

Documentation will follow but for now, all methods are fully documented in the code.
For $data arrays, please see https://api.insight.ly/v2.2/ for requirements. For the most part, Insightly is pretty flexible with "required" data but there are certain situations where a minimum dataset is required.
