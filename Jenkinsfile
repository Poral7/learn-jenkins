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

/*
@Library('roboshop') _

pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                script {
                    env.abc = "hello"
                    def xyz = 10

                    print "abc = ${abc}"
                    print "xyz = ${xyz}"

                    print abc

                }
                script {
                    print "abc = ${abc}"
                }
            }
        }
        stage('test2'){
            steps {
                script {
                  print "abc = ${abc}"
                }
            }
        }
    }
}
*/

@Library('roboshop') _
test.new1()







