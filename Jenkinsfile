pipeline {
      agent any
      stages {
  stage ('Check out'){
  steps {
          https://github.com/Kiran-29/Website.git
         }
     }
 }
   stage('Build') {
   steps {
          withMaven(maven : 'Maven') {
          bat "mvn clean install"
         }
    }
}
  stage ('Deploy'){
  steps {
         sh 'cd /var/www/html sudo cp /var/lib/jenkins/workspace/kiran-29/* .'
       }
  }
}
