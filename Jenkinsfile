def name = "radhika"
def address = "chennai"
pipeline{
  agent any
    stages{
      stage(welcome){
       steps {
        echo "radhika"
       }
      }
      stage('varibledef'){
        steps {
           echo "hi my name is ${name} and address is ${address}"
       }
      }
    }
   }
