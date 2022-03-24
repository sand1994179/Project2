pipeline {
    agent { label slave2 }
    stages{
        stage('printing statements'){
            parallel{
                stage('Print statement1'){
                    steps { 
                        sh "echo 'Hallo Good Morning'"
                          }
                          }
                    stage('print satatement2'){
                        steps { 
                            sh "echo 'hallo how are'"
                              }
                            }
                    }
                  }
                }
            }
