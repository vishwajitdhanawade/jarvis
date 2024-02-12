pipeline {
    agent any
    parameters {
        choice(name: 'executeStages', choices: ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10'], description: 'Select stages to execute')
    }
    stages {
        stage('Stage 1') {
            when {
                expression { params.executeStages.contains('1') }
            }
            steps {
                    echo "this is stage 1"
            }
        }
        stage('Stage 2') {
            when {
                expression { params.executeStages.contains('2') }
            }
            steps {
                
                  echo "this is stage 2"
			  }
        }
        
        stage('Stage 3') {
            when {
                expression { params.executeStages.contains('3') }
            }
            steps {
                echo "this is stage 3"
            }
        }
        
        stage('Stage 10') {
            when {
                expression { params.executeStages.contains('10') }
            }
            steps {
                echo "this is stage 10"
            }
        }
    }
}
