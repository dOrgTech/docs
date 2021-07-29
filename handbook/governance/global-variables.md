# Global Variables

dOrg's global state variables are defined in its `org.json`.

This file may only be altered through DAO proposals.

{% code title="org.json" %}
```javascript
{
  "name" : "dOrg",
  "description" : "A full stack Web3 development collective",
  "address" : {
    "mainnet": "0x15344ecdc2c4edfcb092e284d93c20f0529fd8a6",
    "xdai": "0x94a587478c83491b13291265581cb983e7feb540"
  },
  "homepage" : "https://dorg.tech",
  "email" : "contact@dorg.tech",
  "social" : {
    "Twitter" : "https://twitter.com/dOrg_tech",
    "LinkedIn" : "https://www.linkedin.com/company/dorg-tech/",
    "Medium" : "https://medium.com/dorg-tech",
  },
  "spaces" : {
    "Discord" : "https://discord.com/invite/6Kujmad",
    "Github" : "https://github.com/dOrgTech",
    "Airtable" : "" ,
    "Google" : "",
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
    "interest-rate" : .025, // Annual compounding rate for DORG Tokens
    "deactivation-thresh" : 90, // Days of inactivity to trigger deactivation
    "sourcing-rate" : 0.10, // % distributed to sourcing leads
    "savings-rate" : 0.10, // % retained by the DAO
    "referral-rate" : 0.00 // Rewarded on first $100k earned by referred builder
  },
}
```
{% endcode %}

