pipeline {
    agent any

    tools {
        maven "maven"
    }
    
    stages {
        stage ('SCM'){
            git 'git@github.com:BlackEmpireTO/test.git'
        }
        stage ('test') {
            steps {
                sh("mvn install")
        }
    }
}