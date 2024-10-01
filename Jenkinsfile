pipeline {

agent any


stages {

stage('GIT') {

           steps {

               git branch: 'master',

               url: 'https://github.com/Rabyous1/JenkinsTest.git'

          }

     }

stage ('Compile Stage') {

    steps {

        sh 'mvn clean compile'

    }

}

}

}