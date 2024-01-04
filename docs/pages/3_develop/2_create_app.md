
# Create an SAP Fiori Application with "Start from template"

**Procedure**

1. Click on **Start from template** in the Welcome tab to create the project.

   ![](images/ca1_startfromtemplate.png)

2. In the New Project Wizard select **SAP Fiori Application**. Click **Start**.

   ![](images/ca2_wizard1.png)

3. In the **Template Selection** keep template type "Fiori" and choose **Basic** 

   Choose **Next**.  

   ![](images/ca3_wizard2.png)

4. In the **Data Source and Service Selection** choose **None** for Data source, because you create a "Hello World" without data binding.

5. Choose **Next**.

   ![](images/ca4_datasource.png)

6. Under **Entity Selection** name your SAPUI5 view. 

   This name will appear in the launchpad service for the app. 

   Keep <code>"View1"</code> for now. 

   Choose **Next**

   ![](images/ca5_view1.png)


7. In the next step, **Project Attributes** choose names and a description for your "Hello World" app (examples see figure): 

   Module name <code>helloworldui5 </code>

   Application title <code>Hello World App Title </code>

   Application namespace <code>sap.btp </code>

   Description: <code>A Fiori Hello World application  </code>

   Keep **Project folder path** and **Minimum SAPUI5 version**.

   Add deployment configuration to MTA project <code>Yes </code>

   Add FLP configuration <code>Yes</code>

   Configure advanced options <code>No</code>

   Choose **Next**.
    
   ![](images/ca6_wizard5.png)

8. In the next step, **Deployment Configuration** choose **Cloud Foundry** as a target.

   Choose **None** for Destination Name. 
   
   Choose <strong>Add application to managed application router?</strong> <code>Yes</code> 

   (This is the standard html5 repository from the SAP Work Zone service and eases deployment). 

   Choose **Next**.

   ![](images/Deployment_Config.png)

9. The **SAP Build Work Zone** service needs some **Fiori Launchpad Configuration** data about the app. 

   Choose names for the entries Semantic Object, Action, and Title (examples see figure)
   
   Semantic Object: <code>helloworld </code>
   Action: <code>show </code><br>
   Title: <code>showhelloworld </code> <br>

   ![](images/ca8_wizard_flp.png)

10. Choose **Finish**. <br>
    **Note**: It will take some time until all dependencies are installed.

11. Click on **Open folder** or **add project to workspace** (note: the concept of workspaces is not part of this tutorial).

    ![](images/ca9_openfolder.png)

12. After your App is generated, you should see the "Storyboard" of your Fiori application and in the Explorer.

    Right click on the Fiori app and choose "Open Application Info".

    ![](images/ca10_apphome.png)

13. In the "Application Info" you can see additional details of your app and you can start from here additional tasks.

    ![](images/ca10_apphome_2_info.png)

14. Optional: Open your Projects folder via menu: File > Open Folder ... and enter "/home/user/projects".

    ![](images/ca11_open_folder.png)
 
15. Click **OK**.


