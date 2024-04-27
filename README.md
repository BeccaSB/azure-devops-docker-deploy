# Azure DevOps Docker Deployment

This repository contains Azure Pipelines YAML files for automating the build and deployment of Docker containers to Azure App Service using Azure DevOps.

## Getting Started

To use these pipelines, you'll need to set up an Azure DevOps project and configure the required Azure resources, including a container registry and an Azure App Service.

1. Create a new Azure DevOps project.
2. Set up a Docker container registry in Azure.
3. Set up an Azure App Service for hosting your containerized applications.
4. Update the pipeline YAML files with your Azure subscription details and resource names.

## Usage

1. Fork or clone this repository to your local machine.
2. Customize the pipeline YAML files according to your project requirements.
3. Commit and push your changes to your GitHub repository.
4. Set up a new pipeline in Azure DevOps, pointing to your repository.
5. Trigger the pipeline to start the build and deployment process.

For detailed instructions on setting up and using these pipelines, refer to the [Azure DevOps documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/?view=azure-devops).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
