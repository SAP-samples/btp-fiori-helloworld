**Now you can test and preview the UI application in SAP Business Application Studio**

1. Right click on your project folder "helloworldui5" and choose **Preview Application**. 

<img src="/images/Preview_Application.png" width="750">

 

2. Choose npm script: **start-noflp fiori run --open "intex.html?sap-ui-xx-viewCache=false"**

<img src="/images/Start_noflp.png" width="750">



A new browser tab opens with your app:

<img src="/images/App_generated_new.png" width="750">

Now let us **change the title of the app** to "HelloWorld".

3. Go to **Explorer** in the left navigation pane.

4. Open folder "**webapp**" and subfolder **view** (in our example View1). Click on the page title inside the blue box. The element ID "page" will be selected.

5. Change "{i18n>title}" to "HelloWorld".

<img src="/images/App_title_TechEd_new.png" width="750">

You will see the changes in the application preview accordingly: "HelloWorld" instead of "Hello World App Title".

<img src="/images/App_new.png" width="750">
 

 

 
