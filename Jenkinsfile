pipeline {
  agent any
  stages{
    stage('uff') {
      script {
        n['1'] = stage('1'){
          steps{ echo "1" }
        }
        n['2'] = stage('2'){
          steps{ echo "2" }
        }
      }
     parallel n 
    }
    
  }
}
