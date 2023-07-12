//pipeline {
  //  agent any

    //stages {
      //  stage('Hello') {
        //    steps {
          //      echo 'Hello World'
           // }
        //}
    //}
//}
//scripted pipeline
node{
   stage('Test') {
    print 'Hello World'
    }
    if(env.BUILD_URL == "") {
    stage('Empty') {
      print 'Hello World'
    }
    } else {
       stage('Not Empty') {
       print 'Hello World'
       }
   }

}
