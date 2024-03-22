pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
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
