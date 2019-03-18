node {
   stage('Preparation') {
      git 'https://github.com/inaminam/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}