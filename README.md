# README
Contains general info about this Organization and Ellucian Experience development

## Initial Configuration of Development Environment
The following steps will help you configure your environment for developing cards and pages in Ellucian Experience.

### Install Node
Careful here because Ellucian may require certain versions of node.js and other frameworks, and may not stay current with the LTS or current releases. Supported versions are found in Ellucian Resources: https://resources.elluciancloud.com/bundle/ellucian_experience/page/t_install_node_js_experience_sdk.html

### Github Access
Be sure you have access to the correct Github. All extensions developed by SHSU are located in this GitHub Organization: https://github.com/it-ellucian-experience

### Install Git
1. 

## Development

### Naming Conventions for Extensions

### Create a new Experience Extension project
*All instructions here assume you are using Windows 11 and VS Code*

1.   Create extension project in local development environment.
  1.   https://resources.elluciancloud.com/bundle/ellucian_experience/page/t_create_extension.html
  2.   Clear the cache by entering the following command: npx clear-npx-cache
Cached commands can sometimes cause an extension to be incorrectly created with a previous version of the SDK. Clearing the cache ensures that the extension is created with the latest SDK version.

Enter npx -p https://cdn.elluciancloud.com/assets/SDK/latest/ellucian-create-experience-extension-latest.tgz create-experience-extension your_extension_name, replacing your_extension_name with the desired name of the extension.

### Sync with Github
1. Create project in Github
2. Initialize repo
3. Sync with Github

### Deploy to Experience Test

- **Version Number**. For each deployment to Experience Test, you will need to update the version number in the 

### Deploy to Experience Prod
