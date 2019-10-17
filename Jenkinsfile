pipeline {
    agent any
    environment {
       color = 'blue'
   }
    stages {
        stage('build') {
            steps {
                bat 'set > env.txt' 
                for (String i : readFile('env.txt').split("\r?\n")) {
                    println i
                }
            }
        }
    }
}
