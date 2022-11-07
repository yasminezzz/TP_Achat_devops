pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {

                echo 'Pulling...';
                git branch: 'main',
                url : 'https://github.com/yasminezzz/TP_Achat_devops';

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

