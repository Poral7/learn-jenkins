/*

pipeline {

   agent {
     label 'ansible'
   }

   stages {

     stage('Hello') {
       steps {
         echo 'Hello world'
       }
     }
  }

 post {
   always {
     echo "sending email"
   }
    changed {
      echo "new change"
   }
 }

}
*/

@Library('roboshop') _

pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                script {
                    def abc = "hello"
                    def xyz = 10

                    print "abc = ${abc}"
                    print "xyz = ${xyz}"

                    print abc

                }
            }
        }
    }
}








