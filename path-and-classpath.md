### What is the difference between `PATH` and `CLASSPATH`?                

* CLASSPATH: Classpath is an environment variable which is used by the Java compiler to find the path, of classes. ie .class files. In J2EE we give the path of jar files. 
Example: To connect mysql database from our java program we need `mysql-connector.jar` and to run our program we must add this jar file location in classpath variable.

* PATH: Path is an environment variable which is used by the operating system to find the executables.                                     
Example:
  If we are going to compile java program using `javac` command without setting value of path variable compiler will not execut and it will say
  ```
  `javac` is not recognized as an internal or external command, operable program or batch file.
  ```
