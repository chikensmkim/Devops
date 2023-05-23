pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '8200a365-0ea6-4061-8555-65210a4a00ce', url: 'https://github.com/chikensmkim/Devops.git'
            }
        }
    }
}
