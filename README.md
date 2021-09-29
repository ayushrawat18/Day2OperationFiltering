This store app will let you filter the 'Cloud Resource Operation' in ServiceNow.

App Name : Resource operation filtering

Pre-requisite
  1)	CMP plugin activated.
  2)	To make this application work ServiceNow instance should be on Orlando Patch 3 onwards.

What did this store app do?
The app will allow user to filter the resource operation based on available filters. After installing the application, user can navigate to ‘sn_cpg_filter_operations’ table. This application will also allow user to rename the day2opreation name.

The User can make use of the available OOB filters - 
 1.	Datacenter Types (AWS, Azure, VMware, GCP)
 2.	CI attributes (State, Name)
 3.	Custom script (Script will run at the runtime and perform the action, this can be used for complex filtering structures like showing the operation based on roles, timing etc.)

Steps to filter the resource operations :
 1.	 Navigate ‘sn_cpg_filter_operations’ table. 
 2.	Click on ‘New’ button – Provide the ‘Display Name’, CI Type and select the ‘Resource Operation’.
 3.	Choose the Filter Type.
 4.	In user portal for a selected CI only ‘filtered’ operation will be shown.

