pipeline {
    agent none
    stages{
        stage('printing statements'){
            parallel{
                stage('Print statement1'){
                    agent {label slave1}
                    steps { 
                        sh "echo "Hallo Good Morning" "
                          }
                          }
                    stage('print satatement2'){
                        agent {label slave1}
                        steps { 
                            sh "echo "hallo how are" "
                              }
                            }
                    }
                  }
                }
            }
