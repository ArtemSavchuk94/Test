pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "build"
                data >> index.html
            }
        }
        stage('Test') { 
            steps {
               echo  "test"
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploy"
            }
        }
    }
}
