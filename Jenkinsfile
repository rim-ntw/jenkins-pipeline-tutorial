pipeline{
  agent any
  stage{
      stage('Make Directory'){
        steps{
          sh "mkdir ~/jenkins-tutorial-test"
        }
      }
      stage('Make Files'){
        steps{
          sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
        }
      }
    }
}
