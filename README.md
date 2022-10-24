## Action 
1. Prepare the code to provision 3xEC2 instances;
- codebase execution should guarantee same results;
- code should be prepared in the way that allow us to use it as CI/CD pipeline;
- propose solution to deploy same codebase across different environmets;
- only two parameters are required: Name and Instance type
```
instances  = [
{
    "Name" : "EC2_1"
    "Type" : "t2.micro"
},
{
    "Name" : "EC2_2"
    "Type" : "t2.small"
},
{
    "Name" : "EC2_3"
    "Type" : "t2.mini"
}
]
```
2. Please follow PR to merge the code;
5. Update README file status and howto sections.

## Status
- [ ] EC2 instances;
- [ ] Branch&PR;
- [ ] Environments separation;


## HowTo
Please please here short instruction how to execute the code, with examples.
