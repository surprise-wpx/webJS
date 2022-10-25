pipeline {
  agent none
  stages {
    stage('test_stage') {
      environment {
        stage_var = 'stage_stage_value'
      }
      steps {
        echo '${stage_var}'
      }
    }

  }
  environment {
    stage_var = 'stage_value'
  }
}