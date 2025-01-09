## What is this document about?
The purpose of this document is to guide you through the steps to create a new Bakta(v1.10.3) full DB on AWS.

Some critical points to pay attention to:
1. The script demands **77 GB of storage** to store your Bakta full DB.
2. We didn't measure the timming of the building process because it depends of our Instance type, a good starting point as a cost-effective solution is a t3.xlarge.

We have 2 AWS solutions to reduce the prices/complexity of your construction:
1. AWS ECS + [Task Definition](https://github.com/ldipotetjob/kraken2/blob/kraken2aws_profilingfromv2.1.3/docs/awsStandardDB/krakenDBScriptTaskDef.json) (You don't need to create any service)(automated construction of the kraken2 standard database)
2. Manual construction configuring kraken2 at the instance user data

[Reference to the previous architectural solutions]() 


We support our opinions on the profiling information [gathered in the construction of Bakta full DB]()