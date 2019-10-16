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
                 echo "${env.BUILD_CAUSE_INFORMATION}"
                 echo "${env.MESSAGE_BUS_EXCHANGE_NAME}"
                 echo "${env.MESSAGE_BUS_COMPONENT_NAME}"
                 echo "${env.MESSAGE_BUS_USER_NAME}"
                 echo "${env.MESSAGE_BUS_PASSWORD}"
                 echo "${env.DOMAIN_ID}"
            }
        }
    }
}
