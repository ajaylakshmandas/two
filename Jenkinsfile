pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '59d28281-60c8-4274-87c4-4369bc590b38', url: 'https://github.com/ajaylakshmandas/one.git'], [credentialsId: '59d28281-60c8-4274-87c4-4369bc590b38', url: 'https://github.com/ajaylakshmandas/two.git'], [credentialsId: '59d28281-60c8-4274-87c4-4369bc590b38', url: 'https://github.com/ajaylakshmandas/three.git']]])       
            }
        }
    }
}
