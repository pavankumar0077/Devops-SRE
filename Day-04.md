# JENKINS SHARED LIBRARY
# DEVSECOPS TOOLS -- SONAR, FORTIFY (CODE SCAN), TRIVY (DOCKER-IMAGE SCAN)
# HOW AN ATTACKER ATTACK YOUR WEBSITE
# PIPELINE WITH (SHARED LIBRARY) (Grovy script)
# PIPELINE SETUP ALONG WITH SHARED LIBRARY

# JENKINS SHARED LIBRARY

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/560ac0d9-59e8-423c-a598-126acdf677f7)

1) Only for similar tasks,
2) Makes the jenkins file simple
3) Re-use the code
4) Easyly understand, easy management
5) We can call the shared library as ```@Library('lib-name') _``` this shared library present in github wrote in grovvy script.
6) We can use one or more libraries

# SONAR

1) Code analysis -- Java, Node js, Python -- any type of code it will understand (22 + langs)
2) Duplicate lines  -- Repeating same lines of code, decting 
3) Test cases - pass or fail -- Dev's write junit test cases will pass or fail we have to code (Static analysis)
4) Code converage with test cases -- 10 lines of code demands 5 lines of test cases before going to dev or prod or etc
5) Bugs -- Related to appliation 
6) Vulnerabilites -- Making hacker to hope to hack the application
7) Code smells
8) Quality profiles
9) Quality gates

# FORTIFY (Security Tool)

1) Only for vilnerabilities
2) **It will pin point the vilnerbility and it will tell the solution as well**
3) If pipeline is failed at fortify will be fail the pipeline and it will send the report and we send that report to dev team.
4) DDOS, XML external entity attack, Values shading, password management(hardcoded password)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/f53ba45a-f039-4f12-8e88-abdc5aa00407)

