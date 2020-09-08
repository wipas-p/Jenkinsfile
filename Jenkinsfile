pipeline {
    //agent { label 'slave01' }
    stages {
        stage('Pullcode') {
            steps {
                git 'https://github.com/wipas-p/DemoSpringBoot.git'
            }
       }
       stage('Testing') {
          steps {
            echo "testing"
            
            // Windows use bat
            //bat "mvn clean package"
          }
        }

      }
}
