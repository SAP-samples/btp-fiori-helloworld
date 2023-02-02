<sub>**Note:**
This step is only necessary for an Enterprise Account (e.g. pay-as-you-go Account with free-tier service plans)
SAP BTP Trial comes with preconfigured HTML5 application development.</sub>

 

## Run the Booster "Prepare an account for HTML5 application development"

### Prepare

As shown in the previous step:
1. Login to your global SAP BTP account.
2. Select Boosters in the account menu.
3. Select the Booster "Prepare an account for HTML5 application development"
4. Click "Start"


### Execute Booster

#### `Step 1 - "Check Prerequisites"`

As shown in the previous card, the Booster checks if you have all the entitlements and free quota that are needed to run the booster. 
If the step "Check Prerequisites" passes. Press "Next".

**Important**: Before proceeding to step 2, configuring the booster, please check in [SAP Discovery Center](https://discovery-center.cloud.sap/viewServices?showFilters=true&provider=all&regions=all) for which regions and providers the required services are available and which region and provider you like to choose. If you choose a region or provider, which does not offer the required service, the booster will skip the service.


#### `Step 2 - "Set Up Subaccount"`

1. In this step, you create the following entries to set up your subaccount. You will select:
    * Assign a Quota for your Cloud Foundry Runtime (At least 1 unit of your service plan).
    * Subaccount name (of your choice or keep the default)
    * Preferred Infrastructure Provider 
    * Region (e.g. "Frankfurt") 
    * Subdomain name (of your choice or keep the default)
    * Cloud Foundry Organisation name (of your choice or keep the default)
    * Space name (e.g. "dev", from the typical setup with "dev", "test" and "prod")

    <sub>Note: If you do not have set an entitlement for the Continuous Integration & Delivery service it will not appear in the list. 
you can delete it if you don't want to use it. It is optional for this mission.</sub>

<br>

![](images/booster_step2_1.png)

<br>

2. Press **"Next"**
 
<br>


#### `Step 3 - "Add users"`

In this step, we can add additional users as administrators and developers for the subaccount. The user who is using the Booster is added automatically as Administrator and also added as a Security Admin.

    * Add administrators
    * Add developers
    * Press Next.

<br>

![](images/booster_step3.png)

<br>

#### `Step 4 - "Review" `

You are nearly done. Review your configurations. 

<br>

![](images/Booster_step_4_progress.png)

<br>
If everything is correct press **"Finish"**.

The booster will start. Watch the progress screen, until it turns green for all setup steps.
When the Booster has executed successfully you will get a success window.
you can use the provided links to open your new subaccount and Business Application Studio.

<br>

![](images/booster_step_4_success.png)

<br>




