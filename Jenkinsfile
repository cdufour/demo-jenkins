pipeline {
    agent any

    stages {
        stage('Stage1') {
            steps {
                sh '''
                echo "stage1"
                pwd
                '''
            }
        }
        stage('Stage2') {
            steps {
                sh '''
                chmod +x script1.sh
                ./script.sh
                '''
            }
        }
    }
}

  
