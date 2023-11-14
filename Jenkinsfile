pipeline {

    agent docker { image 'cferigan/flask-app'}

    stages {

        stage('Test') {

            steps {

                sh '''
                sh 'cferigan/flask-app'
                '''

            }

        }

    }

}