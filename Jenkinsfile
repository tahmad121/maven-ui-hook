node {
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace..'
     git url: 'https://github.com/Cenovus123/maven-ui-hook.git'
     checkout scm
   }
   stage('Build Test & Package') {
      echo 'Build the package'
      sh 'mvn clean compile package'
   }
   stage('Results') {
       echo 'Test Results are reported..'
   
   }
   stage('Deploy to Dev'){
       echo 'Deploy to Dev environment'
   }
   stage('Deploy to Test'){
       echo 'Deploy to Test environment'
   }
      stage('Test Automation'){
       echo 'Deploy to Dev environment'
       echo 'POLL will work'
   }
   
}
