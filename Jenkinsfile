// pipeline {
//
//   agent {
//     label 'ansible'
//   }
//
//   stages {
//
//   stage('Hello') {
//    steps {
//       echo 'Hello World'
//    }
//   }
//
//   stage('Hello1') {
//      steps {
//         echo 'Hello World'
//      }
//     }
//
//     stage('Hello2') {
//        steps {
//           echo 'Hello World'
//           mail bcc: '', body: 'Hello this is a test email', cc: '', from: '', replyTo: '', subject: 'Test', to: 'chandrashekar2k10@gmail.com'
//        }
//       }
//
//   }
//
//   post {
//     always {
//       echo "sending mail"
//     }
//   }
// }

@Library('roboshop') _

pipeline {
   agent any
   stages {
   stage(test) {
   steps {
   script {
   env.abc = "Hello"
       def xyz = 10

       print "abc = ${abc}"
       print "xyz = ${xyz}"

       print abc

       def new1() {
       print "hello"
       }

       new1()


   }

   script {
        print "abc = ${abc}"
          }
   }


   }

   stage(test2) {
      steps {
      script {
      print "abc = ${abc}"
      }
      }
      }
   }
}