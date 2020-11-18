pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'WELCOME###\nhello from the trigger@@@\n@@\n@@\n@@\n@@\n@@\n'
      }
    }

  }
}
