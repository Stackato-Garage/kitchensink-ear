
Kitchensink Sample
=============

This is a full JEE6 sample. This example generates a EAR archive. As this is an EAR archive, Stackato uses JBoss server instead of TomEE.

Building the Application
------------------------

It is possible to build the application either with Ant or Maven.

### Maven

Make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

        mvn clean package

That will create the *moviefun.war* file within the 'app/target' directory.

Running the Application
-----------------------

To run the application, make sure you have the Stackato client installed and that you are logged in successfully for your desired target environment (e.g. http://api.stackato.local).

Then execute:

        stackato push -n 

Then go on your application url.

That's all. Have fun!
