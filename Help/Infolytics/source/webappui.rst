.. webappui:

Quick Tour - UI 
==========================

.. include:: ../../common/stub-overview.txt

.. |View| image:: common/images/viewicon.jpg

Infolytics application can be accessed from web-Application and Mobile App based on the user role. 
The web-application can be accessed by Super Admin, Admins and Coordinators where as the Field Users can access it from the App installed on the mobile devices.  

.. Note::*To install App on mobile, follow the link: `Install App on Mobile<http://docs.lmexcellence.com/HelpInfolytics/role_fielduser/mobileappinstall.html>`_ for more details.*

Home
--------------------------------
View displays all studies that are currently ongoing in the application. 

Select a Study from the application Home page, and click |View| View Icon. The Home page of the study with all the details is available on screen.  

Home Menu Tables:

===================  ============================================================
 Menu Options        Description
===================  ============================================================
Home  		         View all ongoing studies associated to the user. Select a Study, the Summary tab will display the following details.

     				 * New Visit: Shows new visits under the current study. User can mark visit for **Follow Up**, **Second Opinion** or **Normal**. 
    				 * Revisits: Displays visits being followed.
    				 * Second Opinion: Shows list of visits yet to be reviewed.
    				 * Potential Duplicates: Displays visits sharing similar data, Select a duplicate visit and associate it to a case. 
    				 * Follow Up: Shows list of visits that are pending for Follow Up.	
    				 * Normal: Show visits that were termed as *Normal**. Such cases can be marked for **Follow Up** or **Second Opnion**.

Scheduled Follow Up   Shows visits under all the studies that are pending for follow up. Select a visit to view the survey details. By default, the last visit details is displayed on screen.  
Follow Up Calendar   Shows calendar blocking of visits scheduled for Follow Up for the current month, week or day. 
Visit Maps	         Exact location of the study can be traced by adjusting and zooming in to the location pointed by Google Maps.
Survey Analysis		 For a study template, view data for a study based on the search criteria. 		  
===================  ============================================================

Planned Studies
--------------------------------

View displays all planned studies with details. The date of commencement of the study is indicated on the calendar.

**Planned Study table**:

================  ============================================================
 Menu Options     Description
================  ============================================================
Listing            Shows studies that are being scheduled. User can edit details, add users, permissions and create a new visit for the Study.
Calendar List      View calendar blocking of studies scheduled during the current month, week and day.
================  ============================================================

Manage
--------------------------------
View and manage all Study Templates, Studies, Cases, Visits, Follow Ups, Locations, User Permissions and Users with their current status on the timeline. 

**Manage tables:**

================  ============================================================
 Menu Options     Description
================  ============================================================
Study Templates   View all study templates created in the application. User can create new template, modify, publish or un-publish the current study template.
Studies        	  View, modify study schedules, locations and user permissions.
Cases	          Review, send for Follow Up, seek opinion or close case.		
Visits	                 
			 * New: Display new visits created under all studies in the application. User can mark the new visit for **Follow Up**, **Second Opinion** 				or **Normal**.
	                 * Possible Duplicates: Shows visits under all studies that share the same data with other visits. User can associate it to a case. 
	                 * In Review: Displays visits that were reviewed. Reviewed visits can be further sent for follow up, closed or deleted. 
		         * Follow Up: List of visits for which Follow Up visits were created. 
		         * Closed: Shows visits that are considered as normal and closed during the survey. Admin can review, re-open, Follow Up or delete these 						visits.  
		         * All: Lists all visits that are new, reviewed, marked for Follow Up, second opinion or closed under all published studies.  
			 * Synchronised Visits: List visits created using App and synced in to be published on to the web application.
Follow Ups	   Displays visits that are pending for Follow Up. User can create a visit for a Follow Up.
Locations          Shows current locations, user can create new location, and modify current location details. Refer: `Create Study Location`_ for more details. 
User Permissions   Show list of studies for which user roles are set. Select a study and modify user permissions.
Users	           Displays all registered users. Select a user to edit details, change password, activate, deactivate or delete user account. 
================  ============================================================

Analysis
--------------------------------
View lists out all studies for analysis. User can view study details and survey analysis of all case visits in the application.

Analysis table:

================  ============================================================
 Menu Options     Description
================  ============================================================
Studies            Shows list of active studies that are currently ongoing or completed. Select a study to view the schedule details. 
​				   
Survey Analysis    Select and add a Study Template to view data related to a particular search criteria. 
================  ============================================================

.. _Create Study Location

Create Study Location
--------------------------------
Study locations are associated to a study to know exactly where the survey is being conducted. Google Maps App points to the current location indicating the current dimensions for latitude and longitude.

To create a new location:

- On Manage menu drop-down, select Locations and click Create Locations. In the new location form, enter the name of the city in the Name text box.
- Select the **Is Active** checkbox. Add parent location for identifying the new location, choose a location and click Add.
- New location details will be automatically captured and marked on Google Maps. Both latitude and longitude for the current location will be automatically set. 
- Click Save, the new location will be available in the list when you are associating it to the study.  

.. image:: common/images/createlocation.png
