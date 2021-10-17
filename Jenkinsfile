pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'MyGithubCred', url: 'https://github.com/akbar-alam/JenkinsJob'
            }
        }
    }
}
