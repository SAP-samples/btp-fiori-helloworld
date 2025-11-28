

### Step 1 - Create a new and empty GitHub Repository 

In this tutorial, you will add the  Hello World UI5 project to Business Application Studio Source Control, commit and push the project and changes to a remote Git repository.

**Note:** To work with the Git view in SAP Business Application Studio, you need to store or cache credentials. This requires entrusting your credentials to SAP and a third party.

This step describes how to create a GitHub repository in which you can store the source code of your project. You need to have a user in a public GitHub to execute the steps below.


> **Note:**
> Create a new, fresh, and empty repository. Do not use an existing repository that already has commits. 
> Do not create a README.md file or anything else for the new repo (for example, your BAS project already contains a README.md file). 
> You would need to merge two commit histories before you can proceed, which you should only do if you are already pretty familiar with Git. 
> And the procedure to do so is not part of this mission.

<br>

**Procedure**

1. Open your GitHub home page.

2. Click on *New* in the **Repository** tab to create a new repository.

    ![Create Github Repo](images/5_0_1_gitrepo_new.png)
   
<br>

3. Enter a GitHub organization (can also be your user) and the name of the repository. 
    For example, `Gitorg/btp-helloworld-app`.  
    **Do not check the checkbox Initialize this repository with a README**.

5. Click on Create repository. 

    ![Create Github Repo](images//5_0_2_gitrepo_create.png)

<br>

5. **Do not create any files.**
   Copy the GitHub URL of the newly created Git repository.

    ![Copy GitHub URL](images/5_0_3_gitrepo_result.png)

<br>


### Step 2 - Generate a Personal Access Token   

This step might be necessary if your GitHub repository does not accept a Git password.
  
In this mission, you will connect to a public GitHub Repository using **basic authentication** with GitHub **Personal Access Token (PAT)**.

**Procedure**  
  
You can create a PAT in GitHub following these [instructions (external link)](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). Other Git providers will have different ways of creating PATs.


**Note:** SAP Business Application Studio can connect to on-premises Git repositories or public Git repositories using Cloud Connector. 
Connecting to on-premises repositories is not part of this mission (see [Connecting to a Corporate Git Repository](https://help.sap.com/docs/SAP%20Business%20Application%20Studio/9d1db9835307451daa8c930fbd9ab264/d54ddfc1bc4f45b19dabfa0950799685.html?locale=en-US) on SAP Help Portal).
 




