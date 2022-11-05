pipeline {
    agent any

    stages {
        stage('git') {
            steps {
                git branch: 'main', url: 'https://github.com/Hema3/terra_no.git'
            }
        }
        stage('Hello1') {
            steps {
               sh 'cp *' 
            }
        }
        stage('Hello2') {
            steps {
               build 'free-2' 
            }
        }
    }
}
