pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1 branch') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}