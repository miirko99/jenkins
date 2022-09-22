pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh'''
                export a="hello world!"
                echo $a'''
            }
        }
    }
}
