pipeline {
    agent any
    
    stages {
        stage ('SCM'){
            git 'git@github.com:BlackEmpireTO/test.git'
        }
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