pipeline{
    
    agent any

    stages {

        stage('Git Checkout') {
        git branch: 'Master', credentialsId: 'gitcred', url: 'https://github.com/shankyz/testdevopsproject.git'
        }
    } 

}
