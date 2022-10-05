pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {

                echo 'Pulling...';
                git branch: 'main',
                url : 'https://github.com/feres5/TP_Achat_devops';

            }

        }


    stage('show Date') {
            steps {

                echo 'Showing Date...';
                sh """ date """;
            }

        }

    }

}

