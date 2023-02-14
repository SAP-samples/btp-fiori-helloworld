<sub>**Note:**
This step is only necessary for an Enterprise Account (e.g. pay-as-you-go Account with free-tier service plans)
SAP BTP Trial comes with preconfigured HTML5 application development. You can either run a "Booster" or set-up your services manually.</sub>

 

# Run Booster - Part 2

### Prepare

As shown in the previous steps:
1. Login to your global SAP BTP account.
2. Select Boosters in the account menu.
3. Select the Booster **"Prepare an account for HTML5 application development"**
4. Click "Start"


### Execute Booster

#### Step 1 - "Check Prerequisites"

As shown in the previous card, the Booster checks if you have all the entitlements and free quota that are needed to run the booster. 
If the step "Check Prerequisites" passes. Press "Next".


#### Step 2 - "Set Up Subaccount"

In this step, you create the following entries to set up your subaccount. You will select:

* Assign a Quota for your Cloud Foundry Runtime (At least 1 unit of your service plan).
* Subaccount name (of your choice or keep the default)
* Preferred Infrastructure Provider 
* Region (e.g. "Frankfurt") 
* Subdomain name (of your choice or keep the default)
* Cloud Foundry Organisation name (of your choice or keep the default)
* Space name (e.g. "dev", from the typical setup with "dev", "test" and "prod")

<sub>Note: If you do not have set an entitlement for the Continuous Integration & Delivery service it will not appear in the list.
You can delete it if you don't want to use it. It is optional for this mission.</sub>

Press **Next** when finished.

![](images/ea7_boosterstep2.png)






#### Step 3 - "Add users"

In this step, we can add additional users as administrators and developers for the subaccount. <br>
The user who is using the Booster is added automatically as Administrator and also added as a Security Admin.


* Add administrators
* Add developers

Press **Next**, when finished.

![](images/ea8_booster_step3.png)


#### Step 4 - "Review"

You are nearly done. Review your configurations, if everything is correct, press **"Finish"**. <br>
The booster will start. Watch the progress screen, until it turns green for all setup steps.

![](images/ea9_boosterstep4.png)

When the Booster has executed successfully you will get a success window. <br>
You can use the provided links to open your new subaccount and Business Application Studio.


![](images/ea10_boostersuccess.png)





