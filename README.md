1. add the checkstyle plugin to build.gradle file
2. add the checkstyle.xml file to the default directory config/checkstyle
3. add some checks to the checkstyle.xml file, here we add the line length check, the line should
   not be longer than 10 characters.
4. add the App class, add a line more than 10 character to a method.
5. go to the project directory, and run the command: gradle idea build
6. it will run the check style and put the result in the checkstyle.xml file.