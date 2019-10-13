pipeline {
    agent any
    stages {
        stage('npm build'){
            steps{
                println "npm build step"
                withNPM(npmrcConfig: '9cb9c651-591d-468e-b547-0ca1a50d8774') {
                    sh 'npm install'
                }
            }
        }
    }
}