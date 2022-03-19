pipeline { 
    agent any 
        stages {
            stage ('Build') {
                agent { lable 'lable-01' }
                steps {
                   git branch: 'main', url: 'https://github.com/harishh1265/java-codes.git'
                    sh 'mvn clean install'
                  echo "build is success"
                }
            }
          stage ('Deploy') {
              agent { lable 'lable-01' }
                steps {
                  echo "build is success"
                }
             }
          stage ('Test') {
              agent { lable 'lable-01' }
                steps {
                  echo "build is success"
                }
          }
        }
}
