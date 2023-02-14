## Build and Deploy your Application in Cloud Foundry Runtime

**Procedure**

1. Go back to your browser window or tab "SAP Business Application Studio" and in case open again the **Explorer** (the pages icon on the top left)&nbsp;
  
     ![](images/bad1_explorer.png)

2. Open the <em>xs-app.json</em> and <em>xs-security.json</em> file. <br />
   You see that you did not define "scopes", no "role-templates" and no "role-collections". <br>
   Means with that configuration every authorized user will have access to the app. 
  
     ![](images/bad2_xs_app.png)
 
3. Build your application in SAP Business Application Studio. <br>
    Right-click on the **mta.yaml** file and choose **Build MTA project**. <br>
    With this a folder "mta_archives" and a mtar file is created.

    ![](images/bad3_buildmta.png)

    You will get the following INFO Message:

    ``INFO the MTA archive generated at: /home/user/projects/helloworldui5/mta_archives/sap-btp-helloworldui5_0.0.1.mtar``
  
    > **Alternative**: Build your application via the command line <br>
    > Right-click on the <strong>mta.yaml</strong> file and choose <strong>Open in Terminal</strong>
    > Type "dir" in the console to show the files in the directory. <br>
    > check if the <em>mta.yaml</em> file is available. Type command ``'mbt build'``.

    For more details, see [Building and Deploying Multitarget Applications](https://help.sap.com/docs/SAP%20Business%20Application%20Studio/9d1db9835307451daa8c930fbd9ab264/97ef204c568c4496917139cee61224a6.html?locale=en-US) on SAP Help Portal. <br>

4. Deploy the HelloWorld application to your SAP BTP dev space. 

    Make sure you are logged in to your SAP BTP subaccount (described under step "Prepare your SAP Business Application Studio"). <br>
    Expand the project folder **mta_archives** and right-click on the built file **sap-btp-hellowordlui5_0.0.1.mtar** and select **Deploy MTA Archive**.
  
    ![](images/bad4_deploymta.png)  

    Your trail subaccount will be selected automatically as destination.<br /><br />
    
    
5. After the deployment is triggered, you can see the progress of the deployment in the terminal under **Task: Deploy MTA Archive**. 

    It takes a while to complete the task. You will see a success message in the console once it's done. <br />
    If not, check the previous steps again.<br />
  
    ![](images/bad5_terminal.png)

  
6. Switch to your **subaccount </strong>in the SAP BTP Cockpit**. <br>   
   Select **HTML5 Application** on the left navigation pane.  <br>
   You will see the deployed application in the repository. <br>
   Click on the application name "**saphelloworldui5**. Your deployed app will open in a new window.

   ![](images/bad5_html5.png)





