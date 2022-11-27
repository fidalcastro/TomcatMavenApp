pipeline { 
    agent any
    tools {
        maven 'mvn-3.8.6'
    }
    stages {
        stage('Build') { 
            steps { 
                sh '''
                    echo "Added echo command"
                    mvn clean package
                '''
            }
        }
    }
}