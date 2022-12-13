## Plan
1. propose the solution for two stories, 
2. prepare the code, 
3. update Status and How-to sections,
4. create pull request to finally marge it into `main` branch,

## Story1
---
5a. Prepare the code to  deploy and remove three azure storage accounts;

### Requirements:
- codebase execution should guarantee the same results each time;
- code should be prepared in a way that **Name** and **Replication Type** are parametrized;
- only those two parameters are required: **Name** and **Replication Type**
- propose a solution which allows you to verify results in isolated Non-Prod and finally deploy in Prod env;
- all those three might be placed within a single RG;
- disable public network access on those accounts;

```
storage_accounts = [
{
    "Name" : "stvcccloudtalks111"
    "Replication Type" : "LRS"
},
{
    "Name" : "stvcccloudtalks222"
    "Replication Type" : "GRS"
},
{
    "Name" : "stvcccloudtalks333"
    "Replication Type" : "LRS"
}
]
```

### Status
- [ ] code is prepared
- [ ] environments separation proposed;

### How-To
Please place below short instruction, on how to execute the code, with examples.

## Story2
---
5b. Prepare the code to create Azure Resource Group wihtin desired Azure Subscription;

### Requirements:
- solution should be exposed as a self service offering;
- every authenticated and authorized user should be able to create such RG via API call;
- propose authorization method to verify if customer has proper right towards subjected subscription;
- code should be prepared in a way that  resource group **Name** is randomized;
- only one parameter is required **SubscriptionID*;

### Status
- [ ] solution is proposed,
- [ ] code is created;

### HowTo
Please place below short instruction, on how to execute the code, with examples.
