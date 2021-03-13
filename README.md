This is a simple web application with JSP, Servlets and an in memory H2 Database.  The application is deployable on tomcat.
This web application is part of the puzzle as we explore automating the migration of applications from weblogic to tomcat.
This application will serve as a source war that we will use as the deployable that we want to migrate from weblogic to tomcat.
This is kind of backwards that we are starting from a tomcat deployable.  
The intent is to start with a weblogic war that can be picked for migration.
We want to apply the Windup rules to the weblogic war and the result should be a target war that is deployable on tomcat.
We are starting with tomcat deployable as it is convenient.

Next steps:
Get this war to deploy on weblogic.
Add Weblogic specific features.
Codify identification of these features in Windup rules.
Run the windup tool with tomcat as target and generate report that identifies the weblogic features and provides migration recommendations.
Apply the recommendations where possible and generate target deployable.
End product is a war that is expected to run on weblogic.
