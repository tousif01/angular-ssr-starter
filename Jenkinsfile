pipeline {
    agent any

    tools {nodejs "node"}

    stages {
        stage('npm build'){
            steps{
                println "npm build step"
                /*withNPM(npmrcConfig: '9cb9c651-591d-468e-b547-0ca1a50d8774') {
                    sh 'npm install'
                }*/
                /*nodejs(nodeJSInstallationName: 'node', configId: '9cb9c651-591d-468e-b547-0ca1a50d8774') {
                    sh 'npm config ls'
                }*/
                sh 'npm install'
            }
        }
    }
}