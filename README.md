# actions-playground

General Idea:

Create a stage that reads in all the variables and then sets output like `::set-output name=url::'value`.

Have a reusable workflow for each major stage of the workflow. These can be turned on/off with a variable at the top of the workflow.

In each reusable workflow execute a series of composite actions.



Can we get cheeky if we need another level for ring deployments. Like can I make a toplevel that has ring 0/1/2 as options. Depending on which are selected invoke the ring deployment workflow with different paramters. See something like: https://github.com/peter-evans/repository-dispatch
