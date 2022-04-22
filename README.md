# actions-playground

General Idea:

Create a stage that reads in all the variables and then sets output like `::set-output name=url::'value`.

Have a reusable workflow for each major stage of the workflow. These can be turned on/off with a variable at the top of the workflow.

In each reusable workflow execute a series of composite actions.
