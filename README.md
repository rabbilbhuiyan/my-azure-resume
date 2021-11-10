# azure-resume
My own azure resume - deployment using Azure App Service and GitHub

# Creating project directory
- creating project structure
- create a new github repo and clone it to local machine
- Also clone the [a cloud guru](https://github.com/ACloudGuru-Resources/acg-project-azure-resume-starter) repo to local machine
- copy the front end (Html, CSS files) from a cloud guru repo to your own repo
- frontend folder contains the static website

```
<header id="home">

      <nav id="nav-wrap">

         <a class="mobile-btn" href="#nav-wrap" title="Show navigation">Show navigation</a>
         <a class="mobile-btn" href="#" title="Hide navigation">Hide navigation</a>

```

# Creating the App Services in Azure
- from portal using App Services create Web App 
- follow the settings - resource group, instance name, region, Windows plan and sku size etc
- get the notication Deployment succeeded

# Set up the deployment in Azure
- Click go the resource
- under Deployment center, provide source code provider as GitHub
- login to the GitHub credentials
- select the repository
- Azure will provide the url for the resume website

# CI/CD with GitHub
- use Sync to update any changes in the github code
