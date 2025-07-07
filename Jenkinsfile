pipeline {
    agent any
    stages {
        stage ('Git') {
            steps {
                echo " my name is subhash"
            }
        }
        stage ('SonarCodeQuality') {
         steps{
            echo "code quality cheacking"   
        }

      }
      stage ('BuildTools') {
        steps {
            echo "building the application"
        }
      }
      stage ('Jenkins') {
        steps {
            echo "Code Quality checking"
        }
      }
      stage  ('Pipelines') {
        steps {
            echo "applicattion building"
        }
      }
      stage ('Docker') {
        steps {
            echo "docker images  building"
        }
      }
      stage ('Branch') {
        when {
            branch 'samsung/*'
        }
        steps {
        echo "addind branch"
        }
      }
      stage ('Tag') {
        steps {
            echo "tag parrtenn addding"
         }
       }
     }
   }
