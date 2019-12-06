pipeline {
    agent any 
    
    environment {
      IAR_TOOL_PATH = "C:\\Program Files (x86)\\IAR Systems\\Embedded Workbench 8.3\\common\\bin:$IAR_TOOL_PATH"
    }
    
    stages {
        stage('Static Analysis') { 
            steps {
                echo "IAR PATH is: $IAR_TOOL_PATH"
            }
        }
        stage('Build') { 
            steps {
                gcc main.c -o main
            }
        }
        stage('Unit Test') { 
            steps {
                echo 'Unit Test'
            }
        }
        stage('Code Coverage') { 
            steps {
                echo 'Code Coverage'
            }
        }
    }
}
