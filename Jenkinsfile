pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
                mkdir build
                cd build
                cmake ..
                make
                ./hello
            }
        }
    }
}