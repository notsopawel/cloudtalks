## ActionPlan
1. Prepare the code to provision 3xEC2 instances;
- codebase execution should guarantee the same results;
- code should be prepared in a way that allows us to use it as CI/CD pipeline;
- propose a solution to deploy the same codebase across different environments;
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
3. Update README file status and howto sections.

## Status
- [ ] EC2 instances;
- [ ] Branch&PR;
- [ ] Environments separation;


## HowTo
Please place here short instructions, on how to execute the code, with examples.

![image](https://user-images.githubusercontent.com/81424793/201279425-acb01a92-2867-40cb-91ae-376a62c52a51.png)
