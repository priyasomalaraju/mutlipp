pipeline {   
    agent any

    stages {   
        stage('Main') { 
            steps { 
               sh 'echo "This is main branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
