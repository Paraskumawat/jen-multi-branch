pipeline{
    agent none
    stages{
        stage('github'){
          agent {
                  label "myslavemaven" 

               }
          steps{
               echo "This is my alpha branch"

            }
        }
    }
}
