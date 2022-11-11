
**Create an SAP Fiori Application with "Start from template"**


<ol> 
<li>Click on <strong>Start from template</strong> in the Welcome tab to create the project.</li> <br />
Alternative: Open the menu in the top left corner and go to <strong>View > Command Palette ...</strong> and search for ">new project". Select the command <strong>SAP Business Application Studio: New Project from Template</strong><br />

<img src="/exercises/images/BAS_start.png" width="750"><br />

<li>In the New Project Wizard select **SAP Fiori Application**.</li><br />

Click <strong>Start</strong>.

<img src="/exercises/images/Template_Fiori_app.png" width="750"><br />


<li>In the <strong>Floorplan Selection</strong> choose the following:</li>

For the field <strong>Application Type</strong> choose <strong>SAPUI5 freestyle</strong> from the drop-down.
Select <strong>SAPUI5 Application</strong> as floorplan.

Choose <strong>Next</strong>.

<img src="/exercises/images/Template_UI5.png" width="750"><br />


<li>In the <strong>Data Source and Service Selection</strong> choose <strong>None</strong> for Data source, because we just create a "Hello World" without data binding.</li>

<li>Choose <strong>Next</strong>.</li>

<img src="/exercises/images/Data_Source.png" width="750"><br />


<li>Under <strong>Entity Selection</strong> name your SAPUI5 view. This name will appear in the launchpad service for the app. We keep <code>"View1"</code> for now</li><br />

Choose <strong>Next</strong>

<img src="/exercises/images/View1.png" width="750"><br />

<li>In the next step, <strong>Project Attributes</strong> choose names and a description for your "Hello World" app (examples see figure):</li><br />

Module name <code>helloworldui5 </code><br>
Application title <code>Hello World App Title </code><br>
Application namespace <code>sap.btp </code><br>
Description: <code>A Fiori Hello World application  </code><br>

<strong>Project folder path</strong> and <strong>Minimum SAPUI5 version</strong> should not be changed

Add deployment configuration to MTA project <code>Yes </code><br>
Add FLP configuration <code>Yes</code><br>
Configure advanced options <code>No</code><br>

Choose <strong>Next</strong>.

<img src="/exercises/images/Template_Project_Attributes.png" width="750"><br />

<li>In the next step, <strong>Deployment Configuration</strong> choose <strong>Cloud Foundry</strong> as a target.</li><br />

Choose <code>None</code> for Destination name.

Choose <strong>Add application to managed application router?</strong> <code>Yes</code>.
This is the standard html5 repository from launchpad service and eases deployment.

Choose <strong>Next</strong>

<img src="/exercises/images/Deployment_Config.png" width="750"><br />

<li>The launchpad service needs some Fiori Launchpad Configuration data about the app. Choose names for the entries Semantic Object, Action, and Title (examples see figure)</li><br />
(Optional: For more information about these data and features, see Intent-Based Navigation in a Nutshell).<br /><br />

Semantic Object: <code>helloworld </code><br>
Action: <code>show </code><br>
Title: <code>showhelloworld </code> <br>

<img src="/exercises/images/Fiori_Launchpad_config.png" width="750"><br />

<li>Choose <strong>Finish</strong></li><br />

*Note*, that it may take some time until all dependencies are installed.

<li>Click on <strong>Add Project to Workspace</strong></li><br />

<img src="/exercises/images/Workspace.png" width="750"><br />

<li>After your App is generated, you should see this page and in the Explorer a new folder "helloworldui5" under HOME.</li><br />

<img src="/exercises/images/BAS_Project_App_Info.png" width="750"><br />

<li>Open your Projects folder via menu: File > Open Folder ... and enter "/home/user/projects".</li><br />

<img src="/exercises/images/Open_Projects_folder.png" width="750"><br />
 
<li>Click <strong>OK</strong>.</li>

</ol> 
