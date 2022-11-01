## Plan
1. Prepare the code and deploy and remove 3xAzure Storage Accounts;

Requiremnts:
- codebase execution should guarantee the same results each time;
- code should be prepared in a way that allows us to use it as CI/CD pipeline;
- propose a solution to deploy the same codebase across different environments;
- only two parameters are required;
- all those three might be palced within single RG;
- disable public network access on those accounts;

```
storage_accounts = [
{
    "Name" : "stvcccloudtalks111"
    "Replication Type" : "LRS"
},
{
    "Name" : "stvcccloudtalks222"
    "Type" : "GRS"
},
{
    "Name" : "stvcccloudtalks333"
    "Type" : "LRS"
}
]
```
2. Please follow PR to merge the code;
3. Update README file status and howto sections.

## Status
- [ ] Code is created
- [ ] Infra is deployed
- [ ] Environments separation proposed;
- [ ] Infra is removed


## HowTo
Please place here short instructions, on how to execute the code, with examples.
