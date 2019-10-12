pipeline {
    agent any
    stages {
        stage('npm build'){
            step{
                withNPM(npmrcConfig: 'my-custom-nprc') {
                    sh 'npm install'
                }
            }
        }
    }
}