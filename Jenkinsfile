pipeline {
  environment {
    imagename = "santhiyaradhakrishnan/mynginxapp"
    registryCredential = 'santhiyaradhakrishnan(dockerhub token)'
    dockerImage = ''
    }
    agent any
    stages {
        stage('Git Clone') {
            steps {
                git([url: 'https://github.com/Santhiyakrishnanr29/jenkinsdemo.git', branch: 'master', credentialsId: 'Santhiyakrishnanr29(github token)'])
            }
        }
    }
}
