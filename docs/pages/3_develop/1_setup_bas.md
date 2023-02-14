
# Set-up SAP Business Application Studio

### Preparation

1. Click Instances and Subscriptions under Services

2. Select the tab Subscriptions, and click on SAP Business Application Studio. You will be forwarded to your SAP Business Application Studio Home Page with automatic login to the application.

   ![](images/app1_openbas.png)

3. Please, accept the Privacy Statement

4. Optional: Discover the SAP Business Application Studio home page.

   ![](images/app2_bashome.png)


### Create a Dev Space in SAP Business Application Studio

1. Click on **Create Dev Space** on the SAP Business Application Studio home page.

   ![](images/app3_createdevspace.png)

2. Provide a name of your choice for the Dev Space (for example, "devfiori") in the upper left corner. <br>
   Select the application type **SAP Fiori**. <br>
   Do not select any additional SAP Extensions here. 
   
   ![](images/app4_createdev2.png)

3. Click again **Create Dev Space** in the lower right corner. <br>
   You will be forwarded to an overview of your dev space(s). <br>
   It may take some time until the newly created dev space is started. <br>
   Once started the status changes from "STARTING" to "RUNNING” and the dev space name (in this case "devdemo") will turn into a blue hyperlink.
   
   ![](images/app5_startdevspace.png)

4. Click on the dev space link (e.g. "devfiori") to enter the space.

   After a few seconds ... you will see the **Get Started** page of your dev space. <br>
   You can always get it back under Help --> Get Started.

    ![](images/app6_initialbas.png)



### Connect your SAP Business Application Studio with your Cloud Foundry Environment

You need a connection from your Dev Space to your Cloud Foundry subaccount to deploy your application into the HTML5 Repository of your Subaccount. 

1. Switch back to your SAP BTP cockpit and click on Overview of your subaccount (top left).

2. Check the **API Endpoint** and **Org Name** and your **Space**. Keep the page open or note the values.

    ![](images/app7_api_endpoint.png)
 

**Procedure for Connecting**

1. Switchback to SAP Business Application Studio. In the tabs, click on View in the menu and select Command Palette ... .

   ![](images/app8_command_palette.png)

2. Search or Select CF: Login to Cloud Foundry.

   ![](images/app9_logincf.png)
 
3. Enter your Cloud Foundry API endpoint. <br>
   (Note: when you copy&paste the API endpoint from the cockpit, make sure to remove spaces at the beginning or end of the URL).

4. Enter your SAP BTP account Email and Password when prompted. 

   ![](images/app10_enter_email.png)

5. Select your Cloud Foundry Org (predefined).

6. Select the Space name (predefined).

   ![](images/app11_cftarget.png)



**Result**

Now we have successfully created a connection between your SAP Business Application dev space and your SAP BTP Cloud Foundry space.
 


 
