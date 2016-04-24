# KrishnanAzureExample
Trying to get the first example from "Programming Windows Azure, by  Sriram Krishnan" to work

It appears that changes in the Azure SDK have gotten his example to fail


To run this

> cspack ServiceDefinition.csdef /role:WebRole1;htmlwebsite /out:output /copyonly
>
> csrun /run:output;ServiceConfiguration.cscfg
