pipeline { 
  agent any 
  stages {
    stage ('version') {
       steps {
         bat '"\\Windows\\System32\\cmd.exe" /c python --version'
       }
    } 
    stage ('Hello') {
      steps {
        bat '"\\Windows\\System32\\cmd.exe" /c python Exercise1-python.py'
      }
    }
  }
}

