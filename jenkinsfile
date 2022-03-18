pipeline{
    agent any
    stages{
        stage('git clone') {
            steps{
              git 'https://github.com/venkatadrikurapati/example-tomcat-war.git'  
             }
            }
            stage('maven build'){
            steps{
                sh 'mvn package'
            }
        }
    }
}
