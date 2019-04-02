# JenkinSample
C:\Program Files (x86)\Jenkins

>java -jar jenkins.war

----------------
C:\Windows\system32>netstat -ano |findstr "8080"
  TCP    0.0.0.0:8080           0.0.0.0:0              LISTENING       1572
  TCP    [::]:8080              [::]:0                 LISTENING       1572

C:\Windows\system32>taskkill /f /pid 1572
SUCCESS: The process with PID 1572 has been terminated.
-----------------------

Browser: http://localhost:8080


	Please use the following password to proceed to installation:

	admin / e321d5bfecc64e769d4b7a96d31e9864

	This may also be found at: C:\Users\Admin\.jenkins\secrets\initialAdminPassword

Browser: 
   new Item
         Name : ProjectManager
         Choose Maven Project
                      click Ok at bottom

         Source Code Management
		Git
			https://github.com/SelvamThangaraj/ProjectManagerSample.git
		build
                   Goals and Options: verify
          Click Save button
 
------------------------
C:\Windows\system32>netstat -ano | findstr "8080"
  TCP    0.0.0.0:8080           0.0.0.0:0              LISTENING       1884
  TCP    [::]:8080              [::]:0                 LISTENING       1884

C:\Windows\system32>taskkill /f /pid 1884
SUCCESS: The process with PID 1884 has been terminated.

----------------------------
MAVEN_HOME:C:\java cognizant\apache-maven-3.5.0-bin\apache-maven-3.5.0


Git: https://github.com/SelvamThangaraj/SpringBootRestHibernateMySqlJUnit.git

http://www.tothenew.com/blog/how-to-setup-jenkins-for-a-maven-project/
