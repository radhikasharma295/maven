pipeline{
  agent any
    stages{
      stage(welcome){
       steps {
        echo "radhika"
       }
      }
      stage('maven build'){
       steps {
        sh label: '', script: 'mvn clean package'
       }
      }
    }
   }
