pipeline { 
    agent any 
        stages {
            stage ('Build') {
                steps {
                   git branch: 'main', url: 'https://github.com/harishh1265/java-codes.git'
                  echo "build is success"
                }
            }
          stage ('Deploy') {
                steps {
                  echo "build is success"
                }
             }
          stage ('Test') {
                steps {
                  echo "build is success"
                }
          }
        }
}
