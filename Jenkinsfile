pipeline {
    agent any
    environment {
       color = 'blue'
   }
    stages {
        stage('build') {
            steps {
                 env.mycolor = red
                 echo env.mycolor
                 bat 'ECHO the value is: %MYSTRING%'
                 echo env.color
            }
        }
    }
}
