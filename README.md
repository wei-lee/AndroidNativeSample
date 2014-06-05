AndroidNativeSample
===================

Sample native android app to test import function on FH3.

To create the sample app, follow these steps:

* Create a new android app using Eclipse
  * Make sure choose minimum target to be 4.0+
  * Create a new activity if there is no one create in the src dir
* You will notice there is no build.xml file created. Run the following command

  ```
  android update project --name <appname> --target <apptarget> --path <apppath>
  ```

  This will create the build.xml file

* Make sure the ant task works locally

