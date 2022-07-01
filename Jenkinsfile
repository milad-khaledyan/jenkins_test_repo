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
                cmakeBuild generator: 'Unix Makefiles', buildDir: 'build', installation: 'InSearchPath'
            }
        }
    }
}