pipeline {
  agent {label 'java'}
  stages{
    stage('checkout') {
      steps {
        sh 'rm -rf weather-forecast'
        sh 'git clone https://github.com/tarundanda147/weather-update.git'
   }
}
 stage('build') {
            steps {
                sh 'mvn --version'
                sh 'mvn clean install'
   
            }
        }
    }
}
