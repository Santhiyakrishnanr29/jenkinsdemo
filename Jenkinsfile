pipeline {
  environment {
    imagename = "santhiyaradhakrishnan/mynginxapp"
    registryCredential = 'Sandy@29'
    dockerImage = ''
    }
    agent any
    stages {
        stage('Git Clone') {
            steps {
                git([url: 'https://github.com/Santhiyakrishnanr29/jenkinsdemo.git', branch: 'master', credentialsId: 'Santhiya@29'])
            }
        }
    }
}
