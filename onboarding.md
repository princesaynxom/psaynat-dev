[[_TOC_]]

# Access 

## Active Directory Group

### Web Dev
- `DEVSERVICES.AZURE.DEV.CONTRIBUTOR.UG` - group providing access to Azure Subscription DEV_APP_MADS and PRD_APP_MADS
- `EMIT-DS-WEB-DEVELOPER.UG` - group providing access for all team members (TFE)
- `EMIT-DS-WEB-DEV-ADMIN.UG ` - group providing access for PO, SM and Arch
- `OCP.SSO.USERS.UG` - This is required to log on OCP4 
- `GITHUB-INTERNAL-DEVELOPER.UG` - will add you to [Internal-Developers GitHub team](https://github.com/orgs/ExxonMobil/teams/internal-developers) for inner-sourcing

### CICD 

- `CI-CD.ENABLEMENT.UG` - group providing most of accesses for CICD team ✅
- `MAP-CICD-ITPA-USERS.UG` - for checking out service account in ITPA `EMPLOYEE-ONLY` ✅

You can submit a request using [LAN Active Directory Group Access - IT Service Portal](https://emprod.service-now.com/itsp?id=sc_cat_item&sys_id=aa73c5761b1170108b18326ecc4bcb97).

## Email Distribution List

🟡 Refer to #169488

- [`GSC-EMIT-BANGKOK-DS-WEB-DEVELOPER`](mailto:GSC-EMIT-BANGKOK-DS-WEB-DEVELOPER@exxonmobil.com): BKK team - ask @princesaynxom to add
- [`GSC-EMIT-BA-DS-WEB-DEVELOPER`](mailto:GSC-EMIT-BA-DS-WEB-DEVELOPER@exxonmobil.com): BKK team - ask @princesaynxom to add

// do we still need this
- [`GSC-EMIT-APPS-MA&P-D&DS-CICD`](mailto:GSC-EMIT-APPS-MA&P-D&DS-CICD@exxonmobil.com): containing East and West group below - no need to add
- [`GSC-EMIT-APPS-MA&P-D&DS-CICD-EAST`](mailto:GSC-EMIT-APPS-MA&P-D&DS-CICD-EAST@exxonmobil.com): East team - ask @princesaynxom to add


## Zoom

### Private Group

Ask anyone who should be already in the group to add you in.

- `Web Club`: Global team general discussions and announcements 
- `CI/CD Pipelines`: Global team general discussions and announcements 
- `CI/CD + Web Dev GitHub`: Global team GitHub PR review 
- `Standard Devs & Designers`: Global team general discussions on Design team support

### Public Channels

You can search for channel and join in by yourself.

- _REQUIRED_: `Let's talk Devs`: Community of developers
- _REQUIRED_: `CI/CD Development Automation`: XOM community general discussions about CI/CD 
  - BKK Team roster: https://zoom.us/wb/doc/GfETMCHlQWih2z2HZAsucQ/p/253763758308897?option=sso
- _OPTIONAL_: `Terraform Community`: XOM community general discussions about Terraform
- _OPTIONAL_: `Azure Remediation Community of Practice`: Community of subscription owners and custodians to help resolve Azure policies.
- _OPTIONAL_: `NoDevNoLife`: Community of developers in Bangkok
- _OPTIONAL_: `Namespace Owner Community of Practice`: Community of OpenShift developers

## Azure DevOps

- [CICD Enablement Backlog items Board](https://emitdev.visualstudio.com/Cloud/_boards/board/t/DDS-CI%20CD%20Enablement/Backlog%20items) - this is our agile board ✅
  - contact @<Sasuwan, Thapanee>  to add into [DDS-CI CD Enablement team](https://emitdev.visualstudio.com/Cloud/_settings/teams?subjectDescriptor=vssgp.Uy0xLTktMTU1MTM3NDI0NS0xNTQ2NjM5NjkyLTE5MDA5MDgzNTMtMjIxNjQxODg1My0zODI1MDQ5NjUtMS0zNjE4OTc0Njc0LTY3NDA0OTA5Mi0yMzYyNTA2NzIyLTM1MDU3NTc3MTE).
- [CICD Enablement Azure Pipelines](https://dev.azure.com/xomDevS/CICD%20Enablement/_build) - this is our Azure Pipelines ✅
  - contact either @<Sasuwan, Thapanee> or @<E65FC941-0C0D-6CA1-8269-1B7E6D60348A>  to:
    - change [users](https://dev.azure.com/xomDevS/_settings/users) access level to `Basic`.
    - add as [CICD Enablement Project Administrators](https://dev.azure.com/xomDevS/CICD%20Enablement/_settings/permissions?subjectDescriptor=vssgp.Uy0xLTktMTU1MTM3NDI0NS0yMzkzNTU2Nzg0LTI5OTk4MzY5My0yNTI5NTU4NTE2LTI0ODQ3NDg4NDQtMC0wLTAtMC0x)
- `OPTIONAL`: [EM-ITOps - Azure DevOps](https://dev.azure.com/EM-ITOps/) - we gonna migrate to this org in the future
- `OPTIONAL`: [EM-testorg - Azure DevOps](https://dev.azure.com/EM-testorg) - this is for testing and can be your playground ✅
  - contact @<E65FC941-0C0D-6CA1-8269-1B7E6D60348A>  to create a new project and assign as an admin

## Azure Cloud

### EMCloudAD tenant

- [APPS_MAP_CICD_ENABLEMENT_DEV subscription](https://portal.azure.com/#@EMCloudAD.onmicrosoft.com/resource/subscriptions/abfc03d9-e6fe-4de1-9ad2-6c646403f01a/overview) with stranding _Contributor_ role ✅
  - [Ability to PIM up Owner role in APPS_MAP_CICD_ENABLEMENT_DEV](https://portal.azure.com/#blade/Microsoft_Azure_PIMCommon/ResourceMenuBlade/MyActions/resourceId/b1d97ea4-eb97-477f-9002-f097345c2726/resourceType/subscription/provider/azurerbac/resourceDisplayName/APPS_MAP_CICD_ENABLEMENT_DEV/resourceExternalId/%2Fsubscriptions%2Fabfc03d9-e6fe-4de1-9ad2-6c646403f01a) - _For subscription custodians only_
- [APPS_MAP_CICD_ENABLEMENT_PRD subscription](https://portal.azure.com/#@EMCloudAD.onmicrosoft.com/resource/subscriptions/e9c0eeda-69be-473e-9aed-5e2424f687a4/overview) ✅
  - [Ability to PIM up Contributor role in APPS_MAP_CICD_ENABLEMENT_PRD](https://portal.azure.com/#blade/Microsoft_Azure_PIMCommon/ResourceMenuBlade/MyActions/resourceId/3c9e12ca-d318-4bf0-a773-8127e6a40da1/resourceType/subscription/provider/azurerbac/resourceDisplayName/APPS_MAP_CICD_ENABLEMENT_PRD/resourceExternalId/%2Fsubscriptions%2Fe9c0eeda-69be-473e-9aed-5e2424f687a4) ✅

If you cannot access or don't have the mentioned roles, make sure you are added into `CI-CD.ENABLEMENT.UG`.

#### App Registration ✅

In addition, you should be the owner of the following App Registration, at least:

- _MAIN_: [APPS_MAP_CICD_ENABLEMENT_DEV_GH_ACTIONS](https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationMenuBlade/Owners/appId/b1aea8e7-3b34-4f63-b61c-1b1be49d5810/isMSAApp/)
- [APPS_MAP_CICD_ENABLEMENT_DEV_SVC](https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationMenuBlade/Owners/appId/c1ce8a5a-2c91-4d86-a46e-3610ec728d75/isMSAApp/)
- [APPS_MAP_CICD_ENABLEMENT_PRD_SVC](https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationMenuBlade/Owners/appId/a978fc78-0201-4463-ae0c-093608360360/isMSAApp/)

If you are not, ask any existing owner to add you in.

#### Personal Service Principal ✅

This is service principal for your own learning and testing. If you need one, go to [Cloud Self-Service Portal - Azure AD Applications](https://portal.xom.cloud/adApps), create a new application with naming convention below. If you are contractor, ask any Employee in the team to create and own on your behalf.

`CICD_ENABLEMENT_DEV_<YOUR_FIRST_NAME>`

Then ask @<E65FC941-0C0D-6CA1-8269-1B7E6D60348A> or @<AFC5DB11-07C9-4408-B122-C6E4360B1E92>  to add `Contributor` role assignment so it can create, modify, and delete resources in [APPS_MAP_CICD_ENABLEMENT_DEV](https://portal.azure.com/#@EMCloudAD.onmicrosoft.com/resource/subscriptions/abfc03d9-e6fe-4de1-9ad2-6c646403f01a/overview) subscription.

## GitHub

- [ExxonMobil - GitHub Enterprise Cloud](https://github.com/ExxonMobil) - where we store our source codes and run GitHub Actions workflows ✅
  - follow instructions on [GitHub Getting Started Guide | AppWiki](https://gotocloud.xom.cloud/cloudwiki/docs/DevOps/MigrateToGitHub.html#github-enterprise-cloud)
- [ci-cd-enablement - GitHub Teams](https://github.com/orgs/ExxonMobil/teams/ci-cd-enablement) ✅
  - make sure you are added into `CI-CD.ENABLEMENT.UG`.
- [ExxonMobil-DEV - GitHub Enterprise Cloud](https://github.com/ExxonMobil-DEV) - for testing only ✅
  - contact @<E65FC941-0C0D-6CA1-8269-1B7E6D60348A>  to add you in
- `ON-PREMISE`: [ExxonMobil - GitHub Enterprise Server](https://github.xom.com/ExxonMobil) - when it is needed to store source codes on-premise ✅
  - follow instructions on [GitHub Getting Started Guide | AppWiki](https://gotocloud.xom.cloud/cloudwiki/docs/DevOps/MigrateToGitHub.html#github-enterprise-server)
- `ON-PREMISE` `OPTIONAL`: [ExxonMobil - GitHub Enterprise Server ACC](https://githubacc.xom.com/ExxonMobil) ✅

## XomServices account

You can request `@xomservices.com` account from [Cloud Self-Service Portal](https://portal.xom.cloud/cloudAccounts). Please add `For Terraform Enterprise use` in the description when submitting the request. ✅

Once you get the account, follow [this guide](https://github.com/ExxonMobil/cicd-enablement/discussions/114) to set up Yubikeys for your account. 🟡

The `@xomservices.com` account should be added to the following AzureAD groups:

- [`CI-CD.ENABLEMENT.XOMSERVICES`](https://portal.azure.com/#blade/Microsoft_AAD_IAM/GroupDetailsMenuBlade/Members/groupId/0fb2426f-cb2f-40f5-8688-474503e4cefa) ✅

## Terraform Enterprise

- [Workspaces | ExxonMobil-DEV | Terraform Enterprise DEV](https://tfedev.xom.cloud/app/ExxonMobil-DEV/workspaces) 🟤
  - Using your `@exxonmobil.com` account: you should be able to access, create workspace, and impersonate tfeadmin
- [Workspaces | ExxonMobil-Sandbox | Terraform Enterprise](https://sandbox.terraform.xom.cloud/app/ExxonMobil-Sandbox/workspaces) 🟤
  - you should have the same permission as dev
- [Workspaces | ExxonMobil | Terraform Enterprise](https://terraform.xom.cloud/app/ExxonMobil/workspaces) 🟤
  - Using your `@exxonmobil.com` account: you should be able to access and see CICD's workspaces only but cannot create workspaces
  - Using your `@xomservices.com` account: you should be able to see all workspaces (workspace-admin) and impersonate tfeadmin

## OpenShift
`ON-PREMISE`

### OpenShift 4

- [cicd-dev - ARO N01](https://console-openshift-console.apps.aro-n01.xomres.cloud/project-details/ns/cicd-dev) ✅
- [cicd-dev - OCP4 HN](https://console-openshift-console.apps.hn.ocp.na.xom.com/project-details/ns/cicd-dev) ✅

Make sure you're added to `CI-CD.ENABLEMENT.UG` and `OCP.SSO.USERS.UG` (required for OCP4).

## Others

- [Pluralsight](https://app.pluralsight.com/sso/exxonmobil) - for self-paced online training ✅
  - check out [How to request Pluralsight](https://itcc.xom.cloud/welcome-pluralsight/)
- [Team calendar](https://www.teamcalendar.xom.cloud/calendar) - to see other's whereabout
  - you should see the following calendar:
  - `CICD ENABLEMENT TEAM` - contact @thasasuwan to add you in ✅
  - `DDS BKK TEAM TEAM` - contact Sira to add you in - Bangkok team member only ✅

## ITPA ✅
`ON-PREMISE` `GME-ONLY` `EMPLOYEE-ONLY`

1. Install and setup `Passcode` from the Software Center
2. Input `secureauth.na.xom.com` into the address field
3. Contact ITHelp to get OTP and setup a 4-digit PIN
4. [goto/ITPA](https://itpa.na.xom.com/PasswordVault) and choose `Step-Up Auth` and input OTP from the Passcode to log into ITPA
5. Search for `APPS_MAP_CICD` and you should see `xsCICDEnablement` and `xsCICDPipeline` which you can add it to your favourite.

![image](https://user-images.githubusercontent.com/24604485/148892757-b3d9b3c2-5bb0-4dc1-900b-ebfa9e0aba57.png)

If you can't see the `xsCICDEnablement` account, make sure you're added to `MAP-CICD-ITPA-USERS.UG`.

For `xsCICDPipeline`, the password is split into 2 half based on the groups below:
- `ITPA-SPLIT-HALF-1.UG` - Apinya, Kanrawee
- `ITPA-SPLIT-HALF-2.UG` - Poonnaphop, Prin, Thanida

# GME Setup

## Software

Check out [IT Self-Help - Request new software](https://emprod.service-now.com/itsp?id=kb_article&sys_id=e45509a397884910a0f79904a253afe5) on how to request software.

- Git for Windows v2.31.1 - Working with Git repositories
  - See [Git Config](#git-config) for configuration
- Azure CLI v2.25.0
  - Switch to Dallas VPN if failed to install
  - az login` (if problem, try to restart PC)
  - See [Azure CLI CA Certificates](#Azure-CLI-CA-Certificates) for configuration
- Terraform v0.14.10
  - `terraform version` (If not found then set PATH variable)
  -- add Terraform installation directory to your PATH variable: C:\Program Files (x86)\terraform-0.14.10
- OpenShift Command Line Tool v4.6.28
  - `oc version` (If not found then set PATH variable)
  -- add OpenShift installation directory to your PATH variable: C:\Program Files\Openshift-Client-Windows

## Git Config

Follow instruction on [GitHub Getting Started Guide | AppWiki](https://gotocloud.xom.cloud/cloudwiki/docs/DevOps/MigrateToGitHub.html#set-up-your-environment).

## Azure CLI CA Certificates

1. Download [all XOM self-signed certificates](https://ca-bundle.apps.hp.ocp.na.xom.com/xom_ca_bundle.pem).
2. Append all XOM self-signed certificate to `C:\Program Files (x86)\Microsoft SDKs\Azure\CLI2\Lib\site-packages\certifi\cacert.pem` (Contact ITChat to get temporary local admin if you cannot edit the file)

# MacBook Setup

The following links can give your some information about what to do to use MacBook with ExxonMobil environment:

- [MacBook enablement - Overview](https://dev.azure.com/EM-CIT/Portfolio-CDO/_wiki/wikis/Data%20Provisioning%20Program/3569/MacBook-enablement)
- [iOS Onboarding | Developer Wiki](https://wiki.ds.xom.cloud/books/ios-support/page/ios-onboarding#)

## Softwares

- VS Code
- iTerm 2 | Warp
- PowerShell (Core)
- Postman
- Azure CLI (`azure-cli`)
- Terraform CLI (`terraform`)
- Terraform Docs (`terraform-docs`)
- `vault`: HashiCorp Vault CLI
- `jq`: JSON Query
- `OPTIONAL` `tfenv`: Manage multiple version of Terraform
- `OPTIONAL` AWS CLI (`awscli`)
- `OPTIONAL` `act`: Run GitHub Actions locally