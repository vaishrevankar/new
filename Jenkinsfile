pipeline {
    agent any
    tools{
        maven "Maven"
    }
    stages {

      stage('clean and buil')
            {
                steps
                 { 
                    sh 'mvn clean package'
                 }
            }
        }
    }