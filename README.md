# Build your own CRUD screens in Lift

This is example code for building your own CRUD screens in Lift.

To build and run:        
        $ cd scala-CRUD_Basic
        $ ./sbt
        >container:start

In a browser, go to http://localhost:8080 to see the app runing.

To import the project into Eclipse, from within Sbt:

        >eclipse with-source=true
        
Then from within Eclipse, File->Import -> Existing Projects into Workspace, and navigate to your scala-CRUD_Basic directory.
    
As a bonus ;-) the project comes with a suite of Selenium-based tests. To run the tests, from within Sbt:

        > test
        
You can see 100% test coverage of the Event and EventOps class using sbt-scct. 
