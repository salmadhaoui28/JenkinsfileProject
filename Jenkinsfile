pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Cloner le dépôt
                git branch: 'main', url: 'git@github.com:salmadhaoui28/JenkinsfileProject.git'
            }
        }

        stage('Build') {
            steps {
                // Ajouter votre commande de build ici
                sh 'echo "Building the project..."'
            }
        }

        stage('Test') {
            steps {
                // Ajouter vos tests ici
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                // Déployer l'application
                sh 'echo "Deploying the application..."'
            }
        }
    }
}
