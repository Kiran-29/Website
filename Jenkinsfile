pipeline {
    agent any
    stages {
stage('scm') {
steps {
    git 'https://github.com/Kiran-29/Website.git'
    }
}
    stage('build') {
    steps {
        build
    }
    }
}
    stage('deploy') {
steps {
    bat 'cd /var/www/html sudo cp /var/lib/jenkins/workspace/kiran_29/* .'
    }
}
}
}
