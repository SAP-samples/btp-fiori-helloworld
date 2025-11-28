# Prerequisites for setting up SAP Build Work Zone in BTP Account

SAP Build Work Zone enables you to easily create business sites that provide centralized access to applications, such as the Hello World app you will create.

SAP Build Work Zone Service is not pre-configured in your BTP trial account. You must first subscribe to the service.

In order to set up SAP Build Work Zone in your Enterprise or Trial Account, you first need to establish Trust and Federation between SAP Authorization and Trust Management Service and SAP Cloud Identity Services.

You use your SAP Cloud Identity Services tenant as an identity provider or a proxy for your own identity provider, which hosts your business users.

For more information, see [SAP Help Portal](https://help.sap.com/docs/btp/sap-business-technology-platform/establish-trust-and-federation-between-uaa-and-identity-authentication?locale=en-US) (external link.


### Set up Cloud Identity Services

Navigate to Instances and Subscriptions in your subaccount. Check if you have already set up a Cloud Identity Service. If not, create one. It is mandatory to use SAP Build Work Zone.

1. First, check your entitlement in your Global Account. Go to your Subaccount (trial) and navigate to "Entitlements". Search for "Cloud Identity Services". If it is present, you can set it up.

    ![](images/2_trial_trust_01_entitlecheck.png)

2. To set it up, navigate to "Service Marketplace." Repeat the Search and click "Cloud Identity Services."

    ![](images/2_trial_trust_02_servicemarketp.png)

3. In the detail view, click "Create".

    ![](images/2_trial_trust_03_servicemarketp.png)

4. The pop-up wizard will start. Step 1: Choose the "Service Plan "default.

    ![](images/2_trial_trust_04_cisstep1.png)

5. Step 2: Choose service type "TEST" (except if you are in a productive environment).

    ![](images/2_trial_trust_05_cisstep2.png)

6. Step 3: Review your settings and choose "Create". 

   ![](images/2_trial_trust_06_cisstep3.png)

7. Navigate to Instances and Subscriptions. The Cloud Identity Service should be subscribed to and run. Before you click on your service, you have to activate your account first.

   ![](images/2_trial_trust_07_cis_created.png)

8. You will receive an email for your subaccount admin email address.

    Press "Click here to activate your account".

   ![](images/2_trial_trust_08_cis_email.png)

9. You will be forwarded to an activation dialog. Provide a password for your newly created admin user in your Cloud Identity Service.

    ![](images/2_trial_trust_09_cis_activate.png)

10. You will receive an activation notice.

     ![](images/2_trial_trust_10_cis_activated.png)

11. You can click on your Cloud Identity Service in Instances and Subscriptions. You will probably have to authenticate yourself.

     ![](images/2_trial_trust_12_cis_signin.png)

     If you work with more than one CI service, you might receive an error. Log off and log in again, or close your browser and reopen it.

     ![](images/2_trial_trust_13_cis_signin.png)

12. Your Trial Cloud Identity Services Trial Account will open.
 
     Feel free to review your account and explore the available options. For the basic setup, you are done.

     ![](images/2_trial_trust_11_cis_admin.png)


### Establish Trust in BTP Trial

If you create an SAP Build Work Zone service in your Account now, you will fail. First, you have to establish trust between your Subaccount and your Cloud Identity Service.

![](images/2_trial_trust_20_subfailed.png)

1. In your subaccount, navigate to "Security" --> "Trust Configuration". If you do not have a Custom Identity Provider for your business users yet, click "Establish Trust." A pop-up wizard opens.

    ![](images/2_trial_trust_21_establish.png)

2. Step 1: Choose a tenant for your Cloud Identity Services (in a trial environment, you usually have just one).

    ![](images/2_trial_trust_22_step1.png)

3. Step 2: Choose a domain for your custom identity provider. 

    ![](images/2_trial_trust_23_step2.png)

4. Step 3: Configure your settings for your tenant. E.g., as shown in the figure.

    ![](images/2_trial_trust_24_step3.png)

5. Review your settings a click create. Your Custom Identity Provider for your Applications will be created.

    ![](images/2_trial_trust_25_new_cip.png)

6. Go to "Security" --> "Users" and check your user(s), which are managed by the Custom Identity and Authentication tenant.

    ![](images/2_trial_trust_26_newuser.png)

You have now established trust, and you can now create a SAP Build Work Zone subscription.
