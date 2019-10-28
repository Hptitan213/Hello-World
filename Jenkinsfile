pipeline {
  agent any
  stages {
    stage('Lint HTML') {
      steps {
        sh '''pipeline {
  agent any
  stages {
    stage(\'Build\') {
      steps {
          sh \'echo "Hello World"\'
          sh \'\'\'
         echo \'Multiline shell steps works too\'
            ls -lah
         \'\'\'
      }
    }
  }
}'''
          echo 'Hello World'
        }
      }
      stage('') {
        steps {
          sh '''s3Upload(file:\'var/lib/jenkins/workspace/static_master/index.html\', bucket:\'s3:jenkinsudacityproject4.s3-website-us-west-1.amazonaws.com\')
'''
        }
      }
    }
  }