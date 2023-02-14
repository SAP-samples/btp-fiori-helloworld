# Prepare your Application for Build Work Zone Service


You can add your Hello World application to a Launchpad Site. For more information, have a look at section [Expose HTML5 Applications in Launchpad](https://help.sap.com/viewer/ad4b9f0b14b0458cad9bd27bf435637d/Cloud/en-US/3a0e6d6b791c4c2189f6a0a424188362.html) on SAP Help Portal.

<br>


### Configure your HTML5 Application for Build Work Zone

To make your HTML5 applications visible to the Launchpad application, you have to check some information in the **webapp/manifest.json** file. 

This information was added by the **Create Project from Template** wizard, if you have chosen **Yes** to add **Fiori Launchpad Configuration** and <strong>Yes</strong> to **Add to Managed Application Router**.

The HTML5 application must be deployed to the same subaccount of the SAP Build Work Zone service.

**Procedure**

1. Open the Workspace containing your HTML5 HelloWorld project in SAP Business Application Studio.</p>

2. Expand your HTML5 project under the folder **helloworldui5 --> webapp**. <br>
   Open the **manifest.json** file.

3. To ensure that the data of the extension application is displayed correctly on the SAP Launchpad site, check the value of **sap.cloud** in webapp/manifest.json file.

    ```
    "sap.cloud": {
            "public": true,
            "service": "sap-btp-helloworldui5"
        }
   ```

    If you made any changes to your project, re-build and deploy the application as described in the previous step. <br>
    If you did not make any changes just continue with the next step.




