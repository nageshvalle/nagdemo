pipeline{
    agent any
      stages {
            stage('build') {
                steps {
                echo "buid"
            }
            }
            stage('testing') {
                steps {
                echo "testing"
                input "does this stage look ok?"
                }
            }
            stage('deploy') {
                steps {
                echo "deploying code"
                }
            }
                stage(create JIRA ticket') {
                      steps {
                          echo 'JIRA ticket'
                      }
                      }
            }
        }
    
