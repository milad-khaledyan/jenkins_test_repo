pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Build') {
            steps {
                cmakeBuild buildDir: 'build', installation: 'InSearchPath', steps: [[withCmake: true]]
            }
        }
    }
}