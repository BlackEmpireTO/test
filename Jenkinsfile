pipeline {
    agent any

    tools {
        maven "maven"
        java "java"
    }
    
    stages {
        stage ('test') {
            steps {
                sh("mvn install")
            }
        // stage ('test') {
        //     steps {
        //         sh "echo 'K'"
        //     }
        // }
    }
}