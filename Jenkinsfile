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
                cmakeBuild generator: 'make', buildDir: 'build', installation: 'InSearchPath', steps: [[args: '-j12']]
            }
        }
    }
}