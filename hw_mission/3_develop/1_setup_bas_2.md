## Connect your SAP Business Application Studio with your Cloud Foundry Environment

A connection of your SAP Business Application Studio to your Cloud Foundry subaccount is necessary if you want to deploy your application into your SAP BTP subaccount html5 repository and make it available. 

</br>
</br>

**Preparation Steps** 

1. Switch to the SAP BTP cockpit and click on Overview of your subaccount (top left).
2. Check the **API Endpoint** and **Org Name** and your **Space**.

 ![](images/API_Endpoint.png)
 

**Keep this information in mind** for the next steps (this is especially important if you want to use multiple subaccounts for your SAP Business Application Studio).

</br>
</br>

**Procedure for Connecting**

1. Switch to the tab where you have opened SAP Business Application Studio. In the tabs, click on View in the menu and select Command Palette ... .

   ![](images/Command_Palette.png)

2. Search or Select CF: Login to Cloud Foundry.

   ![](images/Login_CF.png)
 
3. Ensure that the right cloud foundry API endpoint is entered (attention: when you copy&paste the API endpoint from the cockpit, make sure to remove spaces at the beginning or end of the URL).

4. Enter your SAP BTP account Email and Password when prompted. 

   ![](images/Enter_email.png)

</br>

5. Select your Cloud Foundry Org (predefined).

6. Select the Space name (predefined).

   ![](images/CF_Target.png)

   ![](images/Logged_in.png)


</br>
</br>

**Result**

Now we have successfully created a connection between your SAP Business Application dev space and your SAP BTP Cloud Foundry space.
 

