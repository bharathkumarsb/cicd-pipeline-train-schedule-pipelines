pipleline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo "Running Build Automation"
        sh './gradlew build --no-daemon'
        archiveartifacts artifacts 'dist/trainSchedule.zip'
        }
       }
     }
   }
