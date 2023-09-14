pipeline {
agent any
stages {
stage ('checkout') {
steps {
checkout scm
}}
stage ('Build') {
steps {
sh '/home/akash-1/Documents/Extractfiles/apache-maven-3.9.3/bin/mvn install'
}}
stage ('Deployment') {
steps {
sh 'cp target/grras5.war /home/akash-1/Documents/Extractfiles/apache-tomcat-9.0.76'
}}
}}

