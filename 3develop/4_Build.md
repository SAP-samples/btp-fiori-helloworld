**Build and deploy your HelloWorld the cloud application which you just created**
1. Go back to your browser window or tab "SAP Business Application Studio" and in case open again the **Explorer** (the pages icon on the top left)&nbsp;
  
     ![](../images/Explorer.png)
  
2. Open the <em>xs-app.json</em> and <em>xs-security.json</em> file.<br />You see that you did not define "scopes", no "role-templates" and "role-collections". Meaning with that configuration every authorized user will have access to the app. 
<br /> <br />  
  
     ![](../images/xs_app.png)
 
3. Let's build your application in SAP Business Application Studio. 
Right-click on the <strong>mta.yaml</strong> file and choose <strong>Build MTA project</strong>. With this a folder "mta_archives" and a mtar file is created.

     ![](../images/Build_MTA.png)

You will get the following INFO Message:
<code>INFO the MTA archive generated at: /home/user/projects/helloworldui5/mta_archives/sap-btp-helloworldui5_0.0.1.mtar</code>
  
**Alternative**: Build your application via the command line 
Right-click on the <strong>mta.yaml</strong> file and choose <strong>Open in Terminal</strong>
Type "dir" in the console to show the files in the directory. check if the <em>mta.yaml</em> file is available.
Type command 'mbt build'.

For more details, see section <a href="https://help.sap.com/docs/SAP%20Business%20Application%20Studio/9d1db9835307451daa8c930fbd9ab264/97ef204c568c4496917139cee61224a6.html" target="true" rel="noopener">Building and Deploying Multitarget Applications on SAP Help Portal.</a>

4. Deploy the HelloWorld application to your SAP BTP dev space. <br />Make sure you are logged in to your SAP BTP subaccount (described under step "Prepare your SAP Business Application Studio").
Expand the project folder <strong>mta_archives</strong>and right-click on the built file&nbsp;<strong>sap-btp-hellowordlui5_0.0.1.mtar</strong>&nbsp;and select&nbsp;<strong>Deploy MTA Archive</strong>.
  
     ![](../images/Deploy_mta.png")  

Your trail subaccount will be selected automatically as destination.<br /><br />
5. After the deployment is triggered, you can see the progress of the deployment in the terminal under <strong>Task: Deploy MTA Archive</strong>. <br />It takes a while to complete the task. You will see a success message in the console once it's done. <br />If not, check the previous steps again.<br /><br />
  
     ![](../images/Terminal.png)
  
6. Switch to your <strong>subaccount </strong>in the SAP BTP Cockpit<strong>. <br /></strong>Select<strong> HTML5 Application </strong>on the left navigation pane. You will see the deployed application in the repository.<br /><br />
<img src="/images/HTML5_app.png" width="750">
  

Click on the application name "<strong>saphelloworldui5</strong>". Your deployed app will open in a new window.

     ![](../images/App_new.png)

