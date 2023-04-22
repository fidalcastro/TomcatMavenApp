pipeline { 
    agent any
    tools {
        maven 'mvn-3.9.1'
    }
    stages {
        stage('Build') { 
            steps { 
                sh '''
                    mvn clean package
                '''
            }
        }
    }
}
