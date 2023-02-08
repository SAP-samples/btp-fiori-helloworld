## Create a Hello World Project with Git Source Control

SAP Business Application Studio (BAS) enables you to connect and interact with the **Git source control** system, letting you connect and interact with **remote Git repositories**.
Using SAP Business Application Studio, you can connect to all public git services, such as GitHub, GitLab, and BitBucket.


#### Prerequisites

In this mission you will connect to a public GitHub Repository using **basic authentication** with GitHub **Personal Access Token (PAT)**.
You can create a PAT in GitHub following these [instructions (external link)](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). Other Git providers will have different ways of creating PATs.

**Note:** To work with the Git view in SAP Business Application Studio, you need to store or cache credentials. Doing this requires you to entrust your credentials to SAP and to a third party.

**Note:** SAP Business Application Studio can connect to on premise Git repositories or public Git repositories using Cloud Connector. 
Connecting to on premise repositories is not part of this mission (see [Connecting to a Corporate Git Repository](https://help.sap.com/docs/SAP%20Business%20Application%20Studio/9d1db9835307451daa8c930fbd9ab264/d54ddfc1bc4f45b19dabfa0950799685.html?locale=en-US) on SAP Help Portal).

<br>

#### Two different ways to add a Git Remote Repository

you can either add a **Remote Repository** to an existing project (recommended for this tutorial) or you can **Clone a Repository** from GitHub. However cloning needs some additional configuration in CI/CD service.
