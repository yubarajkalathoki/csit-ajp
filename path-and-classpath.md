# What is the difference between `PATH` and `CLASSPATH`?

CLASSPATH: Classpath describe the location where required `.class` files are available. Java compiler and JVM uses it. If we are not setting class path program may not be compile and run.
PATH: Path is an environment variable which is used by the operating system to find the executables. 
Example:
  If we are going to compile java program using `javac` command without setting value of path variable compiler will not execut and it will say
  ```
  `javac` is not recognized as an internal or external command, operable program or batch file.
  ```
