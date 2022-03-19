pipeline { 
    agent none 
        stages {
            stage ('Build') {
                agent {label 'slave02'}
                steps {
                   git branch: 'master', url: 'https://github.com/harishh1265/java-codes.git'
                    sh 'mvn clean install'
                  echo "build is success"
                }
            }
        }
}
