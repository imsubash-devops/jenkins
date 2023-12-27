pipeline {
     // Define the agent where the pipeline runs, using a Docker container with Python 3.9
    agent {
        docker {
            image 'python:3.9-alpine'
        }
    }
      // Define the stages of the pipeline
    stages {
         // Stage for testing
    stage('Test') {
         // Steps to be executed within the 'Test' stage
        steps {
                // Print the Python version
            sh 'python --version'
        }
    }
   }
}