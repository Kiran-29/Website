node( ){
    stage ('Chekout'){
      https://github.com/Kiran-29/Website.git
    }
    stage ('Build'){
        echo build the website
    }
    stage ('Deploy'){
        sh 'cd /var/www/html sudo cp /var/lib/jenkins/workspace/kiran_29/* .'
    }
}
