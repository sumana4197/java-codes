pipeline { 
    agent any 
        stages {
            stage ('Build') {
                agent {lable'lable-02'}
                steps {
                   git branch: 'master', url: 'https://github.com/harishh1265/java-codes.git'
                    sh 'mvn clean install'
                  echo "build is success"
                }
            }
          stage ('Deploy') {
              agent {lable'lable-02'}
                steps {
                  echo "build is success"
                }
             }
          stage ('Test') {
              agent {lable'lable-02'}
                steps {
                  echo "build is success"
                }
          }
        }
}
