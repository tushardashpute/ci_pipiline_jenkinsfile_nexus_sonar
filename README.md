# ci_pipiline_jenkinsfile_nexus_sonar

Plugins required are :

Plugins installed on jenkins server:
=====================================
  sonaqube scanner  --> Required for sonarqube
  nexus artifact downloader  --> Required for nexus
  pipiline utility steps  --> Required to read the pom.xml file

Components server wise:
======================
  Jenkins Server  -->  git/java/maven/jenkins/sonar-scanner cli 
  Nexus Server    -->  java1.8/nexus3
  Sonar server    --> java 11 / sonarqube8.x
