pipeline {
  agent any
  stages{
    script{
      c['n1'] = stage('one') {
        stage('INIT'){
          steps{
            echo "That's it"
          }
        }
        stage('INIT'){
          steps{
            echo "That's it"
          }
        }
      }
      c['n2'] = stage('two') {
        stage('INIT'){
          steps{
            echo "That's it"
          }
        }
        stage('INIT'){
          steps{
            echo "That's it"
          }
        }
      }
      parallel c

    }
    
  }
}
