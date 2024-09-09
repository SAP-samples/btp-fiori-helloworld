# Setup SAP Build Work Zone Service in your Trial Account

SAP Build Work Zone enables you to easily build business sites that provide centralized access to applications, such as the hello world app you will create.

SAP Build Work Zone Service it not pre-configured in your BTP trial account. You first need to subscribe the service.




### Subscribe to the SAP Build Work Zone Service



1. Go to your trial subaccount, navigate to "Services" --> "Instances and Subscriptions" and choose "Create".

    ![](images/2_trial_wzone_01_create_service.png)

2. Select "SAP Build Work Zone, standard edition" as Service and select "Subscription" as service plan.

  ![](images/2_trial_wzone_02_create_wz.png)


3. The Subscription for SAP Build Work Zone will be created.

   ![](images/2_trial_wzone_03_pending.png)

4. Click on the Work Zone Subscription. A new window will open with "Access Denied".

    You need to add the missing Role Collection "Launchpad_Admin" to your user. 

    The required role collections have been already created with the subscription to the Launchpad Service.

5. Navigate in the left handed navigation pane of the BTP Cockpit to **Security --> Users**. Click on users.

    In a trial account you will basically see your own user. Click on your user. 

6. Click on "Assign Role Collection".

    ![](images/2_trial_wzone_04_asssign_rc.png)

7. Assign this Role Collections:

    - Launchpad_Admin

    Check that you have these Role Collections assigned:
    
    - Business_Application_Studio_Administrator
    - Business_Application_Studio_Developer

    Click "Save".

    ![](images/2_trial_wzone_05_add_rcs.png)

8. Go back to "Services" --> Instances and Subscriptions" and click "SAP Build Work Zone, standard edition" again. 

    The Work Zone Site Manager should open. 
    
    (In some cases the browser still caches the old authorizations. In this case close and restart the browser)

    ![](images/2_trial_wzone_06_enter_wz.png)

