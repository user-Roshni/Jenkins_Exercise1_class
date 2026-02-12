pipeline { 
  agent any 
  stages {
    stage ('version') {
       steps {
         bat '"C:\\Users\\Admin\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" --version'
       }
    } 
    stage ('Hello') {
      steps {
        bat '"C:\\Users\\Admin\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" Exercise1-python.py'
      }
    }
  }
}




