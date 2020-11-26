# Docker Azure DevOps Build Agent with Ansible
A docker-compose configuration to run an Azure DevOps build agent with Ansible.

Built based on guidance here - https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/v2-linux?view=azure-devops

See the linked documentation for information about configuring Agent Pools and obtaining a Personal Access Token.

## Instructions

* Clone the git repository
* Copy file .env.template to .env and edit new file with required values.
* Run the docker-compose configuration using `docker-compose up`

Once the agent's container is running it will be marked as Online in the list of
agents for your Azure DevOps project's Agent Pool.