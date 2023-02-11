pipeline {
    agent any

    stages {
        stage('First stage') {
            steps {
                echo 'this is first stage'
            }
        }
    stage('Second Stage') {
        steps { 
             echo 'this is second stage'
        }
    }
    stage('Third Stage') {
       steps {
            echo 'this is third stage'
        }
     }
    stage('Fourth stage') {
       stage {
            echo 'this is fourth stage'
      }
     }
    }
}

