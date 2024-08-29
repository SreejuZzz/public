pipeline {
  agent any

  stages {
    stage ('remove from DocumentRoot") {
           steps {
             sh 'echo "asd" | sudo -S rm -f /var/www/html/*
           }
    }
    stage ('copy to DocumentRoot') {
          steps {
            sh 'echo "asd" | sudo -S cp * /var/www/html/'
      }
    }
  }
}
