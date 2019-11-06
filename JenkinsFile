pipeline {
     agent { label 'master' }
 
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('QA') {
            steps {
                echo 'Deployed on QA..'
            }
        }
        stage('Stage') {
            steps {
                echo 'Deployed on Stage....'
            }
        }
        stage('Prod') {
            steps {
                echo 'Deployed on Prod....'
            }
        }
    }
}
