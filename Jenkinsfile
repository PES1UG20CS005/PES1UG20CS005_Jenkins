pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'g++ -o output PES1UG20CS005.cpp'
            }
        }
        stage('Test') { 
            steps {
                sh 'cat PES1UG20CS005.cpp'
            }
        }
        stage('Deploy') { 
            steps {
                //sh './output'
                error 'Pipeline Failed' 
            }
        }
    }
    post{
        success{
            echo 'Pipeline Success'
        }
    	failure{
    		echo 'Pipeline Failed'
    	}
    }
}
