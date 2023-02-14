
# Create an SAP Fiori Application with "Start from template"

**Procedure**

1. Click on **Start from template** in the Welcome tab to create the project.

     ![](images/ca1_startfromtemplate.png)

2. In the New Project Wizard select **SAP Fiori Application**. Click **Start**.

   ![](images/ca2_wizard1.png)

3. In the **Floorplan Selection** choose the following: <br>
   For the field **Application Type** choose **SAPUI5 freestyle** from the drop-down. <br>
   Select **SAPUI5 Application** as floorplan. <br>
   Choose **Next**.  <br>

    ![](images/ca3_wizard2.png)

4. In the **Data Source and Service Selection** choose **None** for Data source, because you create a "Hello World" without data binding.

5. Choose **Next**.

    ![](images/ca4_datasource.png)

6. Under **Entity Selection** name your SAPUI5 view.  <br>
   This name will appear in the launchpad service for the app.  <br>
   We keep <code>"View1"</code> for now. <br>
   Choose **Next**

    ![](images/ca5_view1.png)


7. In the next step, **Project Attributes** choose names and a description for your "Hello World" app (examples see figure): <br>
   Module name <code>helloworldui5 </code><br>
   Application title <code>Hello World App Title </code><br>
   Application namespace <code>sap.btp </code><br>
   Description: <code>A Fiori Hello World application  </code><br>

   **Project folder path** and **Minimum SAPUI5 version** must not be changed in this tutorial.

   Add deployment configuration to MTA project <code>Yes </code><br>
   Add FLP configuration <code>Yes</code><br>
   Configure advanced options <code>No</code><br>

   Choose **Next**.
    
    ![](images/ca6_wizard5.png)

8. In the next step, **Deployment Configuration** choose **Cloud Foundry** as a target. <br>
   Choose **None** for Destination Name. <br>
   Choose <strong>Add application to managed application router?</strong> <code>Yes</code> 
   (This is the standard html5 repository from launchpad service and eases deployment). <br>

   Choose **Next**.

     ![](images/Deployment_Config.png)

9. The **SAP Build Work Zone** service needs some **Fiori Launchpad Configuration** data about the app. <br>
   Choose names for the entries Semantic Object, Action, and Title (examples see figure) <br>
   
   Semantic Object: <code>helloworld </code><br>
   Action: <code>show </code><br>
   Title: <code>showhelloworld </code> <br>

   ![](images/ca8_wizard_flp.png)

10. Choose **Finish**. <br>
    **Note**: It will take some time until all dependencies are installed.

11. Click on **Open folder** or **add project to workspace** (note: the concept of workspaces is not part of this tutorial).

     ![](images/ca9_openfolder.png)

12. After your App is generated, you should see this page and in the Explorer a new folder "helloworldui5" under HOME. <br />

     ![](images/ca10_apphome.png)

13. Open your Projects folder via menu: File > Open Folder ... and enter "/home/user/projects". <br />

     ![](images/ca11_open_folder.png)
 
14. Click **OK**.


