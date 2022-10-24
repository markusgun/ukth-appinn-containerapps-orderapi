# Challenge 7: Enable Container App authentication
Azure Container Apps provides built-in authentication and authorization features (sometimes referred to as _Easy Auth_), to secure your external ingress-enabled container app with minimal or no code.

Up until now we have allowed anonymous access to the application. Let's protect the Dashboard App web application with Azure AD authentication using the _Easy Auth_ service built into Container Apps.


The following image illustrates the steps in this challenge

![](images/challenge-7-overview.png)


## Main objectives
- Enable Azure AD Authentication on Container App
- Log in to Container App


## Activities
- Configure Azure AD identity provider for _Dashboard App_
- Verify authentication by accessing _Dashboard App_ with browser.



## Definition of done
- Configured Azure AD authentication for _Dashboard App_ Container App
- Browse _Dashboard App_ and verify you are prompted for login
- Performed a successful login to view _Dashboard App_ (https://dashboardapp.[your container app environment domain]) 

 

## Helpful links
- [Authentication and authorization in Azure Container Apps (learn.microsoft.com)](https://docs.microsoft.com/en-us/azure/container-apps/authentication)
- [Enable authentication and authorization in Azure Container Apps with Azure Active Directory (learn.microsoft.com)](https://learn.microsoft.com/en-us/azure/container-apps/authentication-azure-active-directory)

## Solution
- View the solution here: [Challenge 7 - Solution](solution7.md)

## The challenges

- [Challenge 1: Setup the environment](challenge1.md)
- [Challenge 2: Deploy Container Apps Environment and troubleshoot Container Apps](challenge2.md)
- [Challenge 3: Split traffic for controlled rollout](challenge3.md)
- [Challenge 4: Scale Container Apps](challenge4.md)
- [Challenge 5: Configure CI/CD for Container Apps](challenge5.md)
- [Challenge 6: Protect Container App with API Management](challenge6.md)
- [Challenge 7: Enable Container App authentication](challenge7.md)
