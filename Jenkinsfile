pipeline {
    agent {
    node {
        label 'python310'
        customWorkspace 'C:/Users/schaconcai/AppData/Local/Programs/Python/Python310/python.exe'
    }
}
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}