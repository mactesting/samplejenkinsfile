pipeline {
    agent any
    stages {
        stage('One') {
            steps {
                echo 'I am stage one'
            }
        }
        stage('Two') {
            steps {
                echo 'i am stage two'
                input('Shoud we proceed ?')
            }
        }
        stage('Three') {
            steps {
                echo 'I am final stage'
            }
        }
        
    }
}
