<sub>**Note:**
This step is only necessary for an Enterprise Account (e.g. pay-as-you-go Account with free-tier service plans)
SAP BTP Trial comes with preconfigured HTML5 application development.</sub>

 

### Run the Booster "Prepare an account for HTML5 application development"

**Prepare**

As shown in the previous step:
1. Login to your global SAP BTP account.
2. Select Boosters in the account menu.
3. Select the Booster "Prepare an account for HTML5 application development"
4. Click "Start"


**Execute Booster**

**Step 1 - "Check Prerequisites"**

As shown in the previous card, the Booster checks if you have all the entitlements and free quota that are needed to run the booster. 
If the step "Check Prerequisites" passes. Press "Next".


**Step 2 - "Set Up Subaccount"**

In this step, you provide all information to set up your subaccount in the right region (e.g. "Frankfurt") and service provider, with the right names. You will have to decide upon the same entities also in the manual setup.


Create the following entries:

Assign a Quota for your Cloud Foundry Runtime.

Note: If you do not have set an entitlement for the Continuous Integration & Delivery service it will not appear in the list. 
you can delete it if you don't want to use it. It is optional for this mission.

Set your subaccount name 

Select your preferred cloud infrastructure provider 

Select the region for this subaccount (important for the response time)

Set the subaccount ID  (you can keep the default)

Set the subaccount org name  (change it to a meaningful name)

Set a space name
typically DEV, TEST or PROD as a minimum. In general, it is recommended to have one space per project. You can later add further spaces for additional projects manually.
(see also best the practices guide Account Models with Subaccounts)

Press "Next"



**Step 3 - "Add users"**

In this step, we can add additional users as administrators and developers for the subaccount. The user who is using the Booster is added automatically as Administrator and also added as a Security Admin.

Add administrators
Add developers
Press Next.



**Step 4 - "Review" **

You are nearly done. Review your configuration, if everything is correct press finish.


Watch the progress screen, until it turns green for all setup steps.


When the Booster has executed successfully you will get a success window.
you can use the provided links to open your new subaccount and Business Application Studio.








