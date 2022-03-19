pipeline { 
    agent any 
        stages {
            stage ('Build') {
                steps {
                   git branch: 'branch1', url: 'https://github.com/suman4197/multipipeline.git'
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
