pipeline { 
    agent none 
        stages {
            stage ('Build') {
                agent {label 'slave01'}
                steps {
                   git branch: 'main', url: 'https://github.com/harishh1265/java-codes.git'
                    sh 'mvn clean install'
                  echo "build is success"
                }
            }
        }
}
