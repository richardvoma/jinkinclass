pipeline {
    agent any
    tools {
        maven "Local Maven"
    }
    stages {
        stage('Checkout') {
            steps {
                // Get some code from a GitHub repository
                git url: 'https://github.com/richardvoma/jinkinclass.git', 
                    branch: 'jinkinclass',
                    credentialsId: '2c97cb71-1aca-415b-851c-5a96840c8f52'
            }
        }
    }
}
