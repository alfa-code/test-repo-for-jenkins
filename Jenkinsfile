pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        // stage('build') {
        //     steps {
        //         sh 'npm --version'
        //     }
        // }
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }

    }
}
