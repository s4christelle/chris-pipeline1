pipeline {
    agent any
    environment {
       Country = "Camerooon"
       Name = "Joe"
    }



    stages {
        stage('build') {
            steps {
                sh '''
                mkdir joe
                echo $country
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
