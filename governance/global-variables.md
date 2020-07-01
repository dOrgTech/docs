# org.json

dOrg's global state variables are defined in its `org.json`.

This file may only be altered through DAO proposals.

{% code title="org.json" %}
```javascript
{
  "name" : "dOrg",
  "description" : "A self-service web3 development agency",
  "address" : "0x15344ecdc2c4edfcb092e284d93c20f0529fd8a6",
  "homepage" : "https://dorg.tech",
  "email" : "contact@dorg.tech",
  "social" : {
    "Twitter" : "https://twitter.com/dOrg_tech",
    "LinkedIn" : "https://www.linkedin.com/company/dorg-tech/",
    "Medium" : "https://medium.com/dorg-tech",
  },
  "spaces" : {
    "Keybase" : "https://keybase.io/team/dorg",
    "Github" : "https://github.com/dOrgTech",
    "Airtable" : "" ,
    "Zoho" : "",
  },
  "legal" : {
    "name" : "dOrg, LLC",
    "address" : {
      "street": "76 St. Paul St, 7th Floor, P.O. Box 369",
      "city" : "Burlington",
      "region" : "VT",
      "postal" : "05402",
      "country" : "USA"
    },
    "business-id" : "0357139",
    "tax-id" :"84-2930500"
  },
  "dependencies" : {
    "@daostack/arc" : "0.0.1-rc.33",
  },
  "config" : {
    "rep-rate" : 1.00, // Rep received per USD earned
    "interest-rate" : .00, // Annual compounding rate for DORG Tokens
    "admin-thresh" : 30000, // Rep needed for administrator permissions to spaces
    "deactivation-thresh" : 90, // Days of inactivity to trigger deactivation
  },
}
```
{% endcode %}

