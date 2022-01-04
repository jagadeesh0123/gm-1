pipeline {
    
    agent { label 'main' }

    tools{
            jdk 'Java8'
        maven 'maven3.3.9'
     }

    stages {
        
        stage('Git Clone') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/jagadeesh0123/gm-1.git'

            }

        }
        stage('Maven build') {
            steps {
                // Get some code from a GitHub repository
                sh  'mvn clean install '

            }
        }
    }
}
