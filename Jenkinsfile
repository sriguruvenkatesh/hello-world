pipeline {
    agent any
    environment {
       color = 'blue'
   }
    stages {
        stage('build') {
            steps {
                 bat 'ECHO the value is: %MYSTRING%'
                 echo env.color
            }
        }
    }
}
