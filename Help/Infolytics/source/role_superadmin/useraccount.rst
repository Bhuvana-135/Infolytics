.. role_superadmin\useraccount:

User Account
==========================

.. include:: ../../common/stub-overview.txt

.. |Search| image:: images/searchicon.jpg

A user can login and use the application only if his account exists in the application. A Super Admin can create a new user and update account details that includes -  Account Details , Personal Details, Network Multisite, Responsibilities, Reportees, Configure DND, External Credentials, Certificates, Device Registrations,  Add Email ID and  Issued OTP's.

Add  New User
----------------------------

To add new user account:

* On the Home page, open the Manage menu drop-down, select Users and click New Users to view the form on screen. 
* Type in the First, Last name, Email Id and a valid Mobile number in respective text boxes and click Save. 

The new user will be listed under **All Users** of **Manage**, **Users** menu.

.. Note:: *Please enter a valid E-mail Id as this could be the users login Id*.

 Account Details
--------------------------------

Update user account details to set-up a new password.

* Open the User Account from Manage, Users menu, select Modify to edit the User details form
* Go to Account details tab, the Email Id is taken as Login Id by default and the account is marked as **Is Active**.
* A super user can access all the features of the application, select the Super User check box to assign user with the role.
* Authentication of users can be done by comparing login credentials of user with details provided in the database. Select the Enable Multi Factor Authentication checkbox to check user credentials every time the user logs into the application. 
* Enter a Password and re-type the same password in respective text boxes. Now, a new password will be set-up for your user account. 
* In case you forget your password, system can authenticate you using the question and answer that is provided. Type in an appropriate Question and Answer in the text boxes. 

Personal Details
--------------------------------

To add personal and company details of the user:

* Every account is configured with a preferred locale, default value indicates the current browser locale. 
* Add your personal details, designation and mobile number in respective text boxes.
* Choose your skill level either Basic, Average or Expert and select the currency of the country you reside. 
* Attach certificates you have acquired and a brief description about yourself. 
* Select Company name, Department and Business unit the person belongs to.
* Include additional details of the company. 
* Enter a key to access the network and select a date until when it is valid. 
* Configure biometrics by associating a biometric Id for the user. 

Network, Multisite
--------------------------------
To add access details for the network and site  

* Go to the Network tab, enter an access network key and select a date from the calendar until when it is valid. 
* Select the Enable for Dynamic Access checkbox to  allow users to access the application online.
* Under Biometric details section, associate or view a biometric Id  for the user. 
* Select Multisite tab. Click |Search| of Location, choose a location where the user can access the application and click Add.

Responsibilities, Reportees
--------------------------------

User can view current responsibilities and add new responsibilities:

* Go to Responsibilities tab to view responsibilities already associated to the user. 
* Select Add Role Templates, click |Search|, choose a Role you want to associate to the user and click Add. 
* Selected responsibilities will appear under the Existing tab and click Finish. All the new responsibilities will be associated to the user. 
* If user is a Manager, then all the users reporting to him will be listed under the Reportees tab.

DND
-----------------------------

User can create and manage Do Not Disturb (DND's) for Alerts, Email's and SMS's for the current user. 

To add DND for an Alert: 

* On the DND form, Go to DND's Alert section, click Create DND. A Create DND - for Alert form on screen.
* Add an alert template, click |Search| of Alert Template, choose a template from the list and click Add.
* Enter Mobile number and Email Id of the user for whom the DND is being created and click Save. The Alerts will be blocked for this user. 

To add DND for an Email Account: 

* Go to DND's Email section, click Create DND to open a Create DND - for Alert form on screen.
* To attach an Email template, choose a template from the list and click Add. 
* Enter Mobile number and Email Id of the user for whom the DND is being created and click Save. Email's will be blocked for this user. 

To add DND for SMS's: 

* Go to DND's SMS's section, click Create DND to open a Create DND - for SMS form on screen.
* To attach an SMS template, choose a template from the list and click Add. 
* Enter Mobile number and Email Id of the user for whom the DND is being created and click Save. SMS's will be blocked for this user. 

External Credentials
--------------------------------

External Authentications or SSO (Single Sign-on ) generally used by Corporates, is a method to access control that enables user to log in once and gain access to multiple software systems without being prompted to login again. 

User can add other credentials and map login credentials to external system.				
To upload new credentials:

* In the Account Setting section of the screen, navigate to Connectivity Settings section of the form.  
* Click External Authentications. An External Credential Details form is open on screen. Click Modify to Edit the form details for new changes.
* In the External Credential Details section of the form, enter Provider Name and Provider User Name and ProviderUser Id in respective text box. 
* Choose a date in the |Calendar| icon, select a date when it was Last Used On. Click Save and Close to store the form details on screen. The new provider details will be listed for the user. 
* User credentials can be mapped to external sources like Microsoft windows, Google, Facebook, LinkedIn. 
* To map user to these systems, In the External Credential Details form, click Map Credentials. List of sources is open on screen. Choose source for which you want to add your credentials. System is redirected to the source login page for respective user. 
* Provide your login credentials (user name and password) for respective source and click Login.
* Once the source is mapped to user's user account, user need not re-enter password or login credentials to access the external source. 

Certificates
--------------------------------

New certificates can be uploaded for the user.  To add a new user certificates:

* In the Details section of the form, enter name of the new certificate. The current date is populated in Created on text box.
* Drag-drop file in the Certificate attachment section of the form or click Browse to add a certificate file from the list, click Add.
* Save and Close the form.  A new certificate will be added to the list of Certificates. 

Device Registrations
-------------------------------- 

The application can be accessed on mobiles for which user has to be configured for the device. 

To add application for mobile access:

* In the Account Setting form, Connectivity section, select Mobile Devices, click Add Device. A new mobile device form is open on screen.
* Enter the device details i.e., Device Id, Push Token number that is available on the device. Provide detail about the Platform and the Version on which the device is workingin respective text boxes. 
* Choose Enable check box to configure device for mobility. Select Save and Close the form. The mobile device details will be listed on screen.		

Add Email IDs
--------------------------------

User can link and manage additional Email Id's in the system.

* To link an Email Id, Go to Connectivity section and click Additional Email Id's. 
* In the form that is available on screen, enter an Email Id and click Next. 

Issued OTP's
--------------------------------

A one time password (OTP) is a password that is valid for one login session or transaction. This is used when new user sign's 	up and system generates a password for the new account. Here, User can view and manage OTP's issued in the system. 

Set Default Application
--------------------------------------

The home page of the application will be available on start-up, if it is set as default. 

To set a default application for an account:

* On the User Account details form, click View Details and select Modify. The user details form will be available for changes. 
* Click Default Application, choose an application from the list, click Add and select Save. 

Now, the application Home page will be available on screen when user logs into the account. 

