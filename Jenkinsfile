pipeline {
    agent any
    options {
  buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '2', numToKeepStr: '2')
    }
    environment {
       Country = "Camerooon"
       Name = "Joe"
    }



    stages {
        stage('build') {
            steps {
                sh '''
                mkdir joe
                echo $Country
                '''
            }
        }



        stage('test') {
            steps {
                sh '''
                echo $Name
                '''
            }
        }

        
        stage('deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
