# N8N Sentry Error Workflow for N8N Cloud


## Important information

 - for cloud version of N8N
 - supports environments (by switcher node)


## Installation
 - import `workflow.json` to your account
 - set your Sentry account in the "Sentry Creds" node
 - set your environment workflow ids in the "Environment switcher" node
 - got to the settings and modify "This workflow can be called by" setting (choose all workflows you want to have permission to run this one)
 - go to the settings of your main workflows and modify "Error Workflow" setting by choosing workflow you imported to 