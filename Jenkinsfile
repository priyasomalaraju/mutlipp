pipeline {   
    agent any

    stages {   
        stage('Main') { 
            steps { 
               sh 'echo "This is main branch"' 
            }
        }
     
        stage('sprint1 branch') { 
            steps { 
               sh 'echo "this is sprint1 application..."'
            }
        }

        stage("sprint2 branch") { 
             steps { 
                sh 'echo "this is sprint2 application..."'
            }
        }  
    }
}
