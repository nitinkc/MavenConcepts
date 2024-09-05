
`mvn clean`

`mvn package`


# Using plugins with maven
use plugin name with the task

` mvn compiler:compile`

` mvn dependency:tree`

`mvn clean`: This command is the most commonly used one. 
It tells Maven to execute the **clean phase of the default lifecycle**. 
In this phase, Maven deletes the target directory, which contains the 
build artifacts from previous builds. This helps ensure that you start with 
a fresh state for a new build.

`mvn clean:clean`: This command is more explicit. 
It invokes the clean goal of the clean plugin directly. 
It achieves the same result as mvn clean by deleting the target directory, 
but it's a bit more verbose. 
This can be useful if you want to specify different goals or configurations for the clean plugin.


