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
                mkdir build
                cd build
                cmake ..
                make
                ./hello
            }
        }
    }
}