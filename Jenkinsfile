pipeline {
  agent any
  triggers {
   cron('H/1 * * * *')
  }
  stages {
    stage('echo') {
      steps {
	echo 'welcome ya 3m'
      }
    }

  }
}
