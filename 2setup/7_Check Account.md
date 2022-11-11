<p ="text-align: left;"><strong>Check your created Subaccount </strong></p>
<p>Go back to your SAP BTP Cockpit by clicking on the browser tab "Trial Home ..."</p>
<p>In your new subaccount check the following:<br /><br /></p>
<ol>
<li>Click&nbsp;<strong>Instances and Subscriptions&nbsp;</strong>under&nbsp;<strong>Services</strong> <strong>&nbsp;</strong>(#1 on the following figure). You should see that the following services have been subscribed:<br /><br />
<ul>
<li>SAP Business Application Studio</li>
<li>Launchpad Service<br /><br /></li>
</ul>
</li>
<li>Click on "SAP Business Application Studio" (#4 on the figure). This will open SAP Business Application Studio.<br /><br /></li>
<li>Click on "Launchpad Service". This will open the launchpad site directory.<br /><br />If you get the error message "Access Denied". Your user has not been assigned the role collection "Launchpad_Admin". See card "Add yourself to the Launchpad Admin role".<br />Goto "Role Collections", click on "<strong>Launchpad_Admin</strong>" and assign the email address of your user</li>
</ol>
<p>&nbsp;</p>
<p><img src="/images/steps.png" width="1097" height="357" /><br /><strong>Additional Checks</strong><br /><br />Cloud Foundry - "Org Members" (#2 on the figure):<br />It will list all users you have added as administrators with the "Org Manager" role. Users you have added as developers have no Organization Role.</p>
<p>Security - "Users" (#3 on the figure):<br />You should see all users assigned to the subaccount. A click on the arrow adds details, including their role collections.</p>
<p>&nbsp;</p>
